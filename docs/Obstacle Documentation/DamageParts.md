---
title: Damage Parts
---

Damage parts are a normal [BasePart](https://create.roblox.com/docs/reference/engine/classes/BasePart) that deals damage to a player if their hitbox comes into contact with it. If the damage part has the tag `Hurt`, it will deal 1 heart of damage to the player. If the damage part has the tag `Kill`, it will instantly kill the player.

Additionally, a special string attribute named `KillType` can be applied to the damage part, which will trigger its corresponding hurt / death effect when the player touches it. If this attribute is not present, standard death & hurt animations will be ran instead.

The following damage types are available for `Hurt` parts:

- `Frozen` : The player's avatar will be bounced up a bit while slowly flailing its arms and legs from the cold.
- `Lava` : The player's avatar will be bounced up a bit while quickly flailing its arms and legs from the burn.

The following damage types are available for `Kill` parts:

- `Eaten` : The player's avatar will flail around a bit as it moves down into whatever is swallowing it, then ragdoll
- `Electrocuted` : The player's avatar will rapidly seize in-place as its skeleton flashes visible, then ragdoll
- `Falling` : The player's avatar will enter an uncontrolled fall animation. If the player hits the ground before a respawn is initiated, certain accessories such as shoes will fly off of the avatar and bounce up to the camera while the avatar faceplants.
- `Frozen` : The player's avatar will become encased in a cube of ice that will float to the surface of the damage part, and it will bob there until a respawn is initiated.
- `Portfish` : A giant portfish will jump out of the surface of the damage part and swallow the player. The portfish will then swim back to underneath the surface.
- `Squished` : The player's avatar will be flattened while a "SQUARSH!" sound plays. The avatar will then ragdoll.
- `WaterDrown` : The player's avatar will grab its neck and struggle for breathable air. The avatar will then go limp forward while floating in place.
- `Lava` : The player's avatar will be lit on fire as it quickly flails its arms and legs from the burn. The avatar is bounced upwards, and will then fall downwards, noclipping through anything in its path.
- `Poison` : The player's avatar will either immediately go limp, or it will flail around struggling to stay above the surface only to go limp after. The avatar will then slowly sink beneath the surface.

**Requirements**

- The damage part must have a tag of `Hurt` or `Kill`
- The damage part must not have any textures applied to it, the animated damage textures will be added at runtime by the game if applicable.
- The damage part must have a transparency of 0 if it has the tag `Hurt`.
- The damage part must have a material of `Neon` if it has the tag `Hurt`.

**Example** : [ExampleLava.rbxm](../Assets/ObstacleExamples/ExampleLava.rbxm)
---
title: Damage Parts
---

Damage parts are a normal [BasePart](https://create.roblox.com/docs/reference/engine/classes/BasePart) that deals damage to a player if their hitbox comes into contact with it.

**Requirements**

- The damage part must have a tag of "DamagePart"
- The damage part must not have any textures applied to it, the animated damage textures will be added at runtime by the game
- The damage part must have a transparency of 0
- The damage part must have a material of `Neon`

**Example** : [ExampleLava.rbxm](../Assets/ObstacleExamples/ExampleLava.rbxm)
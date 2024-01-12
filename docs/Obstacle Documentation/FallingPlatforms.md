---
title: Falling platforms
---

Falling platforms are a [Part](https://create.roblox.com/docs/reference/engine/classes/Part) with a beam particle and a crack decal that shakes & falls upon being stepped on by a player with a particle and texture parented to them. The delay before falling & speed of the fall cannot be custom-defined at this time.

**Rig:**

![](../Assets/images/ObstacleRigs/FallingPlatform_Rig.PNG)

**Requirements:**

- The falling platform must have a tag of "FallingPlatform"
- The texture & particles *must* be the ones that are provided in the example below. Custom particles & crack textures are not allowed at this time.
- The particle must match the color of the falling platform.
- Falling platforms must be anchored
- Falling platforms cannot be moved (e.g. they cannot be a projectile)

**Example** : [ExampleFallingPlatforms.rbxm](../Assets/ObstacleExamples/ExampleFallingPlatforms.rbxm)
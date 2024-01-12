---
title: Spinners
---

Spinners are a [Model](https://create.roblox.com/docs/reference/engine/classes/Model) containing a [physics assembly](https://create.roblox.com/docs/physics/assemblies) that relies on [HingeConstraint](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint)s to keep the assembly together & spinning. Unlike most obstacles, spinners have no structure requirements, other than the root being a model, and there being at least one `HingeConstraint` existing as a descendent of the model.

**Requirements:**

- The spinner's model must have a tag of "SpinnerRig"

**Example:** [ExampleSpinners.rbxm](../Assets/ObstacleExamples/ExampleSpinners.rbxm)
---
file_basename: Quicksand
file_dpath: Dynamic Terrain/Environmental Hazards
item_id: quicksand-level-3-hazard-hexer
item_index: '01'
item_name: Quicksand (Level 3 Hazard Hexer)
scc:
  - mcdm.monsters.v1:dynamic-terrain.environmental-hazard:quicksand-level-3-hazard-hexer
scdc:
  - 1.1.1:4.5:01
source: mcdm.monsters.v1
type: dynamic-terrain/environmental-hazard
---

###### Quicksand (Level 3 Hazard Hexer)

When this patch of sand is stepped on, it is revealed to be a slurry saturated by water—and ready to draw creatures down to their doom.

- **EV:** 3 per 10 x 10 patch
- **Stamina:** -
- **Size:** One or more squares

<!-- -->
> 🌀 **Deactivate**

<!-- -->
> ❕ **Activate**
>
> A creature or object enters the quicksand or starts their turn there.
>
> **Effect:** The **Grasping Depths** ability.

<!-- -->
> ❗️ **Grasping Depths**
>
> | **Melee, Strike** |                **Free triggered action** |
> | ----------------- | ---------------------------------------: |
> | **📏 Melee 0**    | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object enters the quicksand or starts their turn there.
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 slowed (save ends)
> - **12-16:** M < 1 restrained (save ends)
> - **17+:** M < 2 restrained (save ends)
>
> **Effect:** This ability takes a bane if a triggering creature shifted into the quicksand. A character who starts their turn restrained this way is suffocating.

<!-- -->
> ⭐️ **Hidden**
>
> The quicksand is hidden until triggered or detected.

---
file_basename: Toxic Plants
file_dpath: Dynamic Terrain/Environmental Hazards
item_id: toxic-plants-level-2-hazard-hexer
item_index: '05'
item_name: Toxic Plants (Level 2 Hazard Hexer)
scc:
  - mcdm.monsters.v1:dynamic-terrain.environmental-hazard:toxic-plants-level-2-hazard-hexer
scdc:
  - 1.1.1:4.5:05
source: mcdm.monsters.v1
type: dynamic-terrain/environmental-hazard
---

###### Toxic Plants (Level 2 Hazard Hexer)

Colorful mushrooms or lovely flowering plants release a cloud of spores or pollen when disturbed, causing creatures to fall into a magical slumber.

- **EV:** 2 per 10 x 10 field
- **Stamina:** 3 per square
- **Size:** One or more squares

<!-- -->
> 🌀 **Deactivate**
>
> Each square of plants must be individually destroyed.

<!-- -->
> ❕ **Activate**
>
> A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without shifting.
>
> **Effect:** The **Sleep Spores** ability.

<!-- -->
> ❗️ **Sleep Spores**
>
> | **Magic, Melee, Strike** |      **Free triggered action** |
> | ------------------------ | -----------------------------: |
> | **📏 Melee 0**           | **🎯 The triggering creature** |
>
> **Trigger:** A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without shifting.
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 dazed (save ends)
> - **12-16:** M < 1 dazed (save ends)
> - **17+:** M < 2 dazed (save ends)
>
> **Effect:** While dazed this way, a target who starts their turn in the area of the toxic plants falls prone and can't stand.

<!-- -->
> ⭐️ **Upgrades**
>
> **Poisonous Spores (+2 EV)** Any creature dazed by this hazard takes 1d6 poison damage at the start of each of their turns.
>
> **Carnivorous Plants (+2 EV)** The plants are carnivorous and attempt to slowly digest any creature who falls among them. Any creature who starts their turn prone in the area takes 4 acid damage.

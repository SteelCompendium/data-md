---
file_basename: Arrow Launcher
file_dpath: Dynamic Terrain/Siege Engines
item_id: arrow-launcher-level-2-siege-engine-artillery
item_index: '02'
item_name: Arrow Launcher (Level 2 Siege Engine Artillery)
scc:
  - mcdm.monsters.v1:dynamic-terrain.siege-engine:arrow-launcher-level-2-siege-engine-artillery
scdc:
  - 1.1.1:4.2:02
source: mcdm.monsters.v1
type: dynamic-terrain/siege-engine
---

###### Arrow Launcher (Level 2 Siege Engine Artillery)

A small wooden cart uses alchemical rockets to launch up to a hundred arrows at a time across a wide area.

- **EV:** 8
- **Stamina:** 30
- **Size:** 1L

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to an arrow launcher can make an **Agility test**.
>
> - **≤11:** The creature accidentally activates the **Arrow Storm** ability.
> - **12-16:** The arrow launcher is deactivated but the creature is slowed (EoT).
> - **17+:** The arrow launcher is deactivated and can't be used.

<!-- -->
> 🔳 **Arrow Storm**
>
> | **- Area, Ranged, Weapon** |         **Main action (Adjacent creature)** |
> | -------------------------- | ------------------------------------------: |
> | **📏 5 cube within 20**    | **🎯 Each creature and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 8 damage
> - **17+:** 11 damage
>
> **Effect:** This ability can't be used again until the arrow launcher is reloaded.

<!-- -->
> ⭐️ **Reload**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The arrow launcher is reloaded, allowing **Arrow Storm** to be used again. This action can be used only once per round.

<!-- -->
> ⭐️ **Spot**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The next use of **Arrow Storm** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.

<!-- -->
> ⭐️ **Move**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The arrow launcher and the creature using this action move together up to 3 squares.

<!-- -->
> ⭐️ **Upgrades**
>
> **Flaming Arrows (+1 EV) Arrow Storm** deals fire damage, and can ignite flammable objects in its area.
>
> **Screamers (+3 EV)** The arrows make a high-pitched screaming noise as they are fired and descend onto their targets. The **Screamers** ability replaces **Arrow Storm**.

<!-- -->
> 🔳 **Screamers**
>
> | **Area, Ranged, Weapon** |         **Main action (Adjacent creature)** |
> | ------------------------ | ------------------------------------------: |
> | **📏 5 cube within 20**  | **🎯 Each creature and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; R < 0 dazed (save ends)
> - **12-16:** 8 damage; R < 1 dazed (save ends)
> - **17+:** 11 damage; R < 2 frightened (save ends)
>
> **Effect:** This ability can't be used again until the arrow launcher is reloaded.

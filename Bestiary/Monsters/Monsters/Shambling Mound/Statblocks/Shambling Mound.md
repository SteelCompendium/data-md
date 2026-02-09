---
agility: -1
ancestry:
  - Plant
  - Shambling Mound
ev: '84'
file_basename: Shambling Mound
file_dpath: Monsters/Shambling Mound/Statblocks
free_strike: 7
intuition: 1
item_id: shambling-mound
item_index: '01'
item_name: Shambling Mound
level: 5
might: 4
presence: 0
reason: 0
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.shambling-mound.statblock:shambling-mound
scdc:
  - 1.1.1:2.49.1:01
size: '3'
source: mcdm.monsters.v1
speed: 3
stability: 5
stamina: '400'
type: monster/shambling-mound/statblock
---

###### Shambling Mound

| Plant, Shambling Mound |          -          |       Level 5        |          Solo           |         EV 84          |
| :--------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|    **3**<br/> Size     |  **3**<br/> Speed   | **400**<br/> Stamina |  **5**<br/> Stability   | **7**<br/> Free Strike |
|  **-**<br/> Immunity   | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|   **+4**<br/> Might    | **-1**<br/> Agility |  **0**<br/> Reason   |  **+1**<br/> Intuition  |  **0**<br/> Presence   |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the shambling mound can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The shambling mound can take two turns each round. They can't take turns consecutively.

<!-- -->
> ⭐️ **Engulfing Sac**
>
> The shambling mound has a vegetative sack on their body where they carry engulfed creatures. The sack has 30 Stamina, damage immunity 5, and fire weakness 10. Destroying the sack frees creatures trapped by the shambling mound's Engulf ability. The shambling mound regrows a destroyed sack at the start of their next turn.

<!-- -->
> 🗡 **Vine Lash (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 6**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; A < 3 grabbed
> - **12-16:** 16 damage; A < 4 grabbed
> - **17+:** 19 damage; grabbed
>
> **2 Malice:** The shambling mound can slide each target up to 6 squares.
>
> **3 Malice:** Each target takes 7 poison damage.

<!-- -->
> ❇️ **Seismic Slam**
>
> | **Area, Weapon** |               **Main action** |
> | ---------------- | ----------------------------: |
> | **📏 6 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 4 damage; M < 2 dazed (save ends)
> - **12-16:** 6 damage; M < 3 dazed (save ends)
> - **17+:** 7 damage; M < 4 dazed (save ends)

<!-- -->
> 🗡 **Engulf (2 Malice)**
>
> | **Melee**      |               **Main action** |
> | -------------- | ----------------------------: |
> | **📏 Melee 6** | **🎯 One creature or object** |
>
> **Effect:** The target must be size 1L or smaller. The shambling mound reaches out with writhing vines, and if the target has A < 3, they are engulfed into the shambling mound's sack. If the target is grabbed by the shambling mound, the potency increases by 1. An engulfed creature is restrained, takes 3 poison damage at the start of each turn, and can't take damage from abilities used from outside the sack. When the shambling mound moves, the engulfed creature moves with them. If the shambling mound dies or their sack is destroyed, each engulfed creature is freed and appears in an unoccupied space within 2 squares of the shambling mound.
>
> **2+ Malice:** The shambling mound can engulf one additional target for each 2 Malice spent.

<!-- -->
> 👤 **Leech**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Each creature engulfed by the shambling mound takes 5 poison damage. The shambling mound gains 5 temporary Stamina for each creature who takes damage this way.

<!-- -->
> ❗️ **Tether Down**
>
> | **Melee**      |           **Triggered action** |
> | -------------- | -----------------------------: |
> | **📏 Melee 6** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance willingly moves.
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 restrained (EoT)
> - **12-16:** 12 damage; M < 3 restrained (EoT)
> - **17+:** 15 damage; M < 4 restrained (EoT)

<!-- -->
> ⭐️ **False Appearance**
>
> While the shambling mound remains motionless, they are indistinguishable from ordinary vegetation.

<!-- -->
> ⭐️ **Frothing Flora**
>
> The area within 6 squares of the shambling mound is difficult terrain.

<!-- -->
> ☠️ **Ravenous Overgrowth (Villain Action 1)**
>
> | **Area, Weapon**            |                            **-** |
> | --------------------------- | -------------------------------: |
> | **📏 10 x 2 line within 1** | **🎯 Each creature in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage, pull 3
> - **12-16:** 12 damage; pull 4; the target has poison weakness 3 until the end of the encounter
> - **17+:** 15 damage; pull 6; the target has poison weakness 5 until the end of the encounter

<!-- -->
> ☠️ **Composting (Villain Action 2)**
>
> | **Melee**      |             **-** |
> | -------------- | ----------------: |
> | **📏 Melee 6** | **🎯 Each enemy** |
>
> **Effect:** The shambling mound uses Engulf against each target without spending Malice.

<!-- -->
> ☠️ **Exposed Crux (Villain Action 3)**
>
> | **Melee**   |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The shambling mound rips themself apart, exposing the crux of magic holding them together. The distance of the shambling mound's melee abilities increases to melee 10, the creature has a double edge on power rolls, and strikes made against them gain an edge.

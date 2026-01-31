---
agility: 2
ancestry:
  - Humanoid
  - Orc
ev: '6'
file_basename: Orc Chainlock
file_dpath: Monsters/Orcs/Statblocks
free_strike: 3
intuition: 0
item_id: orc-chainlock
item_index: '03'
item_name: Orc Chainlock
level: 1
might: 2
presence: 0
reason: 1
roles:
  - Platoon Hexer
scc:
  - mcdm.monsters.v1:monster.orcs.statblock:orc-chainlock
scdc:
  - 1.1.1:2.15.1:03
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: '20'
type: monster/orcs/statblock
---

###### Orc Chainlock

|    Humanoid, Orc    |          -          |       Level 1       |      Platoon Hexer      |          EV 6          |
| :-----------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|  **1L**<br/> Size   |  **5**<br/> Speed   | **20**<br/> Stamina |  **2**<br/> Stability   | **3**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  | **+2**<br/> Agility | **+1**<br/> Reason  |  **+0**<br/> Intuition  |  **+0**<br/> Presence  |

<!-- -->
> 🗡 **Hook and Chain (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; pull 1; M < 0 the target is hooked (save ends)
> - **12-16:** 7 damage; pull 2; M < 1 the target is hooked (save ends)
> - **17+:** 9 damage; pull 3; M < 2 the target is hooked (save ends)
>
> **Effect:** A hooked target can't move more than 3 squares away from the chainlock's position when this ability is used.

<!-- -->
> 🏹 **Heavy Crossbolt (3 Malice)**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> | -------------------------- | ----------------------------: |
> | **📏 Ranged 5**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; A < 0 slowed (save ends)
> - **12-16:** 7 damage; A < 1 slowed (save ends)
> - **17+:** 9 damage; prone; A < 2 slowed (save ends)

<!-- -->
> ⭐️ **Chain Link**
>
> Whenever the chainlock is force moved by a creature's melee ability, the creature is pulled the same distance toward the chainlock after the forced movement is resolved.

<!-- -->
> ⭐️ **Relentless**
>
> If the chainlock is reduced to 0 Stamina, they can make a free strike before dying. If the target of the free strike is reduced to 0 Stamina, the chainlock is reduced to 1 Stamina instead.

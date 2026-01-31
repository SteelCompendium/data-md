---
agility: 2
ancestry:
  - Undead
  - Soulless
ev: '3'
file_basename: Skeleton
file_dpath: Monsters/Undead/Statblocks
free_strike: 2
intuition: 0
item_id: skeleton
item_index: '32'
item_name: Skeleton
level: 1
might: 0
presence: -1
reason: 1
roles:
  - Horde Artillery
scc:
  - mcdm.monsters.v1:monster.undead.statblock:skeleton
scdc:
  - 1.1.1:2.8.1:32
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: '10'
type: monster/undead/statblock
---

###### Skeleton

|             Undead, Soulless             |          -          |       Level 1       |     Horde Artillery     |          EV 3          |
| :--------------------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|             **1M**<br/> Size             |  **5**<br/> Speed   | **10**<br/> Stamina |  **0**<br/> Stability   | **2**<br/> Free Strike |
| **Corruption 1, poison 1**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|             **0**<br/> Might             | **+2**<br/> Agility | **+1**<br/> Reason  |  **0**<br/> Intuition   |  **-1**<br/> Presence  |

<!-- -->
> ⚔️ **Bone Shards (Signature Ability)**
>
> | **Melee, Ranged, Strike, Weapon** |               **Main action** |
> | --------------------------------- | ----------------------------: |
> | **📏 Melee 1 or ranged 10**       | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage
> - **17+:** 7 damage
>
> **Effect:** Until the start of the skeleton's next turn, the target takes 2 damage the first time they willingly move on their turn.

<!-- -->
> ❇️ **Bone Spur (2 Malice)**
>
> | **Area, Weapon** |                  **Maneuver** |
> | ---------------- | ----------------------------: |
> | **📏 1 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 1 damage; M < 0 bleeding (save ends)
> - **12-16:** 2 damage; M < 1 bleeding (save ends)
> - **17+:** 3 damage; M < 2 bleeding (save ends)
>
> **Effect:** Each target takes a bane on their next strike.

<!-- -->
> ⭐️ **Arise**
>
> The first time the skeleton is reduced to 0 Stamina by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 1 Stamina and fall prone.

---
agility: 1
ancestry:
  - Humanoid
  - Radenwight
ev: '6'
file_basename: Radenwight Bruxer
file_dpath: Monsters/Radenwights/Statblocks
free_strike: 4
intuition: 0
item_id: radenwight-bruxer
item_index: '01'
item_name: Radenwight Bruxer
level: 1
might: 2
presence: 1
reason: -1
roles:
  - Platoon Brute
scc:
  - mcdm.monsters.v1:monster.radenwights.statblock:radenwight-bruxer
scdc:
  - 1.1.1:2.18.1:01
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: '40'
type: monster/radenwights/statblock
---

###### Radenwight Bruxer

| Humanoid, Radenwight |            -            |       Level 1       |      Platoon Brute      |          EV 6          |
| :------------------: | :---------------------: | :-----------------: | :---------------------: | :--------------------: |
|   **1L**<br/> Size   |    **5**<br/> Speed     | **40**<br/> Stamina |  **2**<br/> Stability   | **4**<br/> Free Strike |
| **-**<br/> Immunity  | **Climb**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might   |   **+1**<br/> Agility   | **-1**<br/> Reason  |  **0**<br/> Intuition   |  **+1**<br/> Presence  |

<!-- -->
> 🗡 **Lockjaw (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage; grabbed
>
> **Effect:** A target grabbed this way takes 2 damage at the start of each of the bruxer's turns.

<!-- -->
> ❇️ **Flurry of Bites (3 Malice)**
>
> | **Area, Weapon** |               **Main action** |
> | ---------------- | ----------------------------: |
> | **📏 1 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; A < 0 bleeding (save ends)
> - **12-16:** 5 damage; A < 1 bleeding (save ends)
> - **17+:** 8 damage; A < 2 bleeding (save ends)

<!-- -->
> ❗️ **Ready Rodent**
>
> | **Melee, Weapon** | **Triggered action** |
> | ----------------- | -------------------: |
> | **📏 Melee 1**    |  **🎯 One creature** |
>
> **Trigger:** An ally deals damage to the target.
>
> **Effect:** The bruxer makes a free strike against the target.

<!-- -->
> ⭐️ **Lockdown**
>
> Any enemy who shifts adjacent to the bruxer has that shift end. Additionally, any enemy adjacent to the bruxer can't shift.

---
agility: 1
ancestry:
  - Accursed
  - Humanoid
  - Minotaur
ev: '20'
file_basename: Minotaur Sunderer
file_dpath: Monsters/Minotaurs/Statblocks
free_strike: 6
intuition: 2
item_id: minotaur-sunderer
item_index: '04'
item_name: Minotaur Sunderer
level: 3
might: 2
presence: -1
reason: 0
roles:
  - Elite Brute
scc:
  - mcdm.monsters.v1:monster.minotaurs.statblock:minotaur-sunderer
scdc:
  - 1.1.1:2.21.1:04
size: '2'
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: '120'
type: monster/minotaurs/statblock
---

###### Minotaur Sunderer

| Accursed, Humanoid, Minotaur |          -          |       Level 3        |       Elite Brute       |         EV 20          |
| :--------------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|       **2**<br/> Size        |  **6**<br/> Speed   | **120**<br/> Stamina |  **2**<br/> Stability   | **6**<br/> Free Strike |
|     **-**<br/> Immunity      | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|      **+2**<br/> Might       | **+1**<br/> Agility |  **0**<br/> Reason   |  **+2**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Spiked Maul (Signature Ability)**
>
> | **Charge, Melee, Strike, Weapon** |                 **Main action** |
> | --------------------------------- | ------------------------------: |
> | **📏 Melee 2**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage; pull 1
> - **12-16:** 12 damage; pull 2
> - **17+:** 15 damage; pull 3
>
> **Effect:** A target pulled adjacent to the sunderer is automatically grabbed.

<!-- -->
> ❇️ **Fearsome Bay (5 Malice)**
>
> | **Area**       |               **Main action** |
> | -------------- | ----------------------------: |
> | **📏 3 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** I < 0 frightened (save ends)
> - **12-16:** I < 1 frightened (save ends)
> - **17+:** I < 2 frightened (save ends)
>
> **Effect:** Until the end of their next turn, the minotaur has damage immunity 2 and deals an extra 5 damage with strikes.

<!-- -->
> 🗡 **Disemboweling Horns (3 Malice)**
>
> | **Charge, Melee, Strike, Weapon** |        **Maneuver** |
> | --------------------------------- | ------------------: |
> | **📏 Melee 2**                    | **🎯 One creature** |
>
> **Special:** The target must be grabbed by the sunderer.
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; M < 0 bleeding (save ends)
> - **12-16:** 8 damage; M < 1 bleeding (save ends)
> - **17+:** 9 damage; M < 2 bleeding (save ends)
>
> **Effect:** While bleeding this way, the target takes 1d6 damage at the start of each of their turns.

<!-- -->
> ❗️ **Retaliatory Strike**
>
> | **Ranged**      |           **Triggered action** |
> | --------------- | -----------------------------: |
> | **📏 Ranged 6** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the sunderer.
>
> **Effect:** The sunderer uses the Charge main action and Spiked Maul against the target.

<!-- -->
> ⭐️ **Minotaur Sense**
>
> The sunderer can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.

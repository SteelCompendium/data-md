---
agility: 3
ancestry:
  - Beast
  - Wyvern
ev: '24'
file_basename: Wyvern Lurker
file_dpath: Monsters/Wyverns/Statblocks
free_strike: 6
intuition: 1
item_id: wyvern-lurker
item_index: '01'
item_name: Wyvern Lurker
level: 4
might: 2
presence: 0
reason: -1
roles:
  - Elite Ambusher
scc:
  - mcdm.monsters.v1:monster.wyverns.statblock:wyvern-lurker
scdc:
  - 1.1.1:2.14.1:01
size: '2'
source: mcdm.monsters.v1
speed: 9
stability: 2
stamina: '120'
type: monster/wyverns/statblock
---

###### Wyvern Lurker

|      Beast, Wyvern       |           -           |       Level 4        |     Elite Ambusher      |         EV 24          |
| :----------------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|     **2**<br/> Size      |   **9**<br/> Speed    | **120**<br/> Stamina |  **2**<br/> Stability   | **6**<br/> Free Strike |
| **Acid 5**<br/> Immunity | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|    **+2**<br/> Might     |  **+3**<br/> Agility  |  **-1**<br/> Reason  |  **+1**<br/> Intuition  |  **0**<br/> Presence   |

<!-- -->
> 🗡 **Agonizing Stinger (Signature Ability)**
>
> | **Magic, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage
> - **12-16:** 14 damage; M < 2 bleeding (save ends)
> - **17+:** 17 damage; M < 3 bleeding (save ends)
>
> **1 Malice:** One target hidden from the lurker takes an extra 6 acid damage.

<!-- -->
> 🗡 **Acidic Anguish (3 Malice)**
>
> | **Magic, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 acid damage; M < 1 weakened (save ends)
> - **12-16:** 16 acid damage; M < 2 weakened (save ends)
> - **17+:** 20 acid damage; M < 3 weakened (save ends)
>
> **Effect:** A target weakened this way takes 1d4 acid damage at the start of each of their turns.

<!-- -->
> 👤 **Swooping Torment**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The lurker flies up to their speed, then can attempt to hide. Each enemy the lurker moves adjacent to during this movement can choose to take 3 sonic damage or fall prone.

<!-- -->
> ❗️ **Retaliatory Dive**
>
> | **Ranged**      |           **Triggered action** |
> | --------------- | -----------------------------: |
> | **📏 Ranged 5** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the lurker with a ranged ability.
>
> **Effect:** The lurker flies adjacent to the target and can make a free strike against them.

<!-- -->
> ⭐️ **Ruthless Rage**
>
> While within 10 squares of another wyvern, the lurker deals an extra 3 damage with strikes.

<!-- -->
> ⭐️ **Tenacious Hunter**
>
> Any creature affected by a condition imposed by a wyvern can't be hidden from the lurker.

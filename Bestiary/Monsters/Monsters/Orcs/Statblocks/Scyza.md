---
agility: -1
ancestry:
  - Animal
  - Orc
ev: '20'
file_basename: Scyza
file_dpath: Monsters/Orcs/Statblocks
free_strike: 5
intuition: 0
item_id: scyza
item_index: 09
item_name: Scyza
level: 3
might: 2
presence: -1
reason: -4
roles:
  - Elite Mount
scc:
  - mcdm.monsters.v1:monster.orcs.statblock:scyza
scdc:
  - 1.1.1:2.16.1:09
size: '4'
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: '100'
type: monster/orcs/statblock
---

###### Scyza

|     Animal, Orc     |          -          |       Level 3        |       Elite Mount       |         EV 20          |
| :-----------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|   **4**<br/> Size   |  **6**<br/> Speed   | **100**<br/> Stamina |  **3**<br/> Stability   | **5**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  | **-1**<br/> Agility |  **-4**<br/> Reason  |  **+0**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Clawed Kick (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage; prone
> - **17+:** 14 damage; prone
>
> **Effect:** The scyza roars, and if the target has I < 2, they are frightened (save ends).

<!-- -->
> 🗡 **Whiptail**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage
> - **12-16:** 13 damage; prone
> - **17+:** 16 damage; A < 2 bleeding (save ends)
>
> **Effect:** Against a target on top of the scyza, this ability gains an edge, and the target is pushed into an unoccupied adjacent square and knocked prone.

<!-- -->
> 🔳 **Crestfall (2 Malice)**
>
> | **Area, Ranged, Weapon** |               **Main action** |
> | ------------------------ | ----------------------------: |
> | **📏 3 cube within 2**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage, 1 sonic damage; R < 0 dazed (save ends)
> - **12-16:** 7 damage, 2 sonic damage; R < 1 dazed (save ends)
> - **17+:** 9 damage, 3 sonic damage; R < 2 dazed (save ends)

<!-- -->
> ❇️ **Sandstorm (3 Malice)**
>
> | **Area**       |   **Maneuver** |
> | -------------- | -------------: |
> | **📏 3 burst** | **🎯 Special** |
>
> **Effect:** The scyza kicks up a sandstorm, granting concealment to themself and any ally in the area until the end of the scyza's next turn. Each enemy in the area makes an Intuition test.
>
> - **≤11:** 10 damage; prone; slowed (EoT)
> - **12-16:** 7 damage; slowed (EoT)
> - **17+:** 4 damage

<!-- -->
> ❗️ **Brace and Break**
>
> | **-**       | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The scyza or an ally riding the scyza is targeted by an ability.
>
> **Effect:** Any damage dealt by the triggering ability is halved. If the creature or object who used the ability is within 3 squares of the scyza, the scyza can make a free strike against them.

<!-- -->
> ⭐️ **Terrible Beast**
>
> The scyza deals an extra 6 damage with abilities used against objects.

<!-- -->
> ⭐️ **War Harness**
>
> While riding the scyza, three size 1 allies can occupy the same space.

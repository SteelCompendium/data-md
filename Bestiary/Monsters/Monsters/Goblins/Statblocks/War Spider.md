---
agility: 1
ancestry:
  - Animal
  - Goblin
ev: '12'
file_basename: War Spider
file_dpath: Monsters/Goblins/Statblocks
free_strike: 4
intuition: 0
item_id: war-spider
item_index: '11'
item_name: War Spider
level: 1
might: 2
presence: -3
reason: -4
roles:
  - Elite Mount
scc:
  - mcdm.monsters.v1:monster.goblins.statblock:war-spider
scdc:
  - 1.1.1:2.39.1:11
size: '3'
source: mcdm.monsters.v1
speed: 7
stability: 2
stamina: '60'
type: monster/goblins/statblock
---

###### War Spider

|   Animal, Goblin    |            -            |       Level 1       |       Elite Mount       |         EV 12          |
| :-----------------: | :---------------------: | :-----------------: | :---------------------: | :--------------------: |
|   **3**<br/> Size   |    **7**<br/> Speed     | **60**<br/> Stamina |  **2**<br/> Stability   | **4**<br/> Free Strike |
| **-**<br/> Immunity | **Climb**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  |   **+1**<br/> Agility   | **-4**<br/> Reason  |  **0**<br/> Intuition   |  **-3**<br/> Presence  |

<!-- -->
> 🗡 **Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 poison damage
> - **12-16:** 11 poison damage
> - **17+:** 14 poison damage; M < 2 weakened (save ends)
>
> **2 Malice:** For any tier outcome, if the target has M < 3, they are weakened (save ends).

<!-- -->
> 🗡 **Leg Blade**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage

<!-- -->
> 👤 **Trample (5 Malice)**
>
> | **-**       | **Main action** |
> | ----------- | --------------: |
> | **📏 Self** |     **🎯 Self** |
>
> **Effect:** The spider shifts up to their speed and uses Leg Blade against each creature who comes adjacent to them during the shift. The spider makes one power roll against all targets.

<!-- -->
> 🔳 **Web**
>
> | **Area, Weapon**       |                     **Maneuver** |
> | ---------------------- | -------------------------------: |
> | **📏 3 cube within 1** | **🎯 Each creature in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** A < 0 restrained (save ends)
> - **12-16:** A < 1 restrained (save ends)
> - **17+:** A < 2 restrained (save ends)
>
> **Effect:** The area is difficult terrain for enemies.

<!-- -->
> ❗️ **Skitter**
>
> | **-**       | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The spider or any ally riding the spider takes damage.
>
> **Effect:** The damage is halved, and the spider shifts up to 2 squares after the triggering effect resolves.

<!-- -->
> ⭐️ **Ride Launcher**
>
> Any ally who leaps off the back of the spider can jump up to 6 squares without making a test, and takes no damage if they fall during the jump. After any ally jumps, the first melee strike the make on the same turn gains an edge.

<!-- -->
> ⭐️ **Wide Back**
>
> While riding the spider, two size 1 allies can occupy the same space.

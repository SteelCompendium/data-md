---
agility: 1
ancestry:
  - Undead
ev: '9'
file_basename: Dirt Mournling
file_dpath: Monsters/Undead/Statblocks
free_strike: 3
intuition: 1
item_id: dirt-mournling
item_index: '22'
item_name: Dirt Mournling
level: 7
might: 4
presence: -3
reason: -2
roles:
  - Horde Controller
scc:
  - mcdm.monsters.v1:monster.undead.statblock:dirt-mournling
scdc:
  - 1.1.1:2.8.1:22
size: '3'
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: '64'
type: monster/undead/statblock
---

###### Dirt Mournling

|                  Undead                  |                -                |       Level 7       |    Horde Controller     |          EV 9          |
| :--------------------------------------: | :-----------------------------: | :-----------------: | :---------------------: | :--------------------: |
|             **3**<br/> Size              |        **6**<br/> Speed         | **64**<br/> Stamina |  **3**<br/> Stability   | **3**<br/> Free Strike |
| **Corruption 7, poison 7**<br/> Immunity | **Burrow, climb**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|            **+4**<br/> Might             |       **+1**<br/> Agility       | **-2**<br/> Reason  |  **+1**<br/> Intuition  |  **-3**<br/> Presence  |

<!-- -->
> 🗡 **Mudslide (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 3 grabbed
> - **12-16:** 10 damage; M < 4 grabbed
> - **17+:** 11 damage; grabbed
>
> **Effect:** A 3-cube area of ground centered on the target is difficult terrain for enemies.

<!-- -->
> ❇️ **Mourning Cry (3 Malice)**
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 3 corruption damage; I < 2 frightened (save ends)
> - **12-16:** 6 corruption damage; I < 3 frightened (save ends)
> - **17+:** 7 corruption damage; I < 4 frightened (save ends)
>
> **Effect:** A target frightened this way is frightened of all undead. This effect ends early if the mournling is destroyed.

<!-- -->
> ⭐️ **Arise**
>
> The first time the mournling is reduced to 0 Stamina by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 15 Stamina and fall prone.

<!-- -->
> ⭐️ **Immutable Form**
>
> The mournling's shape can't be changed by any external effect.

<!-- -->
> ⭐️ **Rupture**
>
> Whenever the mournling uses the Dig maneuver to breach the surface, they make a free strike against each adjacent enemy.

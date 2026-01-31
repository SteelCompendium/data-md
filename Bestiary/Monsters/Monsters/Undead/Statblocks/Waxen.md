---
agility: -2
ancestry:
  - Undead
  - Soulless
ev: '9'
file_basename: Waxen
file_dpath: Monsters/Undead/Statblocks
free_strike: 4
intuition: 1
item_id: waxen
item_index: '12'
item_name: Waxen
level: 7
might: 4
presence: -2
reason: -4
roles:
  - Horde Artillery
scc:
  - mcdm.monsters.v1:monster.undead.statblock:waxen
scdc:
  - 1.1.1:2.8.1:12
size: 1M
source: mcdm.monsters.v1
speed: 4
stability: 2
stamina: '40'
type: monster/undead/statblock
---

###### Waxen

|             Undead, Soulless             |          -          |       Level 7       |     Horde Artillery     |          EV 9          |
| :--------------------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|             **1M**<br/> Size             |  **4**<br/> Speed   | **40**<br/> Stamina |  **2**<br/> Stability   | **4**<br/> Free Strike |
| **Corruption 7, poison 7**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|            **+4**<br/> Might             | **-2**<br/> Agility | **-4**<br/> Reason  |  **+1**<br/> Intuition  |  **-2**<br/> Presence  |

<!-- -->
> 🏹 **Wax Fling (Signature Ability)**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> | -------------------------- | ----------------------------: |
> | **📏 Ranged 15**           | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 8 damage
> - **12-16:** 11 damage
> - **17+:** 12 damage; A < 4 slowed (save ends)
>
> **Effect:** If a target made slowed this way is already slowed, they are instead restrained (save ends).

<!-- -->
> ❇️ **Erupt (3 Malice)**
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 2 burst**  | **🎯 Each enemy in the area** |
>
> **Effect:** If the waxen is ignited (see Burn Bright), they shift up to their speed before using this ability. Each target makes an **Agility test**.
>
> - **≤11:** 10 damage
>
> - **12-16:** 8 damage
>
> - **17+:** 5 damage
>
> - The waxen is then destroyed and the area is difficult terrain for enemies.

<!-- -->
> ⭐️ **Burn Bright**
>
> If the waxen takes fire damage, they ignite. While ignited, the waxen takes 4 fire damage at the start of each of their turns and their strikes deal an extra 4 fire damage.

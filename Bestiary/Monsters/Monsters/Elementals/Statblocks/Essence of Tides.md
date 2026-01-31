---
agility: 0
ancestry:
  - Elemental
ev: '20'
file_basename: Essence of Tides
file_dpath: Monsters/Elementals/Statblocks
free_strike: 5
intuition: -1
item_id: essence-of-tides
item_index: '01'
item_name: Essence of Tides
level: 3
might: 2
presence: 2
reason: 1
roles:
  - Elite Controller
scc:
  - mcdm.monsters.v1:monster.elementals.statblock:essence-of-tides
scdc:
  - 1.1.1:2.40.1:01
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: '80'
type: monster/elementals/statblock
---

###### Essence of Tides

|        Elemental         |           -            |       Level 3       |    Elite Controller     |         EV 20          |
| :----------------------: | :--------------------: | :-----------------: | :---------------------: | :--------------------: |
|     **1M**<br/> Size     |    **7**<br/> Speed    | **80**<br/> Stamina |  **1**<br/> Stability   | **5**<br/> Free Strike |
| **Cold 5**<br/> Immunity | **Swim**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|    **+2**<br/> Might     |  **+0**<br/> Agility   | **+1**<br/> Reason  |  **-1**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🗡 **Water Wing (Signature Ability)**
>
> | **Magic, Melee, Strike** |                 **Main action** |
> | ------------------------ | ------------------------------: |
> | **📏 Melee 1**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; slide 1
> - **12-16:** 11 damage; slide 2
> - **17+:** 14 damage; slide 3
>
> **Effect:** If a target has P < 2, their stability is reduced to 0 and they move 2 additional squares whenever they are force moved (save ends).

<!-- -->
> 🏹 **Convocation of Waves**
>
> | **Magic, Ranged** |                 **Maneuver** |
> | ----------------- | ---------------------------: |
> | **📏 Ranged 5**   | **🎯 Self or one elemental** |
>
> **Effect:** Until the start of the essence's next turn, the target has cold immunity 5.
>
> **3 Malice:** Until the end of the encounter, the ground within 1 square of the target is a pool of water that is difficult terrain. This water extends out behind the target as they move, creating a stream that lasts until the end of the encounter. Any enemy who ends their turn in the stream and has M < 2 is slowed (save ends).

<!-- -->
> ❗️ **Sea-Salted Wounds (1 Malice)**
>
> | **Melee**      | **Triggered action** |
> | -------------- | -------------------: |
> | **📏 Melee 1** |     **🎯 One enemy** |
>
> **Trigger:** An ally deals rolled damage to the target.
>
> **Effect:** The essence makes a free strike against the target.

<!-- -->
> ⭐️ **Fickle and Free**
>
> The essence can't be restrained, slowed, or knocked prone, and they ignore difficult terrain.

<!-- -->
> ⭐️ **Water Glide**
>
> Whenever the essence starts their turn in a space containing water, they can fly until the end of their turn. While flying, the essence doesn't provoke opportunity attacks.

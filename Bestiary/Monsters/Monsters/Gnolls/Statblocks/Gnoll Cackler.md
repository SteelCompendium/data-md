---
agility: 0
ancestry:
  - Abyssal
  - Gnoll
ev: '4'
file_basename: Gnoll Cackler
file_dpath: Monsters/Gnolls/Statblocks
free_strike: 2
intuition: 2
item_id: gnoll-cackler
item_index: '07'
item_name: Gnoll Cackler
level: 2
might: 0
presence: 2
reason: 2
roles:
  - Horde Hexer
scc:
  - mcdm.monsters.v1:monster.gnolls.statblock:gnoll-cackler
scdc:
  - 1.1.1:2.6.1:07
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: '15'
type: monster/gnolls/statblock
---

###### Gnoll Cackler

|   Abyssal, Gnoll    |          -          |       Level 2       |       Horde Hexer       |          EV 4          |
| :-----------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|  **1S**<br/> Size   |  **5**<br/> Speed   | **15**<br/> Stamina |  **1**<br/> Stability   | **2**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **0**<br/> Might   | **0**<br/> Agility  | **+2**<br/> Reason  |  **+2**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🏹 **Moment of Brutality (Signature Ability)**
>
> | **Magic, Ranged, Strike** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 8**           | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 psychic damage; I < 0 the target makes a free strike against a creature of the cackler's choice
> - **12-16:** 5 psychic damage; I < 1 the target makes a free strike against a creature of the cackler's choice
> - **17+:** 7 psychic damage; I < 2 the target uses a signature ability against a creature of the cackler's choice
>
> **Effect:** An ally targeted by this ability ignores the damage and can make a free strike.

<!-- -->
> ❇️ **Cackler's Cackletongue (4 Malice)**
>
> | **Area, Magic** |                     **Maneuver** |
> | --------------- | -------------------------------: |
> | **📏 2 burst**  | **🎯 Each creature in the area** |
>
> **Effect:** Each enemy target makes an **Intuition test**. If any target hasn't used their own Cackletongue maneuver on this turn, they can use it immediately at no cost.
>
> - **≤11:** Frightened (save ends)
> - **12-16:** Frightened (EoT)
> - **17+:** No effect

<!-- -->
> ⭐️ **Death Frenzy**
>
> Whenever a non-minion ally within 5 squares of the cackler is reduced to 0 Stamina, the cackler moves up to their speed and can make a melee free strike.

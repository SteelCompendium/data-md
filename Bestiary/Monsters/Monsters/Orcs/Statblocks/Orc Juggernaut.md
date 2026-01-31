---
agility: 2
ancestry:
  - Humanoid
  - Orc
ev: '10'
file_basename: Orc Juggernaut
file_dpath: Monsters/Orcs/Statblocks
free_strike: 5
intuition: -1
item_id: orc-juggernaut
item_index: '15'
item_name: Orc Juggernaut
level: 3
might: 2
presence: 2
reason: -1
roles:
  - Platoon Brute
scc:
  - mcdm.monsters.v1:monster.orcs.statblock:orc-juggernaut
scdc:
  - 1.1.1:2.15.1:15
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: '60'
type: monster/orcs/statblock
---

###### Orc Juggernaut

|    Humanoid, Orc    |          -          |       Level 3       |      Platoon Brute      |         EV 10          |
| :-----------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|  **1L**<br/> Size   |  **6**<br/> Speed   | **60**<br/> Stamina |  **0**<br/> Stability   | **5**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  | **+2**<br/> Agility | **-1**<br/> Reason  |  **-1**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🗡 **Haymaker Greataxe (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage; prone
> - **17+:** 14 damage; prone; M < 2 bleeding (save ends)
>
> **Effect:** A target who is already prone takes an extra 6 damage.

<!-- -->
> ❗️ **Hrraaaaaagh! (1 Malice)**
>
> | **-**       | **Free triggered action** |
> | ----------- | ------------------------: |
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** The juggernaut takes damage.
>
> **Effect:** The juggernaut moves up to their speed and can make a free strike.

<!-- -->
> ⭐️ **Blood in the Water**
>
> Whenever the juggernaut willingly moves, they can move 3 additional squares if they end their movement closer to a prone creature.

<!-- -->
> ⭐️ **Relentless**
>
> If the juggernaut is reduced to 0 Stamina, they can make a free strike before dying. If the target of the free strike is reduced to 0 Stamina, the juggernaut is reduced to 1 Stamina instead.

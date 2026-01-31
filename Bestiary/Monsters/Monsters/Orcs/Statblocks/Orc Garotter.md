---
agility: 2
ancestry:
  - Humanoid
  - Orc
ev: '6'
file_basename: Orc Garotter
file_dpath: Monsters/Orcs/Statblocks
free_strike: 4
intuition: 1
item_id: orc-garotter
item_index: '13'
item_name: Orc Garotter
level: 1
might: 1
presence: -1
reason: 0
roles:
  - Platoon Ambusher
scc:
  - mcdm.monsters.v1:monster.orcs.statblock:orc-garotter
scdc:
  - 1.1.1:2.15.1:13
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: '30'
type: monster/orcs/statblock
---

###### Orc Garotter

|    Humanoid, Orc    |          -          |       Level 1       |    Platoon Ambusher     |          EV 6          |
| :-----------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|  **1L**<br/> Size   |  **5**<br/> Speed   | **30**<br/> Stamina |  **0**<br/> Stability   | **4**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+1**<br/> Might  | **+2**<br/> Agility | **+0**<br/> Reason  |  **+1**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Dagger Feint (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage; the garroter can shift 1 square
> - **12-16:** 9 damage; the garroter shifts up to 2 squares
> - **17+:** 12 damage; the garroter shifts up to 3 squares
>
> **Effect:** If this ability gains an edge or has a double edge, it deals an extra 4 damage.

<!-- -->
> 🗡 **Strangle**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage; I < 1 dazed (save ends)
> - **17+:** 12 damage; grabbed; I < 2 dazed (save ends)
>
> **Effect:** While grabbed this way, a target can't communicate or use magic abilities.

<!-- -->
> 👤 **Chroma Cloak (1 Malice)**
>
> | **-**    | **Maneuver** |
> | -------- | -----------: |
> | **📏 -** |     **🎯 -** |
>
> The garroter turns invisible until the end of their turn. This invisibility ends early if they take damage or use an ability.

<!-- -->
> ⭐️ **Relentless**
>
> If the garroter is reduced to 0 Stamina, they can make a free strike before dying. If the target of the free strike is reduced to 0 Stamina, the garroter is reduced to 1 Stamina instead.

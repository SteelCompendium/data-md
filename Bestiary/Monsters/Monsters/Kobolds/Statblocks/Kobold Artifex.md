---
agility: 2
ancestry:
  - Humanoid
  - Kobold
ev: '3'
file_basename: Kobold Artifex
file_dpath: Monsters/Kobolds/Statblocks
free_strike: 1
intuition: 0
item_id: kobold-artifex
item_index: '03'
item_name: Kobold Artifex
level: 1
might: 0
presence: 0
reason: 1
roles:
  - Horde Controller
scc:
  - mcdm.monsters.v1:monster.kobolds.statblock:kobold-artifex
scdc:
  - 1.1.1:2.10.1:03
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: '10'
type: monster/kobolds/statblock
---

###### Kobold Artifex

|  Humanoid, Kobold   |          -          |       Level 1       |    Horde Controller     |          EV 3          |
| :-----------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|  **1S**<br/> Size   |  **5**<br/> Speed   | **10**<br/> Stamina |  **0**<br/> Stability   | **1**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **0**<br/> Might   | **+2**<br/> Agility | **+1**<br/> Reason  |  **0**<br/> Intuition   |  **0**<br/> Presence   |

<!-- -->
> 🏹 **Chain Hook (Signature Ability)**
>
> | **Ranged, Strike, Weapon** |               **Main action** |
> | -------------------------- | ----------------------------: |
> | **📏 Ranged 5**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; pull 1
> - **12-16:** 4 damage; pull 2
> - **17+:** 5 damage; pull 3
>
> **Effect:** If this forced movement triggers a trap that uses a power roll, that roll has a double edge.

<!-- -->
> ⭐️ **Activate Trap**
>
> | **Ranged**       |                            **Maneuver** |
> | ---------------- | --------------------------------------: |
> | **📏 Ranged 10** | **🎯 One trap or other terrain object** |
>
> **Effect:** The trap or terrain object instantly triggers.
>
> **3 Malice:** The artifex places a new trap in the encounter and can instantly trigger it. The artifex prefers working with angry beehives, flammable oil, snare traps, and spike traps (see Dynamic Terrain).

<!-- -->
> ⭐️ **Shield? Shield!**
>
> While adjacent to an ally who also has this trait, the artifex has stability 1, has cover, and grants cover to allies.

---
agility: 0
ancestry:
  - Dwarf
  - Humanoid
ev: '10'
file_basename: Dwarf Shieldwall
file_dpath: Monsters/Dwarves/Statblocks
free_strike: 5
intuition: 0
item_id: dwarf-shieldwall
item_index: '12'
item_name: Dwarf Shieldwall
level: 3
might: 2
presence: 1
reason: 0
roles:
  - Platoon Defender
scc:
  - mcdm.monsters.v1:monster.dwarves.statblock:dwarf-shieldwall
scdc:
  - 1.1.1:2.51.1:12
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: '72'
type: monster/dwarves/statblock
---

###### Dwarf Shieldwall

|   Dwarf, Humanoid   |          -          |       Level 3       |    Platoon Defender     |         EV 10          |
| :-----------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|  **1M**<br/> Size   |  **5**<br/> Speed   | **72**<br/> Stamina |  **4**<br/> Stability   | **5**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  | **+0**<br/> Agility | **+0**<br/> Reason  |  **+0**<br/> Intuition  |  **+1**<br/> Presence  |

<!-- -->
> 🗡 **Wide Axe (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; slide 1
> - **12-16:** 10 damage; slide 1
> - **17+:** 13 damage; slide 1
>
> **Effect:** The shieldwall can shift 1 square to remain adjacent to the target. A target restrained by a dwarf can be force moved by this ability. This forced movement doesn't end the restrained condition unless the Director determines otherwise.
>
> **3 Malice:** This ability targets one additional target.

<!-- -->
> ❗️ **Intercepting Shield (1 Malice)**
>
> | **-**       | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** A creature makes a strike against an ally adjacent to the shieldwall.
>
> **Effect:** The shieldwall becomes the target of the triggering strike and halves the damage.

<!-- -->
> ⭐️ **Call to the Wall**
>
> Whenever a creature deals damage to or takes damage from the shieldwall, the shieldwall can make that creature taunted until the end of the creature's next turn.

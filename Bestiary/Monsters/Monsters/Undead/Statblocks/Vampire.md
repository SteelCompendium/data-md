---
agility: 2
ancestry:
  - Undead
  - Vampire
ev: '9'
file_basename: Vampire
file_dpath: Monsters/Undead/Statblocks
free_strike: 3
intuition: 1
item_id: vampire
item_index: '19'
item_name: Vampire
level: 7
might: 4
presence: 1
reason: 1
roles:
  - Horde Hexer
scc:
  - mcdm.monsters.v1:monster.undead.statblock:vampire
scdc:
  - 1.1.1:2.8.1:19
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 3
stamina: '40'
type: monster/undead/statblock
---

###### Vampire

|             Undead, Vampire              |            -            |       Level 7       |       Horde Hexer       |          EV 9          |
| :--------------------------------------: | :---------------------: | :-----------------: | :---------------------: | :--------------------: |
|             **1M**<br/> Size             |    **6**<br/> Speed     | **40**<br/> Stamina |  **3**<br/> Stability   | **3**<br/> Free Strike |
| **Corruption 7, poison 7**<br/> Immunity | **Climb**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|            **+4**<br/> Might             |   **+2**<br/> Agility   | **+1**<br/> Reason  |  **+1**<br/> Intuition  |  **+1**<br/> Presence  |

<!-- -->
> 🗡 **Exsanguinating Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 bleeding (save ends)
> - **12-16:** 10 corruption damage; M < 3 5 corruption damage and bleeding (save ends)
> - **17+:** 11 corruption damage; M < 4 7 corruption damage and bleeding (save ends)
>
> **Effect:** The vampire regains Stamina equal to any corruption damage dealt.

<!-- -->
> 🗡 **Vicious Pursuit (3 Malice)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; A < 2 slowed (save ends)
> - **12-16:** 10 damage; A < 3 slowed (save ends)
> - **17+:** 11 damage; A < 4 slowed (save ends)
>
> **Effect:** If the target is bleeding, the vampire shifts up to their speed before using this ability.

<!-- -->
> ❗️ **Reactive Charm (2 Malice)**
>
> | **Magic, Ranged** | **Triggered action** |
> | ----------------- | -------------------: |
> | **📏 Ranged 5**   |     **🎯 One enemy** |
>
> **Trigger:** A creature makes a strike against the vampire.
>
> **Effect:** The target becomes the new target of the strike.

<!-- -->
> ⭐️ **Unslakable Bloodthirst**
>
> The vampire has speed 10 while any creature within 10 squares of them is bleeding. The vampire must make a strike against a bleeding creature on their turn if they are able to.

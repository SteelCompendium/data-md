---
agility: -1
ancestry:
  - Mummy
  - Undead
ev: '6'
file_basename: Mummy
file_dpath: Monsters/Undead/Statblocks
free_strike: 3
intuition: 3
item_id: mummy
item_index: 09
item_name: Mummy
level: 4
might: 3
presence: 0
reason: 1
roles:
  - Horde Brute
scc:
  - mcdm.monsters.v1:monster.undead.statblock:mummy
scdc:
  - 1.1.1:2.8.1:09
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: '50'
type: monster/undead/statblock
---

###### Mummy

|              Mummy, Undead               |          -          |       Level 4       |       Horde Brute       |           EV 6           |
| :--------------------------------------: | :-----------------: | :-----------------: | :---------------------: | :----------------------: |
|             **1M**<br/> Size             |  **5**<br/> Speed   | **50**<br/> Stamina |  **2**<br/> Stability   |  **3**<br/> Free Strike  |
| **Corruption 4, poison 4**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain | **Fire 5**<br/> Weakness |
|            **+3**<br/> Might             | **-1**<br/> Agility | **+1**<br/> Reason  |  **+3**<br/> Intuition  |   **0**<br/> Presence    |

<!-- -->
> 🗡 **Accursed Bindings (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 corruption damage; pull 1
> - **12-16:** 8 corruption damage; pull 2
> - **17+:** 10 corruption damage; pull 2; M < 3 restrained (save ends)
>
> **Effect:** The next ability the mummy uses against the target has any potency increased by 1 for the target.

<!-- -->
> 🏹 **Eldritch Curse (3 Malice)**
>
> | **Magic, Ranged** |     **Main action** |
> | ----------------- | ------------------: |
> | **📏 Ranged 10**  | **🎯 One creature** |
>
> **Power Roll + 3:**
>
> - **≤11:** 3 corruption damage; I < 1 the target is cursed (save ends)
> - **12-16:** 5 corruption damage; I < 2 the target is cursed (save ends)
> - **17+:** 7 corruption damage; I < 3 the target is cursed (save ends)
>
> **Effect:** A cursed target is bleeding and weakened, and allies gain an edge on strikes made against them.

<!-- -->
> ❗️ **Blast of Mummy Dust (1 Malice)**
>
> | **Area**       |           **Triggered action** |
> | -------------- | -----------------------------: |
> | **📏 1 burst** | **🎯 The triggering creature** |
>
> **Trigger:** The mummy comes within distance of a restrained creature or starts their turn within distance of one.
>
> **Effect:** The target takes 8 poison damage.

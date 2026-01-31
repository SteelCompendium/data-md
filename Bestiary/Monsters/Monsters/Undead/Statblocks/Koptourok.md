---
agility: 2
ancestry:
  - Undead
ev: '9'
file_basename: Koptourok
file_dpath: Monsters/Undead/Statblocks
free_strike: 3
intuition: 1
item_id: koptourok
item_index: '07'
item_name: Koptourok
level: 7
might: 4
presence: -1
reason: 0
roles:
  - Horde Hexer
scc:
  - mcdm.monsters.v1:monster.undead.statblock:koptourok
scdc:
  - 1.1.1:2.8.1:07
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: '40'
type: monster/undead/statblock
---

###### Koptourok

|                  Undead                  |          -          |       Level 7       |       Horde Hexer       |          EV 9          |
| :--------------------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|             **1M**<br/> Size             |  **5**<br/> Speed   | **40**<br/> Stamina |  **1**<br/> Stability   | **3**<br/> Free Strike |
| **Corruption 7, poison 7**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|            **+4**<br/> Might             | **+2**<br/> Agility |  **0**<br/> Reason  |  **+1**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Choking Grasp (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 5**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 7 damage; M < 2 grabbed
> - **12-16:** 10 damage; M < 3 grabbed
> - **17+:** 11 damage; M < 4 grabbed
>
> **Effect:** A creature grabbed this way is suffocating. The koptourok can have up to two creatures grabbed at once.

<!-- -->
> ❇️ **Inhale (3 Malice)**
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** Pull 3; M < 2 5 corruption damage
> - **12-16:** Pull 5; M < 3 5 corruption damage
> - **17+:** Pull 7; M < 4 5 corruption damage
>
> **Effect:** This ability gains an edge against any target grabbed by the koptourok. If one or more targets are pulled adjacent to the koptourok, the koptourok can fly until the end of the encounter.

<!-- -->
> ⭐️ **Exhale**
>
> The first time the koptourok is made winded by damage that isn't fire damage or holy damage, each enemy within 3 squares of them takes 8 corruption damage. Any enemy who takes this damage and has M < 3 is also weakened (save ends)

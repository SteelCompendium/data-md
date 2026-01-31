---
agility: 1
ancestry:
  - Undead
  - Soulless
ev: '3'
file_basename: Zombie
file_dpath: Monsters/Undead/Statblocks
free_strike: 2
intuition: -2
item_id: zombie
item_index: '27'
item_name: Zombie
level: 1
might: 2
presence: 1
reason: -5
roles:
  - Horde Brute
scc:
  - mcdm.monsters.v1:monster.undead.statblock:zombie
scdc:
  - 1.1.1:2.8.1:27
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: '20'
type: monster/undead/statblock
---

###### Zombie

|             Undead, Soulless             |          -          |       Level 1       |       Horde Brute       |          EV 3          |
| :--------------------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|             **1M**<br/> Size             |  **5**<br/> Speed   | **20**<br/> Stamina |  **1**<br/> Stability   | **2**<br/> Free Strike |
| **Corruption 1, poison 1**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|            **+2**<br/> Might             | **+1**<br/> Agility | **-5**<br/> Reason  |  **-2**<br/> Intuition  |  **+1**<br/> Presence  |

<!-- -->
> 🗡 **Clobber and Clutch (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage
> - **17+:** 7 damage; grabbed
>
> **Effect:** A target who starts their turn grabbed by the zombie takes 2 corruption damage. A creature who takes 5 or more corruption damage this way becomes insatiably hungry for flesh, and must complete the Find a Cure downtime project in Draw Steel: Heroes to end this effect.

<!-- -->
> ❇️ **Zombie Dust (3 Malice)**
>
> | **Area**       |                  **Maneuver** |
> | -------------- | ----------------------------: |
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** The zombie falls prone, expelling a wave of rot and dust.
>
> **Power Roll + 2:**
>
> - **≤11:** 2 corruption damage
> - **12-16:** 3 corruption damage; M < 1 weakened (save ends)
> - **17+:** 4 corruption damage; M < 2 dazed (save ends)

<!-- -->
> ⭐️ **Endless Knight**
>
> The first time the zombie is reduced to 0 Stamina by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 10 Stamina and fall prone.

---
agility: 2
ancestry:
  - Humanoid
  - Orc
ev: '20'
file_basename: Orc Warleader
file_dpath: Monsters/Orcs/Statblocks
free_strike: 5
intuition: 2
item_id: orc-warleader
item_index: '06'
item_name: Orc Warleader
level: 3
might: 3
presence: 2
reason: 1
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.orcs.statblock:orc-warleader
scdc:
  - 1.1.1:2.15.1:06
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: '120'
type: monster/orcs/statblock
---

###### Orc Warleader

|    Humanoid, Orc    |          -          |       Level 3        |         Leader          |         EV 20          |
| :-----------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|  **1M**<br/> Size   |  **6**<br/> Speed   | **120**<br/> Stamina |  **2**<br/> Stability   | **5**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+3**<br/> Might  | **+2**<br/> Agility |  **+1**<br/> Reason  |  **+2**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🏹 **Go. (Signature Ability)**
>
> | **Ranged**       | **Main action** |
> | ---------------- | --------------: |
> | **📏 Ranged 10** | **🎯 One ally** |
>
> **Effect:** The target moves up to their speed and can use a main action.
>
> **1 Malice:** The warleader targets two allies.
>
> **3 Malice:** The warleader targets one ally and a minion squad.

<!-- -->
> 🗡 **Mace Lariat**
>
> | **Melee, Strike, Weapon** |   **Main action** |
> | ------------------------- | ----------------: |
> | **📏 Melee 1**            | **🎯 Each enemy** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 damage; push 1; M < 1 dazed (save ends)
> - **12-16:** 10 damage; push 3; M < 2 dazed (save ends)
> - **17+:** 13 damage; push 5; M < 3 dazed (save ends)

<!-- -->
> 🏹 **Lockdown (3 Malice)**
>
> | **Ranged**                |                 **Maneuver** |
> | ------------------------- | ---------------------------: |
> | **📏 Self and ranged 10** | **🎯 Self and three allies** |
>
> **Effect:** Each target moves up to their speed and can use the Grab maneuver, which gains an edge.

<!-- -->
> ❗️ **Courtesy Call**
>
> | **Ranged**       | **Triggered action** |
> | ---------------- | -------------------: |
> | **📏 Ranged 10** |  **🎯 One creature** |
>
> **Trigger:** The target obtains a tier 1 outcome on one power roll.
>
> **Effect:** The target has a double edge on their next power roll before the end of the encounter.

<!-- -->
> ☠️ **Close In (Villain Action 1)**
>
> | **Area**        |                        **-** |
> | --------------- | ---------------------------: |
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target moves up to their speed. Each enemy adjacent to a target after this move makes an Intuition test.
>
> - **≤11:** Frightened of the warleader (save ends)
> - **12-16:** Frightened of the warleader (EoT)
> - **17+:** No effect

<!-- -->
> ☠️ **Familial Reinforcements (Villain Action 2)**
>
> | **Ranged**       |       **-** |
> | ---------------- | ----------: |
> | **📏 Ranged 10** | **🎯 Self** |
>
> **Effect:** The warleader shifts up to their speed, and four orc blitzers appear in unoccupied spaces within distance.

<!-- -->
> ☠️ **I'll Do This Myself (Villain Action 3)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** Three times in succession, the warleader shifts up to their speed and can use Mace Lariat.

<!-- -->
> ⭐️ **End Effect**
>
> At the end of each of their turns, the warleader can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

<!-- -->
> ⭐️ **Relentless**
>
> If the warleader is reduced to 0 Stamina, they can make a free strike before dying. If the target of the free strike is reduced to 0 Stamina, the warleader is reduced to 1 Stamina instead.

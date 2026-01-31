---
agility: 2
ancestry:
  - Humanoid
  - Radenwight
ev: '12'
file_basename: Radenwight Maestro
file_dpath: Monsters/Radenwights/Statblocks
free_strike: 4
intuition: 0
item_id: radenwight-maestro
item_index: '03'
item_name: Radenwight Maestro
level: 1
might: -2
presence: 3
reason: 0
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.radenwights.statblock:radenwight-maestro
scdc:
  - 1.1.1:2.18.1:03
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: '80'
type: monster/radenwights/statblock
---

###### Radenwight Maestro

| Humanoid, Radenwight |            -            |       Level 1       |         Leader          |         EV 12          |
| :------------------: | :---------------------: | :-----------------: | :---------------------: | :--------------------: |
|   **1S**<br/> Size   |    **5**<br/> Speed     | **80**<br/> Stamina |  **1**<br/> Stability   | **4**<br/> Free Strike |
| **-**<br/> Immunity  | **Climb**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **-2**<br/> Might   |   **+2**<br/> Agility   |  **0**<br/> Reason  |  **0**<br/> Intuition   |  **+3**<br/> Presence  |

<!-- -->
> ❇️ **Cacophony (Signature Ability)**
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 3 sonic damage; slide 1, the maestro can shift 1 square
> - **12-16:** 6 sonic damage; slide 3, the maestro shifts up to 3 squares
> - **17+:** 8 sonic damage; slide 5, the maestro shifts up to 5 squares
>
> **Effect:** Each ally within distance can use Ready Rodent as a free triggered action once before the end of the round.

<!-- -->
> 🏹 **Tempo Changer**
>
> | **Magic, Ranged, Strike** |       **Maneuver** |
> | ------------------------- | -----------------: |
> | **📏 Ranged 10**          | **🎯 Two enemies** |
>
> **Power Roll + 3:**
>
> - **≤11:** P < 1 slowed (save ends)
> - **12-16:** P < 2 slowed (save ends)
> - **17+:** P < 3 slowed (save ends)
>
> **3 Malice:** Each ally within 3 squares of any target has a +2 bonus to speed until the end of their next turn.

<!-- -->
> ❗️ **Ever-Ready Rodent (2 Malice)**
>
> | **Magic, Ranged** |      **Free triggered action** |
> | ----------------- | -----------------------------: |
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to an ally or takes damage from an ally.
>
> **Effect:** The maestro makes a free strike against the target.

<!-- -->
> ⭐️ **End Effect**
>
> At the end of each of their turns, the maestro can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

<!-- -->
> ☠️ **Overture (Villain Action 1)**
>
> | **Area**        |                        **-** |
> | --------------- | ---------------------------: |
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target can shift up to their speed or take the Defend action.

<!-- -->
> ☠️ **Solo Act (Villain Action 2)**
>
> | **Ranged**       |               **-** |
> | ---------------- | ------------------: |
> | **📏 Ranged 15** | **🎯 One creature** |
>
> **Effect:** Until the end of their next turn, the target halves any damage they take, gains a +4 damage bonus to strikes, and has their speed doubled.

<!-- -->
> ☠️ **Rondo of Rat (Villain Action 3)**
>
> | **Area**        |                             **-** |
> | --------------- | --------------------------------: |
> | **📏 10 burst** | **🎯 Each dead ally in the area** |
>
> **Effect:** Each target stands, makes a free strike, then falls dead again. Any ally of the targets can use Ready Rodent as a free triggered action once in conjunction with these free strikes.

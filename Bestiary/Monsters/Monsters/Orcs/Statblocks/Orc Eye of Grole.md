---
agility: 1
ancestry:
  - Humanoid
  - Orc
ev: '6'
file_basename: Orc Eye of Grole
file_dpath: Monsters/Orcs/Statblocks
free_strike: 4
intuition: 0
item_id: orc-eye-of-grole
item_index: '07'
item_name: Orc Eye of Grole
level: 1
might: 1
presence: 2
reason: 0
roles:
  - Platoon Artillery
scc:
  - mcdm.monsters.v1:monster.orcs.statblock:orc-eye-of-grole
scdc:
  - 1.1.1:2.15.1:07
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: '20'
type: monster/orcs/statblock
---

###### Orc Eye of Grole

|               Humanoid, Orc                |          -          |       Level 1       |    Platoon Artillery    |          EV 6          |
| :----------------------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|              **1M**<br/> Size              |  **6**<br/> Speed   | **20**<br/> Stamina |  **0**<br/> Stability   | **4**<br/> Free Strike |
| **Cold, fire, or lightning**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|             **+1**<br/> Might              | **+1**<br/> Agility | **+0**<br/> Reason  |  **+0**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> ⭐️ **Elemental Affinity**
>
> The eye has an affinity for one of the following damage types cold, fire, or lightning. The chosen type determines the eye's damage immunity and the damage dealt by their abilities.

<!-- -->
> 🏹 **Elemental Discharge (Signature Ability)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage; push 2, or the eye shifts up to 2 squares away from the target
> - **12-16:** 9 damage; slide 4, or the eye shifts up to 4 squares away from the target
> - **17+:** 12 damage; slide 6, or the eye shifts up to 6 squares away from the target
>
> **Effect:** This ability deals cold, fire, or lightning damage.

<!-- -->
> 🔳 **Power Burst (3 Malice)**
>
> | **Area, Magic**            |               **Main action** |
> | -------------------------- | ----------------------------: |
> | **📏 5 x 2 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; push 2
> - **12-16:** 5 damage; push 3
> - **17+:** 8 damage; push 4, prone
>
> **Effect:** This ability deals cold, fire, or lightning damage, and any enemy targeted by the ability has damage weakness 3 to the same damage type (save ends).

<!-- -->
> ⭐️ **Relentless**
>
> If the eye is reduced to 0 Stamina, they can make a free strike before dying. If the target of the free strike is reduced to 0 Stamina, the eye is reduced to 1 Stamina instead.

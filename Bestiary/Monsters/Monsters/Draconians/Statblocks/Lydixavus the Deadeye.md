---
agility: 3
ancestry:
  - Draconian
  - Dragon
  - Humanoid
ev: '32'
file_basename: Lydixavus the Deadeye
file_dpath: Monsters/Draconians/Statblocks
free_strike: 7
intuition: 3
item_id: lydixavus-the-deadeye
item_index: '06'
item_name: Lydixavus the Deadeye
level: 6
might: -1
presence: 1
reason: 3
roles:
  - Elite Artillery
scc:
  - mcdm.monsters.v1:monster.draconians.statblock:lydixavus-the-deadeye
scdc:
  - 1.1.1:2.11.1:06
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: '140'
type: monster/draconians/statblock
---

###### Lydixavus the Deadeye

| Draconian, Dragon, Humanoid |           -           |       Level 6        |     Elite Artillery     |         EV 32          |
| :-------------------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|      **1M**<br/> Size       |   **5**<br/> Speed    | **140**<br/> Stamina |  **2**<br/> Stability   | **7**<br/> Free Strike |
|  **Cold 6**<br/> Immunity   | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|      **-1**<br/> Might      |  **+3**<br/> Agility  |  **+3**<br/> Reason  |  **+3**<br/> Intuition  |  **+1**<br/> Presence  |

<!-- -->
> 🏹 **Breathsnipe (Signature Ability)**
>
> | **Ranged, Strike, Weapon** |  **Main action** |
> | -------------------------- | ---------------: |
> | **📏 Ranged 15**           | **🎯 One enemy** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 cold damage
> - **12-16:** 16 cold damage; the target takes a bane on their next strike
> - **17+:** 19 cold damage; the target has a double bane on their next strike

<!-- -->
> 🔳 **Ice Lob**
>
> | **Area, Magic, Ranged** |                          **Main action** |
> | ----------------------- | ---------------------------------------: |
> | **📏 2 cube within 10** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 cold damage; M < 1 dazed (save ends)
> - **12-16:** 12 cold damage; M < 2 dazed (save ends)
> - **17+:** 15 cold damage; M < 3 dazed (save ends)

<!-- -->
> 👤 **Parting Gift**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Lydixavus flies up to their speed, leaving a size 1S ice mine in the space they took off from. The ice mine explodes when an enemy enters its space, using the power roll for the Ice Lob ability, and targeting the triggering creature and each creature and object adjacent to the ice mine.

<!-- -->
> ❗️ **Wasn't Aiming For You**
>
> | **-**       | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** Lydixavus obtains a tier 1 outcome on their signature ability.
>
> **Effect:** Lydixavus uses their signature ability again, targeting a creature within 5 squares of the original target.

<!-- -->
> ⭐️ **Scorekeeping Scales**
>
> Lydixavus knows the location of every creature who has ever dealt damage to them. If any of those creatures are within 20 squares of Lydixavus, Lydixavus always has line of effect to them as long as a size 1 opening exists between Lydixavus and the target.

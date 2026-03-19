---
agility: 2
ancestry:
  - Fire Giant
  - Giant
ev: '44'
file_basename: Fire Giant Red Fist
file_dpath: Monsters/Giants/Statblocks
free_strike: 10
intuition: 2
item_id: fire-giant-red-fist
item_index: '07'
item_name: Fire Giant Red Fist
level: 9
might: 4
presence: 1
reason: 0
roles:
  - Elite Brute
scc:
  - mcdm.monsters.v1:monster.giants.statblock:fire-giant-red-fist
scdc:
  - 1.1.1:2.23.1:07
size: '4'
source: mcdm.monsters.v1
speed: 8
stability: 5
stamina: '240'
type: monster/giants/statblock
---

###### Fire Giant Red Fist

|    Fire Giant, Giant     |          -          |       Level 9        |       Elite Brute       |          EV 44          |
| :----------------------: | :-----------------: | :------------------: | :---------------------: | :---------------------: |
|     **4**<br/> Size      |  **8**<br/> Speed   | **240**<br/> Stamina |  **5**<br/> Stability   | **10**<br/> Free Strike |
| **Fire 9**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |   **-**<br/> Weakness   |
|    **+4**<br/> Might     | **+2**<br/> Agility |  **0**<br/> Reason   |  **+2**<br/> Intuition  |  **+1**<br/> Presence   |

<!-- -->
> 🗡 **Flaming Punch (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 14 fire damage; push 2
> - **12-16:** 19 fire damage; push 4; A < 3 burning (save ends)
> - **17+:** 23 fire damage; push 6; A < 4 burning (save ends)
>
> **Effect:** A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.

<!-- -->
> ❇️ **Caldera (5 Malice)**
>
> | **Area**       |                          **Main action** |
> | -------------- | ---------------------------------------: |
> | **📏 Special** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** The distance is a 2 burst; 8 fire damage; M < 2 pull 2
> - **12-16:** The distance is a 3 burst; 12 fire damage; M < 3 pull 4
> - **17+:** The distance is a 4 burst; 15 fire damage; M < 4 pull 6
>
> **Effect:** The outermost squares of the area become a 1-square-tall wall of stone. The rest of the area is on fire until the end of the encounter. A creature who enters the area for the first time in a round or starts their turn there takes 3 fire damage.

<!-- -->
> 👤 **Blazing Leap**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The red fist jumps up to 5 squares. Each creature adjacent to them when they land takes 5 fire damage.

<!-- -->
> ❗️ **Heat and Pressure**
>
> | **Melee**      |      **Free triggered action** |
> | -------------- | -----------------------------: |
> | **📏 Melee 3** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance willingly moves or shifts away from the red fist.
>
> **Effect:** The target makes a **Might test**. A target with fire immunity automatically obtains a tier 3 outcome.
>
> - **≤11:** Weakened and slowed (save ends)
> - **12-16:** Weakened (EoT)
> - **17+:** No effect

<!-- -->
> ❗️ **Guardian Block**
>
> | **Melee**      | **Triggered action** |
> | -------------- | -------------------: |
> | **📏 Melee 3** |          **🎯 Self** |
>
> **Trigger:** An ally within distance is targeted by an enemy's ability.
>
> **Effect:** The red fist becomes the target of the triggering ability, then can make a free strike against the enemy after the ability resolves.

<!-- -->
> ⭐️ **Searing Skin**
>
> Whenever an adjacent enemy grabs the red fist or uses a melee ability against them, that enemy takes 5 fire damage.

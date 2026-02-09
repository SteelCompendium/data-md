---
agility: 1
ancestry:
  - Bugbear
  - Fey
  - Goblin
  - Humanoid
ev: '16'
file_basename: Bugbear Channeler
file_dpath: Monsters/Bugbears/Statblocks
free_strike: 5
intuition: 2
item_id: bugbear-channeler
item_index: '03'
item_name: Bugbear Channeler
level: 2
might: 1
presence: 2
reason: 2
roles:
  - Elite Controller
scc:
  - mcdm.monsters.v1:monster.bugbears.statblock:bugbear-channeler
scdc:
  - 1.1.1:2.36.1:03
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: '60'
type: monster/bugbears/statblock
---

###### Bugbear Channeler

| Bugbear, Fey, Goblin, Humanoid |          -          |       Level 2       |    Elite Controller     |         EV 16          |
| :----------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|        **1L**<br/> Size        |  **5**<br/> Speed   | **60**<br/> Stamina |  **0**<br/> Stability   | **5**<br/> Free Strike |
|      **-**<br/> Immunity       | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|       **+1**<br/> Might        | **+1**<br/> Agility | **+2**<br/> Reason  |  **+2**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🏹 **Shadow Drag (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main Action** |
> | ------------------------- | ------------------------------: |
> | **📏 Ranged 8**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; pull 2
> - **12-16:** 10 damage; pull 3
> - **17+:** 13 damage; pull 4
>
> **Effect:** Each target must be on the ground, and each square a target is pulled through is difficult terrain for enemies.

<!-- -->
> ❇️ **Blistering Element**
>
> | **Area, Magic** |               **Main Action** |
> | --------------- | ----------------------------: |
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Effect:** The channeler chooses one of the following damage types: acid, cold, corruption, fire, or poison.
>
> **Power Roll + 2:**
>
> - **≤11:** 2 damage; M < 0 bleeding (save ends)
> - **12-16:** 3 damage; M < 1 bleeding (save ends)
> - **17+:** 4 damage; M < 2 bleeding (save ends)

<!-- -->
> 🏹 **Twist Shape (5 Malice)**
>
> | **Magic, Ranged, Strike** |     **Main Action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 5**           | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 corruption damage; P < 0 slowed (save ends)
> - **12-16:** 8 corruption damage; P < 1 the target is shapechanged (save ends)
> - **17+:** 11 corruption damage; P < 2 the target is shapechanged (save ends)
>
> **Effect:** A shapechanged creature is slowed and has fire weakness 10 as their limbs stretch and their skin becomes paper thin.

<!-- -->
> 🗡 **Throw**
>
> | **Melee, Strike** |                  **Maneuver** |
> | ----------------- | ----------------------------: |
> | **📏 Melee 1**    | **🎯 One creature or object** |
>
> **Special:** The target must be grabbed by the channeler.
>
> **Effect:** The target is vertical pushed up to 3 squares. An ally doesn't take damage from being force moved this way.

<!-- -->
> ❗️ **Catcher**
>
> | **Melee**      |                **Free triggered action** |
> | -------------- | ---------------------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A size 1 creature or object is force moved within distance, or a size 1 ally willingly moves within distance.
>
> **Effect:** The target is grabbed by the channeler.

<!-- -->
> ❗️ **Shadow Veil**
>
> | **Magic, Ranged** |       **Triggered action** |
> | ----------------- | -------------------------: |
> | **📏 Ranged 5**   | **🎯 The triggering ally** |
>
> **Trigger:** An ally within distance takes damage.
>
> **Effect:** The target is wrapped in shadow and halves the damage. The target can't be targeted by strikes until the start of their next turn.

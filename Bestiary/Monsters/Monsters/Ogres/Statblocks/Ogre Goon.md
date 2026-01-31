---
agility: 0
ancestry:
  - Giant
  - Ogre
ev: '16'
file_basename: Ogre Goon
file_dpath: Monsters/Ogres/Statblocks
free_strike: 5
intuition: 0
item_id: ogre-goon
item_index: '01'
item_name: Ogre Goon
level: 2
might: 2
presence: -1
reason: -1
roles:
  - Elite Brute
scc:
  - mcdm.monsters.v1:monster.ogres.statblock:ogre-goon
scdc:
  - 1.1.1:2.4.1:01
size: '2'
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: '100'
type: monster/ogres/statblock
---

###### Ogre Goon

|     Giant, Ogre     |          -          |       Level 2        |       Elite Brute       |         EV 16          |
| :-----------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|   **2**<br/> Size   |  **5**<br/> Speed   | **100**<br/> Stamina |  **4**<br/> Stability   | **5**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  | **0**<br/> Agility  |  **-1**<br/> Reason  |  **0**<br/> Intuition   |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Club Swing (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; push 2
> - **12-16:** 11 damage; push 4
> - **17+:** 14 damage; push 6, prone
>
> **Effect:** Any target who takes damage from this forced movement takes an extra 4 damage.

<!-- -->
> 🗡 **Grabby Hand (1 Malice)**
>
> | **Melee, Strike, Weapon** |                  **Maneuver** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage; grabbed
> - **17+:** 14 damage; grabbed
>
> **Effect:** A target grabbed this way takes a bane on the Escape Grab maneuver.

<!-- -->
> 🔳 **People Bowling (3 Malice)**
>
> | **Area, Weapon**           |                                **Maneuver** |
> | -------------------------- | ------------------------------------------: |
> | **📏 6 x 1 line within 1** | **🎯 Each creature and object in the area** |
>
> **Effect:** The goon must have a size 1 creature or object grabbed, which they hurl across the area, ending the grab. The hurled creature or object is targeted by the ability, and lands in the last square of the line or the nearest unoccupied square of the goon's choice.
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage; prone

<!-- -->
> ❗️ **Swat the Fly**
>
> | **Melee**      |                     **Triggered action** |
> | -------------- | ---------------------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance moves or shifts away from the goon.
>
> **Effect:** The goon slides the target up to 5 squares.

<!-- -->
> ⭐️ **Defiant Anger**
>
> While winded, the goon has damage immunity 2.

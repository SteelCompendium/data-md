---
agility: 2
ancestry:
  - Humanoid
  - Lizardfolk
ev: '12'
file_basename: Lizardfolk Deathrex
file_dpath: Monsters/Lizardfolks/Statblocks
free_strike: 4
intuition: 1
item_id: lizardfolk-deathrex
item_index: '01'
item_name: Lizardfolk Deathrex
level: 1
might: 3
presence: 2
reason: 0
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.lizardfolks.statblock:lizardfolk-deathrex
scdc:
  - 1.1.1:2.7.1:01
size: '2'
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: '80'
type: monster/lizardfolks/statblock
---

###### Lizardfolk Deathrex

| Humanoid, Lizardfolk |               -               |       Level 1       |         Leader          |         EV 12          |
| :------------------: | :---------------------------: | :-----------------: | :---------------------: | :--------------------: |
|   **2**<br/> Size    |       **5**<br/> Speed        | **80**<br/> Stamina |  **2**<br/> Stability   | **4**<br/> Free Strike |
| **-**<br/> Immunity  | **Climb, swim**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+3**<br/> Might   |      **+2**<br/> Agility      |  **0**<br/> Reason  |  **+1**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🗡 **Ripper Spear (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 damage; pull 1; A < 1 bleeding (save ends)
> - **12-16:** 10 damage; pull 1; A < 2 bleeding (save ends)
> - **17+:** 12 damage; pull 2; A < 3 bleeding (save ends)
>
> **1 Malice:** One target adjacent to the deathrex is grabbed in the deathrex's mouth.

<!-- -->
> 🗡 **Death Roll (3 Malice)**
>
> | **Melee, Strike, Weapon** |                       **Main action** |
> | ------------------------- | ------------------------------------: |
> | **📏 Melee 1**            | **🎯 One grabbed creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; M < 1 dazed (save ends)
> - **12-16:** 12 damage; M < 2 dazed (save ends)
> - **17+:** 15 damage; M < 3 dazed (save ends)
>
> **Effect:** The target is no longer grabbed by the deathrex, and the deathrex slides them up to 5 squares.

<!-- -->
> 👤 **Trundle**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The deathrex moves up to their speed. They can make a free strike against each creature who makes an opportunity attack against them during this movement.

<!-- -->
> ❗️ **Swat the Fly**
>
> | **Melee**      |                     **Triggered action** |
> | -------------- | ---------------------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance moves or shifts away from the deathrex.
>
> **Effect:** The deathrex slides the target up to 5 squares.

<!-- -->
> ⭐️ **Rex Reptilian Escape**
>
> While the deathrex has a tail, whenever they are affected by an effect that can be ended by a saving throw or that ends at the end of their turn, they can lose their tail to immediately end that effect, then shift up to 2 squares.

<!-- -->
> ☠️ **Snack Attack (Villain Action 1)**
>
> | **Area**        |                                 **-** |
> | --------------- | ------------------------------------: |
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target moves up to their speed and can make a free strike. Each target gains temporary Stamina equal to the damage they deal.

<!-- -->
> ☠️ **Shed Some Skin (Villain Action 2)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The deathrex shifts up to their speed, leaving behind a shed skin duplicate in the space they started in. The duplicate acts on the deathrex's turn and has the deathrex's characteristics, but has 10 Stamina and no villain actions.

<!-- -->
> ☠️ **Thresher Thrasher (Villain Action 3)**
>
> | **Area**        |                                 **-** |
> | --------------- | ------------------------------------: |
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target moves up to their speed. Until the end of the encounter, whenever a creature comes adjacent to a target or starts their turn there, the target can make a free strike against them.

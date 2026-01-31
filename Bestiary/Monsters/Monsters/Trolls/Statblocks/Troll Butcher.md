---
agility: 1
ancestry:
  - Giant
  - Troll
ev: '28'
file_basename: Troll Butcher
file_dpath: Monsters/Trolls/Statblocks
free_strike: 6
intuition: 0
item_id: troll-butcher
item_index: '01'
item_name: Troll Butcher
level: 5
might: 3
presence: 0
reason: 1
roles:
  - Elite Hexer
scc:
  - mcdm.monsters.v1:monster.trolls.statblock:troll-butcher
scdc:
  - 1.1.1:2.51.1:01
size: '2'
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: '120'
type: monster/trolls/statblock
---

###### Troll Butcher

|    Giant, Troll     |          -          |       Level 5        |       Elite Hexer       |             EV 28              |
| :-----------------: | :-----------------: | :------------------: | :---------------------: | :----------------------------: |
|   **2**<br/> Size   |  **8**<br/> Speed   | **120**<br/> Stamina |  **2**<br/> Stability   |     **6**<br/> Free Strike     |
| **-**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain | **Acid 5, fire**<br/> Weakness |
|  **+3**<br/> Might  | **+1**<br/> Agility |  **+1**<br/> Reason  |  **0**<br/> Intuition   |      **0**<br/> Presence       |

<!-- -->
> 🗡 **Savoring Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; M < 1 bleeding (save ends)
> - **12-16:** 14 damage; M < 2 bleeding (save ends)
> - **17+:** 17 damage; M < 3 bleeding (save ends)
>
> **1 Malice:** The butcher regains Stamina equal to the damage dealt.

<!-- -->
> 🔳 **Rotten Scraps**
>
> | **Area, Ranged**        |                  **Main action** |
> | ----------------------- | -------------------------------: |
> | **📏 3 cube within 10** | **🎯 Each creature in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 poison damage; M < 1 weakened (save ends)
> - **12-16:** 9 poison damage; M < 2 weakened (save ends)
> - **17+:** 11 poison damage; M < 3 weakened (save ends)
>
> **Effect:** Each troll in the area ignores the damage and instead regains 3 Stamina.

<!-- -->
> 👤 **Gourmet Flesh (2 Malice)**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The butcher enhances their next use of Savoring Bite, changing the damage type and condition imposed to one of the following pairs: corruption damage and dazed, acid damage and restrained, or lightning damage and frightened.

<!-- -->
> ❗️ **Acquired Taste**
>
> | **Melee**      |           **Triggered action** |
> | -------------- | -----------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the butcher with an ability that gains an edge, has a double edge, or uses a surge.
>
> **Effect:** The butcher makes a free strike against the target. Until the end of their next turn, the butcher gains an edge on power rolls and deals an extra 3 damage with strikes.

<!-- -->
> ⭐️ **Bloody Feast**
>
> Each ally within 5 squares of the butcher gains an edge on power rolls against any enemy affected by a condition.

<!-- -->
> ⭐️ **Relentless Hunger**
>
> The butcher dies only if they are reduced to 0 Stamina by acid or fire damage, if they end their turn with 0 Stamina, or if they take acid or fire damage while at 0 Stamina.

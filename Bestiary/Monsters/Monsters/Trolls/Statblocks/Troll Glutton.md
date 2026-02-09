---
agility: 1
ancestry:
  - Giant
  - Troll
ev: '28'
file_basename: Troll Glutton
file_dpath: Monsters/Trolls/Statblocks
free_strike: 7
intuition: 0
item_id: troll-glutton
item_index: '03'
item_name: Troll Glutton
level: 5
might: 3
presence: 1
reason: -1
roles:
  - Elite Brute
scc:
  - mcdm.monsters.v1:monster.trolls.statblock:troll-glutton
scdc:
  - 1.1.1:2.52.1:03
size: '2'
source: mcdm.monsters.v1
speed: 6
stability: 4
stamina: '160'
type: monster/trolls/statblock
---

###### Troll Glutton

|    Giant, Troll     |          -          |       Level 5        |       Elite Brute       |             EV 28              |
| :-----------------: | :-----------------: | :------------------: | :---------------------: | :----------------------------: |
|   **2**<br/> Size   |  **6**<br/> Speed   | **160**<br/> Stamina |  **4**<br/> Stability   |     **7**<br/> Free Strike     |
| **-**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain | **Acid 5, fire**<br/> Weakness |
|  **+3**<br/> Might  | **+1**<br/> Agility |  **-1**<br/> Reason  |  **0**<br/> Intuition   |      **+1**<br/> Presence      |

<!-- -->
> 🗡 **Voracious Mastication (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage
> - **12-16:** 15 damage; M < 2 slowed (save ends)
> - **17+:** 18 damage; M < 3 slowed (save ends)
>
> **1 Malice:** The glutton regains Stamina equal to the damage dealt.

<!-- -->
> 👤 **Crash Through (3 Malice)**
>
> | **-**       | **Main action** |
> | ----------- | --------------: |
> | **📏 Self** |     **🎯 Self** |
>
> **Effect:** The glutton shifts up to their speed in a straight line, ignoring difficult terrain. The first time during this movement that the glutton moves through the space of a creature or object their size or smaller, that creature or object takes 10 damage, or a creature can choose to fall prone instead. If the glutton moves into a creature or object larger than them and doesn't knock the creature prone or destroy the object, the glutton's movement ends and they are dazed until the end of their next turn.

<!-- -->
> 👤 **Food Frenzy**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Until the start of their next turn, the glutton has a double edge on strikes, and strikes made against them gain an edge.

<!-- -->
> ❗️ **Spiteful Retort (1 Malice)**
>
> | **Melee**      |      **Free triggered action** |
> | -------------- | -----------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** The glutton is reduced to 0 Stamina but doesn't die.
>
> **Effect:** The glutton uses Voracious Mastication against an adjacent creature.

<!-- -->
> ⭐️ **Insatiable Appetite**
>
> Once per turn, the glutton can use the Charge main actionas a free maneuver if they target a winded creature.

<!-- -->
> ⭐️ **Relentless Hunger**
>
> The glutton dies only if they are reduced to 0 Stamina by acid or fire damage, if they end their turn with 0 Stamina, or if they take acid or fire damage while at 0 Stamina.

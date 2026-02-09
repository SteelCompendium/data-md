---
agility: 1
ancestry:
  - Beast
  - Lightbender
ev: '20'
file_basename: Lightbender
file_dpath: Monsters/Lightbenders/Statblocks
free_strike: 6
intuition: 1
item_id: lightbender
item_index: '01'
item_name: Lightbender
level: 3
might: 2
presence: -1
reason: -3
roles:
  - Elite Ambusher
scc:
  - mcdm.monsters.v1:monster.lightbenders.statblock:lightbender
scdc:
  - 1.1.1:2.24.1:01
size: '2'
source: mcdm.monsters.v1
speed: 10
stability: 1
stamina: '100'
type: monster/lightbenders/statblock
---

###### Lightbender

| Beast, Lightbender  |          -          |       Level 3        |     Elite Ambusher      |         EV 20          |
| :-----------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|   **2**<br/> Size   |  **10**<br/> Speed  | **100**<br/> Stamina |  **1**<br/> Stability   | **6**<br/> Free Strike |
| **-**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  | **+1**<br/> Agility |  **-3**<br/> Reason  |  **+1**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Flash Swipe (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 9 damage
> - **12-16:** 14 damage
> - **17+:** 18 damage
>
> **Effect:** If this ability gains an edge or has a double edge, it deals an extra 4 damage.

<!-- -->
> 🗡 **Piercing Tails**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage
> - **12-16:** 12 damage; M < 1 bleeding (save ends)
> - **17+:** 15 damage; M < 2 bleeding (save ends)
>
> **Effect:** While bleeding this way, the target takes a bane on tests to search for the lightbender while they are hidden.

<!-- -->
> ❇️ **Hypnotic Mane (5 Malice)**
>
> | **Area, Magic** |                  **Maneuver** |
> | --------------- | ----------------------------: |
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** I < 0 dazed (save ends)
> - **12-16:** I < 1 dazed (save ends)
> - **17+:** I < 2 dazed (save ends)
>
> **Effect:** While dazed this way, a target has speed 0. If a target takes damage, or if someone else uses a main action to shake the target out of their stupor, the dazed condition ends.

<!-- -->
> ❗️ **Stalker's Afterimage**
>
> | **Magic**   | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The lightbender takes damage from a strike.
>
> **Effect:** The lightbender halves the damage, ignores any nondamaging effects associated with it, and can teleport up to 5 squares. If they teleport into concealment or cover, the lightbender can immediately attempt to hide as a free maneuver.

<!-- -->
> ⭐️ **Avoidance**
>
> Any effect on the lightbender that would be ended by a saving throw instead ends automatically at the end of their next turn.

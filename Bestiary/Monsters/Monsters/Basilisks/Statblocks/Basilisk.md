---
agility: 0
ancestry:
  - Basilisk
  - Beast
ev: '12'
file_basename: Basilisk
file_dpath: Monsters/Basilisks/Statblocks
free_strike: 5
intuition: -1
item_id: basilisk
item_index: '01'
item_name: Basilisk
level: 1
might: 2
presence: -1
reason: -3
roles:
  - Elite Brute
scc:
  - mcdm.monsters.v1:monster.basilisks.statblock:basilisk
scdc:
  - 1.1.1:2.42.1:01
size: '2'
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: '80'
type: monster/basilisks/statblock
---

###### Basilisk

|      Basilisk, Beast       |          -          |       Level 1       |       Elite Brute       |         EV 12          |
| :------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|      **2**<br/> Size       |  **8**<br/> Speed   | **80**<br/> Stamina |  **2**<br/> Stability   | **5**<br/> Free Strike |
| **Poison 4**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|     **+2**<br/> Might      | **+0**<br/> Agility | **-3**<br/> Reason  |  **-1**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Noxious Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main Action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 poison damage
> - **12-16:** 10 poison damage
> - **17+:** 13 poison damage
>
> **Effect:** This ability gains an edge against targets the basilisk has previously dealt poison damage to.

<!-- -->
> 🔳 **Petrifying Eye Beams**
>
> | **Area, Magic**            |   **Maneuver** |
> | -------------------------- | -------------: |
> | **📏 5 x 2 line within 1** | **🎯 Special** |
>
> **Special:** The area extends from both the basilisk's eyes, and this ability targets the first creature without cover on either side of the area.
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 restrained (save ends)
> - **12-16:** M < 1 restrained (save ends)
> - **17+:** Slowed (save ends); or if M < 2 restrained (save ends)
>
> **Effect:** If a target is already slowed, the potency increases by 1 for that target. A target restrained this way magically begins to turn to stone, and a target who ends two consecutive turns restrained this way is petrified. A target restrained this way or a creature adjacent to them can use a main action to cut encroaching stone from the target's body, dealing 8 damage to the target that can't be reduced in any way and ending this effect.

<!-- -->
> 🔳 **Poison Fumes (5 Malice)**
>
> | **Area, Magic**        |               **Main action** |
> | ---------------------- | ----------------------------: |
> | **📏 3 cube within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 poison damage; M < 0 weakened (save ends)
> - **12-16:** 6 poison damage; M < 1 weakened and slowed (save ends)
> - **17+:** 9 poison damage; M < 2 weakened and slowed (save ends)

<!-- -->
> ❗️ **Lash Out**
>
> | **Area**       |          **Triggered action** |
> | -------------- | ----------------------------: |
> | **📏 1 burst** | **🎯 Each enemy in the area** |
>
> **Trigger:** The basilisk takes damage from a melee ability.
>
> **Effect:** Each target takes 5 damage. Any target who has A < 2 is also bleeding (save ends).

<!-- -->
> ⭐️ **Calcifying Presence**
>
> The area within 3 squares of the basilisk is difficult terrain for enemies.

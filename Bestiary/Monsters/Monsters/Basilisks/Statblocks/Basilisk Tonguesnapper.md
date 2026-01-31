---
agility: 2
ancestry:
  - Basilisk
  - Beast
ev: '12'
file_basename: Basilisk Tonguesnapper
file_dpath: Monsters/Basilisks/Statblocks
free_strike: 4
intuition: -1
item_id: basilisk-tonguesnapper
item_index: '02'
item_name: Basilisk Tonguesnapper
level: 1
might: 1
presence: -1
reason: -3
roles:
  - Elite Hexer
scc:
  - mcdm.monsters.v1:monster.basilisks.statblock:basilisk-tonguesnapper
scdc:
  - 1.1.1:2.42.1:02
size: '2'
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: '40'
type: monster/basilisks/statblock
---

###### Basilisk Tonguesnapper

|          Basilisk, Beast           |          -          |       Level 1       |       Elite Hexer       |         EV 12          |
| :--------------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|          **2**<br/> Size           |  **8**<br/> Speed   | **40**<br/> Stamina |  **2**<br/> Stability   | **4**<br/> Free Strike |
| **Acid 2, Poison 2**<br/> Immunity | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|         **+1**<br/> Might          | **+2**<br/> Agility | **-3**<br/> Reason  |  **-1**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Prehensile Tongue (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 acid damage; pull 1
> - **12-16:** 10 acid damage; pull 2
> - **17+:** 14 acid damage; pull 3
>
> **Effect:** This ability can pull targets restrained by Petrifying Eye Beams, and ignores stability if it does so.
>
> **3 Malice:** The tonguesnapper targets two additional creatures or objects.

<!-- -->
> 🔳 **Petrifying Eye Beams**
>
> | **Area, Magic**            |   **Maneuver** |
> | -------------------------- | -------------: |
> | **📏 5 x 2 line within 1** | **🎯 Special** |
>
> **Special:** The area extends from both the tonguesnapper's eyes, and this ability targets the first creature without cover on either side of the area.
>
> **Power Roll + 2:**
>
> - **≤11:** A < 0 restrained (save ends)
> - **12-16:** A < 1 restrained (save ends)
> - **17+:** Slowed (save ends); or if A < 2 restrained (save ends)
>
> **Effect:** If a target is already slowed, the potency increases by 1 for that target. A target restrained this way magically begins to turn to stone, and a target who ends two consecutive turns restrained this way is petrified. A target restrained this way or a creature adjacent to them can use a main action to cut encroaching stone from the target's body, dealing 8 damage to the target that can't be reduced in any way and ending this effect.

<!-- -->
> ⚔️ **Wink (2 Malice)**
>
> | **Magic, Melee, Ranged, Strike** |     **Main action** |
> | -------------------------------- | ------------------: |
> | **📏 Melee 1 or ranged 10**      | **🎯 One creature** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 corruption damage; R < 0 dazed (save ends)
> - **12-16:** 10 corruption damage; R < 1 dazed (save ends)
> - **17+:** 14 corruption damage; R < 2 dazed and slowed (save ends)
>
> **Effect:** A creature dazed this way can't benefit from edges or double edges and can't gain or use surges.

<!-- -->
> ❗️ **Neurotoxin Splash**
>
> | **Area**       |          **Triggered action** |
> | -------------- | ----------------------------: |
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Trigger:** The tonguesnapper takes damage from a melee ability.
>
> **Effect:** Each target takes 4 acid damage. Any target who has M < 2 is also slowed (save ends).

<!-- -->
> ⭐️ **Petrifying Fumes**
>
> Any creature who starts their turn adjacent to the tonguesnapper and has M < 1 is slowed (save ends).

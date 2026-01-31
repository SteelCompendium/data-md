---
agility: 4
ancestry:
  - Dragon
  - Elemental
ev: '72'
file_basename: Gloom Dragon
file_dpath: Monsters/Dragons/Statblocks
free_strike: 6
intuition: 3
item_id: gloom-dragon
item_index: '02'
item_name: Gloom Dragon
level: 4
might: 2
presence: 4
reason: 1
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.dragons.statblock:gloom-dragon
scdc:
  - 1.1.1:2.45.1:02
size: '4'
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: '350'
type: monster/dragons/statblock
---

###### Gloom Dragon

|      Dragon, Elemental      |              -               |       Level 4        |          Solo           |         EV 72          |
| :-------------------------: | :--------------------------: | :------------------: | :---------------------: | :--------------------: |
|       **4**<br/> Size       |       **8**<br/> Speed       | **350**<br/> Stamina |  **2**<br/> Stability   | **6**<br/> Free Strike |
| **Psychic 5**<br/> Immunity | **Fly, hover**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|      **+2**<br/> Might      |     **+4**<br/> Agility      |  **+1**<br/> Reason  |  **+3**<br/> Intuition  |  **+4**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

<!-- -->
> ❇️ **Gloaming Wyrmscale Aura**
>
> The dragon's scales create a 3 aura of dark supernatural fog around them that feeds on their victims' fears and provides concealment to the dragon only. Each enemy who starts their turn in the area takes 2 psychic damage. Additionally, whenever one or more enemies is in the area, the dragon's abilities deal an extra 3 psychic damage.

<!-- -->
> 🔳 **Breath of Brume (Signature Ability)**
>
> | **Area, Magic, Ranged** |                          **Main action** |
> | ----------------------- | ---------------------------------------: |
> | **📏 4 cube within 10** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes an **Agility test**.
>
> - **≤11:** 14 cold damage; the target is dragonsealed (save ends)
> - **12-16:** 11 cold damage; the target is dragonsealed (save ends)
> - **17+:** 6 cold damage
>
> A dragonsealed creature has psychic weakness 3 and cold weakness 3. Additionally, the area is filled with magical darkness. The dragon ignores concealment created by this darkness.

<!-- -->
> 🗡 **Phantom Tail Swing**
>
> | **Charge, Magic, Melee, Strike** |                 **Main action** |
> | -------------------------------- | ------------------------------: |
> | **📏 Melee 3**                   | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 10 psychic damage; pull 2
> - **12-16:** 15 psychic damage; pull 4
> - **17+:** 18 psychic damage; pull 6
>
> **3 Malice:** The pull becomes a vertical slide.

<!-- -->
> ⭐️ **Shadow Skulk**
>
> Once per turn, the dragon can shift up to their speed, leaving behind a 4 cube area of magical darkness in their starting space that lasts until the end of the encounter. The dragon ignores concealment created by this darkness. Any enemy who ends their turn in the area and has I < 3 is frightened of the dragon until the end of their next turn.

<!-- -->
> ❇️ **Visions in the Dark (5 Malice)**
>
> | **Area, Magic** |                  **Maneuver** |
> | --------------- | ----------------------------: |
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. Each target takes 3 psychic damage, and if they have I < 3 they immediately make a free strike against one ally of the dragon's choice.

<!-- -->
> ❗️ **Encroaching Darkness (1 Malice)**
>
> | **-**       | **Free triggered action** |
> | ----------- | ------------------------: |
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** A creature within 10 squares moves.
>
> **Effect:** The dragon moves two existing cubes of magical darkness they created up to 10 squares each.

<!-- -->
> ☠️ **Enveloping Umbrage (Villain Action 1)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** Pull 2; I < 2 frightened (EoT)
> - **12-16:** Pull 4; I < 3 frightened (save ends)
> - **17+:** Pull 6; I < 4 frightened (save ends)

<!-- -->
> ☠️ **Pall of Nightmares (Villain Action 2)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 psychic damage
> - **12-16:** 11 psychic damage
> - **17+:** 14 psychic damage
>
> **Effect:** Each target must be dragonsealed. Any target who has I < 3 is also dazed (save ends).

<!-- -->
> ☠️ **Absence of All Light (Villain Action 3)**
>
> | **-**          |          **-** |
> | -------------- | -------------: |
> | **📏 Special** | **🎯 Special** |
>
> **Effect:** The dragon disappears from the encounter map. The dragon and three hallucinatory illusions of themself then immediately reappear in unoccupied spaces on the encounter map, and the dragon and each illusion uses Breath of Brume. Each illusion is indistinguishable from the dragon except by supernatural means, has 1 Stamina, and has the dragon's speed. An illusion acts on the dragon's turns but can take only move actions. Once per round before or after using an ability, the dragon can trade places with any duplicate.

###### Gloom Dragon Malice (Malice Features)

At the start of a gloom dragon's turn, you can spend Malice to activate one of the following features.

<!-- -->
> ⭐️ **Dread and Terror (3 Malice)**
>
> The dragon thickens the fog of their Gloaming Wyrmscale Aura trait and the horrors within it. Each creature in the area takes a bane on strikes made against the dragon until the start of the dragon's next turn.

<!-- -->
> 🔳 **Doleful Visions (5 Malice)**
>
> The dragon manifests four 2 cubes of nightmarish apparitions anywhere on the encounter map. Each creature in the area when it appears makes an **Intuition test**.
>
> - **≤11:** 14 damage; dazed (save ends)
> - **12-16:** 11 damage; dazed (EoT)
> - **17+:** 6 damage

<!-- -->
> ☠️ **Solo Action (5 Malice)**
>
> The dragon takes an additional main action on their turn. They can use this feature even if they are dazed.

<!-- -->
> 🔳 **Phantasmagoria! (7 Malice)**
>
> The dragon summons macabre, disquieting phantasms in a 10 cube within 1 square that lasts until the end of the encounter. Any enemy who enters the area for the first time in a round or starts their turn there takes 6 psychic damage, or 8 psychic damage if they are dragonsealed by the gloom dragon. Additionally, the enemy's Intuition score is treated as 1 lower for the purpose of resisting potencies until the end of the encounter.

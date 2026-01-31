---
agility: 3
ancestry:
  - Undead
ev: '144'
file_basename: Lich
file_dpath: Monsters/Lich/Statblocks
free_strike: 10
intuition: 5
item_id: lich
item_index: '01'
item_name: Lich
level: 10
might: 2
presence: 5
reason: 5
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.lich.statblock:lich
scdc:
  - 1.1.1:2.47.1:01
size: 1M
source: mcdm.monsters.v1
speed: 10
stability: 1
stamina: '650'
type: monster/lich/statblock
---

###### Lich

|                   Undead                   |              -               |       Level 10       |          Solo           |          EV 144          |
| :----------------------------------------: | :--------------------------: | :------------------: | :---------------------: | :----------------------: |
|              **1M**<br/> Size              |      **10**<br/> Speed       | **650**<br/> Stamina |  **1**<br/> Stability   | **10**<br/> Free Strike  |
| **Corruption 10, poison 10**<br/> Immunity | **Fly, hover**<br/> Movement |          -           | **-**<br/> With Captain | **Holy 5**<br/> Weakness |
|             **+2**<br/> Might              |     **+3**<br/> Agility      |  **+5**<br/> Reason  |  **+5**<br/> Intuition  |   **+5**<br/> Presence   |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the lich can take 20 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The lich can take two turns each round. They can't take turns consecutively.

<!-- -->
> 🏹 **Conflagration (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Ranged 20**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 fire damage; A < 4 the target is immolated (save ends)
> - **12-16:** 21 fire damage; A < 5 the target is immolated (save ends)
> - **17+:** 25 fire damage; A < 6 the target is immolated (save ends)
>
> **Effect:** An immolated creature takes 10 fire damage whenever they use a main action and a maneuver on their turn. This damage can't be reduced in any way.

<!-- -->
> ❇️ **Hopeless Place**
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 corruption damage; P < 4 the target is hopeless (save ends)
> - **12-16:** 13 corruption damage; P < 5 the target is hopeless (save ends)
> - **17+:** 16 corruption damage; P < 6 the target is hopeless (save ends)
>
> **Effect:** A hopeless creature can't benefit from edges or double edges, can't gain or use surges, and can't gain temporary Stamina.
>
> **3 Malice:** The distance of this ability increases to a 20 burst and its potency increases by 1.

<!-- -->
> 🏹 **Pain Unending (2 Malice)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 20**          | **🎯 One creature or object** |
>
> **Power Roll + 5:**
>
> - **≤11:** 17 psychic damage
> - **12-16:** 24 psychic damage
> - **17+:** 29 psychic damage
>
> **Effect:** A target who has M < 4 is wracked with pain (save ends). A creature wracked with pain has a double bane on abilities.
>
> **3 Malice:** The lich chooses one additional target.
>
> **2+ Malice:** Each creature wracked with pain gains one of the following conditions of the lich's choice for each 2 Malice spent: bleeding, slowed, or prone and can't stand. These conditions end when a creature is no longer wracked with pain.

<!-- -->
> 👤 **Necrotic Form**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The lich becomes spectral, moves up to their speed, and becomes corporeal again. While spectral, the lich automatically ends the grabbed or restrained conditions, has damage immunity 5, can move through solid matter, and ignores difficult terrain. If the lich ends this movement inside solid matter, they are shunted out into the space from which they entered it.

<!-- -->
> ❗️ **Baleful Swap (2 Malice)**
>
> | **Ranged**       | **Triggered action** |
> | ---------------- | -------------------: |
> | **📏 Ranged 10** |     **🎯 One enemy** |
>
> **Trigger:** The lich is targeted using an ability by a creature other than the target.
>
> **Effect:** If the target has P < 4, they swap places with the lich to become the new target of the triggering ability.

<!-- -->
> ⭐️ **Herald of Oblivion**
>
> In the lich's presence, death's call is stronger. Any winded creature within 5 squares of the lich is bleeding and can't use the Catch Breath maneuver.

<!-- -->
> ⭐️ **Glare of Undeath**
>
> At the start of each round, the lich chooses a creature within 10 squares. If that creature has R < 4, they are restrained until the end of the lich's next turn. The lich can't choose the same creature two rounds in a row.

<!-- -->
> ⭐️ **Rejuvenation**
>
> The lich has a soulstone, which has 50 Stamina and damage immunity all except to sonic damage and holy damage. If the lich is destroyed while their soulstone is intact, their soul retreats into the soulstone. Any creature who has P < 5 and who moves within 5 squares of an inhabited soulstone for the first time in a round or starts their turn there is compelled (save ends). A compelled creature must do everything in their power to move toward and touch the soulstone.
>
> A creature who touches an inhabited soulstone makes a **Might test** that takes a bane.
>
> - **≤11:** The creature is reduced to 0 Stamina and the lich manifests adjacent to the soulstone with full Stamina.
> - **12-16:** The creature is reduced to 0 Stamina and the lich manifests adjacent to the soulstone with 300 Stamina.
> - **17+:** The creature has their Stamina reduced to their winded value unless it is already lower, and the lich manifests adjacent to the soulstone with 100 Stamina.

<!-- -->
> ☠️ **Cages of Wasting (Villain Action 1)**
>
> | **Area, Magic, Ranged**      |                            **-** |
> | ---------------------------- | -------------------------------: |
> | **📏 Two 3 cubes within 10** | **🎯 Each creature in the area** |
>
> **Effect:** Each target makes an Agility test.
>
> - **≤11:** 10 corruption damage; restrained (save ends)
> - **12-16:** 16 corruption damage; restrained (EoT)
> - **17+:** 20 corruption damage
>
> **Effect:** The lich deals an additional 10 corruption damage to each creature restrained this way.

<!-- -->
> ☠️ **My Power Alone (Villain Action 2)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 12 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** A target can't use heroic abilities until the start of the lich's next turn.

<!-- -->
> ☠️ **Arms of Necrosis (Villain Action 3)**
>
> | **Area, Magic** |                            **-** |
> | --------------- | -------------------------------: |
> | **📏 6 burst**  | **🎯 Each creature in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 corruption damage; A < 4 frightened (save ends)
> - **12-16:** 13 corruption damage; A < 5 frightened (save ends)
> - **17+:** 16 corruption damage; A < 6 frightened (save ends)
>
> **Effect:** At the end of each of the lich's turns, they regain 10 Stamina for each creature frightened this way.

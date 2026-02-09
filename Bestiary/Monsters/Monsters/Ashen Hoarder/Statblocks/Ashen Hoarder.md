---
agility: -1
ancestry:
  - Construct
  - Undead
ev: '72'
file_basename: Ashen Hoarder
file_dpath: Monsters/Ashen Hoarder/Statblocks
free_strike: 6
intuition: 0
item_id: ashen-hoarder
item_index: '01'
item_name: Ashen Hoarder
level: 4
might: 4
presence: -5
reason: -2
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.ashen-hoarder.statblock:ashen-hoarder
scdc:
  - 1.1.1:2.25.1:01
size: '3'
source: mcdm.monsters.v1
speed: 8
stability: 3
stamina: '350'
type: monster/ashen-hoarder/statblock
---

###### Ashen Hoarder

|  Construct, Undead  |            -             |       Level 4        |          Solo           |          EV 72           |
| :-----------------: | :----------------------: | :------------------: | :---------------------: | :----------------------: |
|   **3**<br/> Size   |     **8**<br/> Speed     | **350**<br/> Stamina |  **3**<br/> Stability   |  **6**<br/> Free Strike  |
| **-**<br/> Immunity | **Burrow**<br/> Movement |          -           | **-**<br/> With Captain | **Holy 5**<br/> Weakness |
|  **+4**<br/> Might  |   **-1**<br/> Agility    |  **-2**<br/> Reason  |  **+0**<br/> Intuition  |   **-5**<br/> Presence   |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the ashen hoarder can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The ashen hoarder can take two turns each round. They can't take turns consecutively.

<!-- -->
> 🗡 **Claw and Blade (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 10 damage; if one target has M < 2 they are bleeding (save ends); if the other target has A < 2 they are grabbed
> - **12-16:** 15 damage; if one target has M < 3 they are bleeding (save ends); if the other target has A < 3 they are grabbed
> - **17+:** 18 damage; M < 4 bleeding (save ends); A < 2 grabbed
>
> **Effect:** The ashen hoarder can have up to two size 1 creatures grabbed at a time. | |

<!-- -->
> 🔳 **Corpse Bomb**
>
> | **Area, Magic, Ranged** |               **Main Action** |
> | ----------------------- | ----------------------------: |
> | **📏 4 cube within 20** | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 4 damage; A < 2 weakened (save ends)
> - **12-16:** 8 damage; A < 3 weakened (save ends)
> - **17+:** 11 damage; A < 4 weakened (save ends)
>
> **2 Malice:** Any enemy weakened this way is instead slowed and weakened (save ends).
>
> **3 Malice:** The ashen hoarder targets a second 4 cube within distance.

<!-- -->
> 🔳 **Impale (3 Malice)**
>
> | **Area, Weapon**           |                  **Main action** |
> | -------------------------- | -------------------------------: |
> | **📏 4 x 1 line within 1** | **🎯 Each creature in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 corruption damage; M < 2 the target is impaled (save ends)
> - **12-16:** 11 corruption damage; M < 3 the target is impaled (save ends)
> - **17+:** 14 corruption damage; M < 4 the target is impaled (save ends)
>
> **Effect:** An impaled creature is restrained and bleeding, and moves with the ashen hoarder. The ashen hoarder can have three creatures impaled with this ability at a time.

<!-- -->
> 👤 **Bone Dozer**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The ashen hoarder moves up to twice their speed in a straight line. Each creature or object in the path of this movement is either pushed into the nearest unoccupied space outside the path, or if they have M < 3 is pushed forward until the movement ends. Any creature who is force moved forward into an obstacle is dazed (save ends).

<!-- -->
> ❗️ **Armor of Corpses (2 Malice)**
>
> | **-**       | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The ashen hoarder takes damage.
>
> **Effect:** The ashen hoarder halves the damage. If the ashen hoarder has one or more creatures impaled, the Malice cost of this feature is reduced by 1 and one impaled creature takes the other half of the damage.

<!-- -->
> ⭐️ **Bladed Body**
>
> An adjacent enemy who grabs the ashen hoarder or uses a melee ability against them takes 3 damage.

<!-- -->
> ⭐️ **Soul Singularity**
>
> When the ashen hoarder is reduced to 0 Stamina, they explode in a swirling singularity of bone shards and soul energy. Each creature within 5 squares of the ashen hoarder who has M < 3 takes 11 corruption damage. A creature killed by this damage has their soul sucked into the vortex and lost somewhere in the Abyssal Wasteland, and can't be brought back to life until their soul is recovered.

<!-- -->
> ☠️ **Skeletal Eruption (Villain Action 1)**
>
> | **Area, Weapon**           |                                       **-** |
> | -------------------------- | ------------------------------------------: |
> | **📏 8 x 3 line within 1** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 damage, vertical push 2
> - **12-16:** 11 damage, vertical push 2
> - **17+:** 14 damage, vertical push 3
>
> **Effect:** Each target is force moved straight up, then falls. A target who would normally land prone after falling is instead restrained (save ends).

<!-- -->
> ☠️ **Mobile Mine Field (Villain Action 2)**
>
> | **Area, Ranged**         |          **-** |
> | ------------------------ | -------------: |
> | **📏 10 cube within 20** | **🎯 Special** |
>
> **Effect:** The ashen hoarder sprays out six size 1M zombie mines that appear in unoccupied squares within distance. Any enemy who moves adjacent to a zombie mine for the first time in a round or starts their turn there causes the mine to explode, dealing 4 corruption damage to each creature adjacent to the mine. Any other zombie mines adjacent to the exploding mine also explode. At the start of each of the ashen hoarder's turns, each unexploded zombie mine can be moved up to 2 squares.

<!-- -->
> ☠️ **Ossuary Assault (Villain Action 3)**
>
> | **Melee, Strike, Weapon** |       **-** |
> | ------------------------- | ----------: |
> | **📏 Self; see below**    | **🎯 Self** |
>
> **Effect:** The ashen hoarder moves up to their speed and uses Claw and Blade with a double edge against one target. On a tier 3 outcome, the ashen hoarder can use Impale without spending Malice.

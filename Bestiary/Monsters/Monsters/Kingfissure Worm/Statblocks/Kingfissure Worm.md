---
agility: 1
ancestry:
  - Beast
  - Worm
ev: '108'
file_basename: Kingfissure Worm
file_dpath: Monsters/Kingfissure Worm/Statblocks
free_strike: 8
intuition: 2
item_id: kingfissure-worm
item_index: '01'
item_name: Kingfissure Worm
level: 7
might: 5
presence: -3
reason: -5
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.kingfissure-worm.statblock:kingfissure-worm
scdc:
  - 1.1.1:2.32.1:01
size: '5'
source: mcdm.monsters.v1
speed: 10
stability: 5
stamina: '420'
type: monster/kingfissure-worm/statblock
---

###### Kingfissure Worm

|     Beast, Worm     |            -             |       Level 7        |          Solo           |         EV 108         |
| :-----------------: | :----------------------: | :------------------: | :---------------------: | :--------------------: |
|   **5**<br/> Size   |    **10**<br/> Speed     | **420**<br/> Stamina |  **5**<br/> Stability   | **8**<br/> Free Strike |
| **-**<br/> Immunity | **Burrow**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+5**<br/> Might  |   **+1**<br/> Agility    |  **-5**<br/> Reason  |  **+2**<br/> Intuition  |  **-3**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the kingfissure worm can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The kingfissure worm can take two turns each round. They can't take turns consecutively.

<!-- -->
> ⭐️ **Multiple Tongues**
>
> The kingfissure worm has three tongues. Each tongue is a 5 x 1 line within 1 square of the kingfissure worm, has 35 Stamina and psychic immunity all, and can't be force moved. Each tongue enables the kingfissure worm to grab one size 3 or smaller creature or object. A tongue can be targeted by abilities only while it has a target grabbed.

<!-- -->
> 🗡 **Tongue Grab (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                          **Main action** |
> | ------------------------- | ---------------------------------------: |
> | **📏 Melee 5**            | **🎯 One creature or object per tongue** |
>
> **Power Roll + 5:**
>
> - **≤11:** 13 damage; M < 3 grabbed
> - **12-16:** 18 damage; M < 4 grabbed
> - **17+:** 22 damage; M < 5 grabbed and the target takes a bane on the Escape Grab maneuver
>
> **Effect:** The kingfissure worm must have one or more tongues to use this ability. As a maneuver, the kingfissure worm can pull up to two creatures grabbed this way adjacent to them.

<!-- -->
> 🗡 **Maw**
>
> | **Charge, Melee, Strike, Weapon** |               **Main action** |
> | --------------------------------- | ----------------------------: |
> | **📏 Melee 1**                    | **🎯 One creature or object** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 damage; push 3
> - **12-16:** 20 damage; push 5, prone
> - **17+:** 25 damage; the target is swallowed (see Swallowed)
>
> **2 Malice:** When the kingfissure worm uses the Charge main action, they ignore difficult terrain and automatically destroy mundane size 3 and smaller objects in the path of their charge. The first time the kingfissure worm moves through a creature's space during this charge, that creature takes 8 damage and is pushed up to 3 squares.

<!-- -->
> 🗡 **Consume (2 Malice)**
>
> | **Melee**      |             **Main action** |
> | -------------- | --------------------------: |
> | **📏 Melee 1** | **🎯 One grabbed creature** |
>
> **Effect:** The target is swallowed (see Swallowed).

<!-- -->
> ⚔️ **Tongue Whip**
>
> | **Melee, Ranged, Strike, Weapon** |                  **Maneuver** |
> | --------------------------------- | ----------------------------: |
> | **📏 Melee 5 or ranged 10**       | **🎯 One creature or object** |
>
> **Effect:** The kingfissure worm can use this maneuver only while they have a creature or object grabbed. The worm slams the grabbed creature or object against the target, dealing 13 damage to both. If this ability is used at range, it deals an extra 5 damage and the grabbed creature or object is released.

<!-- -->
> ❗️ **Tearing Recoil**
>
> | **-**       | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |       **🎯 Special** |
>
> **Trigger:** A tongue takes damage that doesn't reduce it to 0 Stamina.
>
> **Effect:** The kingfissure worm deals 5 damage to the creature or object the tongue had grabbed, releases that creature or object, then pulls the damaged tongue back into their mouth.

<!-- -->
> ⭐️ **Seismic King**
>
> The kingfissure worm has line of effect only within 3 squares However, they ignore concealment for creatures touching the ground and don't need line of effect to use abilities against those creatures.

<!-- -->
> ⭐️ **Swallowed**
>
> A creature swallowed by the kingfissure worm is restrained and takes 1d6 acid damage at the start of every turn. If the worm takes 25 or more damage in a single round from swallowed creatures, they immediately regurgitate all creatures they have swallowed, who land prone in unoccupied spaces within 3 squares of the kingfissure worm.

<!-- -->
> ⭐️ **Titanic Tunneler**
>
> The kingfissure worm can burrow through stone. When the worm burrows, they create a stable size 3 tunnel in the squares they move through.

<!-- -->
> ⭐️ **Unstoppable Crawler**
>
> The kingfissure worm can't be frightened or knocked prone. While the worm is restrained or slowed, they take a −2 penalty to speed instead of suffering those conditions' usual effects on speed.

<!-- -->
> ☠️ **King's Fissure (Villain Action 1)**
>
> | **Area, Weapon**            |                                       **-** |
> | --------------------------- | ------------------------------------------: |
> | **📏 20 x 4 line within 1** | **🎯 Each creature and object in the area** |
>
> **Special:** Each target must be on the ground.
>
> **Effect:** The area becomes a 10-square-deep fissure in the earth. Each target makes an **Agility test**.
>
> - **≤11:** 10 damage; the target falls into the fissure, lands prone, and can't stand (EoT)
> - **12-16:** 10 damage; the target is knocked prone and left hanging at the edge of the area
> - **17+:** The target shifts to the nearest unoccupied space outside the area.

<!-- -->
> ☠️ **Earth Breach (Villain Action 2)**
>
> | **Weapon**  |          **-** |
> | ----------- | -------------: |
> | **📏 Self** | **🎯 Special** |
>
> **Effect:** The kingfissure worm can use this villain action only while burrowing. The worm burrows up to half their speed, then breaches the surface and moves 5 squares straight up before dropping back to the ground. Each creature or object whose space the worm moves through during this movement takes 10 damage, and if they have A < 4 they are knocked prone. Any creature who is made winded by this damage is swallowed (see Swallowed).

<!-- -->
> ☠️ **Better Out Than In (Villain Action 3)**
>
> | **Area, Weapon** |                                    **-** |
> | ---------------- | ---------------------------------------: |
> | **📏 5 burst**   | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 acid damage; P < 3 weakened (save ends)
> - **12-16:** 13 acid damage; P < 4 weakened (save ends)
> - **17+:** 17 acid damage; P < 5 weakened (save ends)
>
> **Effect:** Each creature swallowed by the worm is regurgitated and automatically subject to the tier 3 outcome, then lands prone in an unoccupied space within 5 squares of the kingfissure worm.

---
agility: -2
ancestry:
  - Construct
  - Servok
  - Soulless
  - Valok
ev: '44'
file_basename: Servok Miner
file_dpath: Monsters/Valok/Statblocks
free_strike: 9
intuition: -1
item_id: servok-miner
item_index: '04'
item_name: Servok Miner
level: 9
might: 4
presence: -5
reason: -4
roles:
  - Elite Controller
scc:
  - mcdm.monsters.v1:monster.valok.statblock:servok-miner
scdc:
  - 1.1.1:2.41.1:04
size: '2'
source: mcdm.monsters.v1
speed: 5
stability: 6
stamina: '200'
type: monster/valok/statblock
---

###### Servok Miner

| Construct, Servok, Soulless, Valok |                -                |       Level 9        |    Elite Controller     |         EV 44          |
| :--------------------------------: | :-----------------------------: | :------------------: | :---------------------: | :--------------------: |
|          **2**<br/> Size           |        **5**<br/> Speed         | **200**<br/> Stamina |  **6**<br/> Stability   | **9**<br/> Free Strike |
|        **-**<br/> Immunity         | **Burrow, climb**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|         **+4**<br/> Might          |       **-2**<br/> Agility       |  **-4**<br/> Reason  |  **-1**<br/> Intuition  |  **-5**<br/> Presence  |

<!-- -->
> 🗡 **Drill Press (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 13 damage; M < 2 restrained (save ends) and prone
> - **12-16:** 18 damage; M < 3 restrained (save ends) and prone
> - **17+:** 22 damage; prone; M < 4 restrained (save ends)
>
> **Effect:** In suitably soft ground, a target restrained this way is etrenched in a 1-square-deep hole.

<!-- -->
> 🔳 **Unload Rocks (3 Malice)**
>
> | **Area**               |                          **Main action** |
> | ---------------------- | ---------------------------------------: |
> | **📏 4 cube within 1** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes an **Agility test**.
>
> - **≤11:** 14 damage; slide 4; the miner's allies have concealment from the target (save ends)
> - **12-16:** 11 damage; slide 2
> - **17+:** 7 damage
>
> The area is difficult terrain.

<!-- -->
> 🔳 **Break Ground (5 Malice)**
>
> | **Area**                    |                             **Maneuver** |
> | --------------------------- | ---------------------------------------: |
> | **📏 20 x 1 line within 1** | **🎯 Each enemy and object in the area** |
>
> **Effect:** A 5-square-deep fissure opens along the ground in the area. Each ally in the area can shift into the nearest unoccupied space outside the fissure. Each target makes an **Agility test**.
>
> - **≤11:** 14 damage; the target falls into the fissure, and is prone and can't stand (EoT)
> - **12-16:** 11 damage; the target is prone and hanging onto the edge of the fissure
> - **17+:** 7 damage; the target can shift into the nearest unoccupied space outside the fissure

<!-- -->
> ❗️ **Miner Inconvenience (2 Malice)**
>
> | **Area**    | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The miner is targeted by a strike.
>
> **Effect:** Until the end of the round, dust and dirt billow in a 2 burst around the miner's initial space. While the miner is in the area, they ignore the nondamaging effects of any strike made against them, including the triggering strike.

<!-- -->
> ⭐️ **Valiar Tunneler**
>
> The miner can burrow through stone and metal. When the miner burrows, they create a stable size 2 tunnel in their wake.

<!-- -->
> ⭐️ **Servok Siege Machine**
>
> The miner ignores difficult terrain, and their abilities deal an extra 15 damage to objects.

<!-- -->
> ⭐️ **Crafted to Perfection**
>
> The miner's shape can't be changed by any external effect.

<!-- -->
> ⭐️ **Valiar Might**
>
> While the miner isn't bleeding, weakened, or winded, any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.

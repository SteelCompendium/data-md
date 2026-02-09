---
agility: 0
ancestry:
  - Construct
  - Multivok
  - Soulless
  - Valok
ev: '44'
file_basename: Multivok Bodyguard
file_dpath: Monsters/Valok/Statblocks
free_strike: 9
intuition: 1
item_id: multivok-bodyguard
item_index: '01'
item_name: Multivok Bodyguard
level: 9
might: 4
presence: -4
reason: -2
roles:
  - Elite Defender
scc:
  - mcdm.monsters.v1:monster.valok.statblock:multivok-bodyguard
scdc:
  - 1.1.1:2.42.1:01
size: '2'
source: mcdm.monsters.v1
speed: 5
stability: 5
stamina: '240'
type: monster/valok/statblock
---

###### Multivok Bodyguard

| Construct, Multivok, Soulless, Valok |          -          |       Level 9        |     Elite Defender      |         EV 44          |
| :----------------------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|           **2**<br/> Size            |  **5**<br/> Speed   | **240**<br/> Stamina |  **5**<br/> Stability   | **9**<br/> Free Strike |
|         **-**<br/> Immunity          | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|          **+4**<br/> Might           | **0**<br/> Agility  |  **-2**<br/> Reason  |  **+1**<br/> Intuition  |  **-4**<br/> Presence  |

<!-- -->
> 🏹 **Gatling Bolt Gun (Signature Ability)**
>
> | **Ranged, Strike, Weapon** |                 **Main action** |
> | -------------------------- | ------------------------------: |
> | **📏 Ranged 10**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 13 damage
> - **12-16:** 18 damage
> - **17+:** 22 damage; A < 4 bleeding (save ends)

<!-- -->
> 🗡 **Valiar Axe (3 Malice)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 2**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 15 damage; M < 2 weakened (save ends)
> - **12-16:** 21 damage; M < 3 weakened (save ends)
> - **17+:** 26 damage; prone; M < 4 weakened (save ends)
>
> **Effect:** The bodyguard has a double edge on this ability if it was previously used against the same target in this encounter.

<!-- -->
> ❇️ **Magnetic Pull**
>
> | **Area**        |                             **Maneuver** |
> | --------------- | ---------------------------------------: |
> | **📏 10 burst** | **🎯 Each enemy and object in the area** |
>
> **Special:** This ability targets only metal-clad enemies and metal objects of size 3 or smaller.
>
> **Effect:** Each target is pulled up to 8 squares, or if they have M < 3, they are pulled up to 15 squares. The bodyguard can make a free strike against each target who ends this forced movement adjacent to them.

<!-- -->
> ❗️ **Valiar Cloak**
>
> | **Melee**      | **Triggered action** |
> | -------------- | -------------------: |
> | **📏 Melee 2** |          **🎯 Self** |
>
> **Trigger:** One ally within distance is targeted by an enemy's ability. The bodyguard can use this ability after seeing the outcome of the power roll.
>
> **Effect:** The bodyguard becomes the triggering ability's target instead.

<!-- -->
> ⭐️ **Multivok Maintenance**
>
> At the start of the bodyguard's turn, each servok within 2 squares of them regains 15 Stamina.

<!-- -->
> ⭐️ **Crafted to Perfection**
>
> The bodyguard's shape can't be changed by any external effect.

<!-- -->
> ⭐️ **Valiar Might**
>
> While the bodyguard isn't bleeding, weakened, or winded, any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.

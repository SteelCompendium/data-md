---
agility: -2
ancestry:
  - Construct
  - Servok
  - Soulless
  - Valok
ev: '44'
file_basename: Servok Builder
file_dpath: Monsters/Valok/Statblocks
free_strike: 10
intuition: -1
item_id: servok-builder
item_index: '03'
item_name: Servok Builder
level: 9
might: 4
presence: -5
reason: -4
roles:
  - Elite Brute
scc:
  - mcdm.monsters.v1:monster.valok.statblock:servok-builder
scdc:
  - 1.1.1:2.42.1:03
size: '3'
source: mcdm.monsters.v1
speed: 5
stability: 8
stamina: '240'
type: monster/valok/statblock
---

###### Servok Builder

| Construct, Servok, Soulless, Valok |          -          |       Level 9        |       Elite Brute       |          EV 44          |
| :--------------------------------: | :-----------------: | :------------------: | :---------------------: | :---------------------: |
|          **3**<br/> Size           |  **5**<br/> Speed   | **240**<br/> Stamina |  **8**<br/> Stability   | **10**<br/> Free Strike |
|        **-**<br/> Immunity         | **-**<br/> Movement |          -           | **-**<br/> With Captain |   **-**<br/> Weakness   |
|         **+4**<br/> Might          | **-2**<br/> Agility |  **-4**<br/> Reason  |  **-1**<br/> Intuition  |  **-5**<br/> Presence   |

<!-- -->
> 🔳 **Wrecking Ball (Signature Ability)**
>
> | **Area, Ranged, Weapon** |                          **Main action** |
> | ------------------------ | ---------------------------------------: |
> | **📏 3 cube within 5**   | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target must make either an Agility test or an **Intuition test**.
>
> - **≤11:** 15 damage; push 5, prone
> - **12-16:** 12 damage; push 3
> - **17+:** 8 damage

<!-- -->
> 🗡 **Construction Arm**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 3**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 16 damage
> - **12-16:** 23 damage; grabbed
> - **17+:** 28 damage; grabbed; M < 4 vertical push 5

<!-- -->
> 🔳 **Lay the Foundation (3 Malice)**
>
> | **Area**                   | **Main action** |
> | -------------------------- | --------------: |
> | **📏 6 x 3 line within 1** |  **🎯 Special** |
>
> **Effect:** The area is covered in wet concrete and is difficult terrain. An enemy who starts their turn in the concrete makes a **Might test**.
>
> - **≤11:** Restrained (EoT)
> - **12-16:** Slowed (EoT)
> - **17+:** No effect

<!-- -->
> 🔳 **Build Wall**
>
> | **Area, Ranged**       |   **Maneuver** |
> | ---------------------- | -------------: |
> | **📏 6 wall within 3** | **🎯 Special** |
>
> **Effect:** The builder creates a concrete wall. They can also remove any unoccupied squares of wet concrete within 3 squares of them, creating two additional squares of wall for each square of concrete removed.

<!-- -->
> ❗️ **Sputter (1 Malice)**
>
> | **Melee**      |                **Free triggered action** |
> | -------------- | ---------------------------------------: |
> | **📏 Melee 3** | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object within distance deals damage to the builder.
>
> **Power Roll + 4:**
>
> - **≤11:** A < 2 restrained (save ends)
> - **12-16:** A < 3 restrained (save ends)
> - **17+:** A < 4 restrained (save ends)
>
> **Effect:** While a creature is restrained this way, or if the target is an object, the target and their space are encased in wet concrete. A creature no longer restrained leaves squares of wet concrete behind.

<!-- -->
> ⭐️ **Servok Siege Machine**
>
> The builder ignores difficult terrain, and their abilities deal an extra 15 damage to objects.

<!-- -->
> ⭐️ **Crafted to Perfection**
>
> The builder's shape can't be changed by any external effect.

<!-- -->
> ⭐️ **Valiar Might**
>
> While the builder isn't bleeding, weakened, or winded, any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.

---
agility: 3
ancestry:
  - Humanoid
  - Soulless
  - War Dog
ev: '48'
file_basename: Soulbinder Psyche
file_dpath: Monsters/War Dogs/Statblocks
free_strike: 10
intuition: 4
item_id: soulbinder-psyche
item_index: '39'
item_name: Soulbinder Psyche
level: 10
might: 1
presence: 5
reason: 3
roles:
  - Elite Hexer
scc:
  - mcdm.monsters.v1:monster.war-dogs.statblock:soulbinder-psyche
scdc:
  - 1.1.1:2.49.1:39
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: '220'
type: monster/war-dogs/statblock
---

###### Soulbinder Psyche

| Humanoid, Soulless, War Dog |              -               |       Level 10       |       Elite Hexer       |          EV 48          |
| :-------------------------: | :--------------------------: | :------------------: | :---------------------: | :---------------------: |
|      **1M**<br/> Size       |       **5**<br/> Speed       | **220**<br/> Stamina |  **1**<br/> Stability   | **10**<br/> Free Strike |
|     **-**<br/> Immunity     | **Fly, hover**<br/> Movement |          -           | **-**<br/> With Captain |   **-**<br/> Weakness   |
|      **+1**<br/> Might      |     **+3**<br/> Agility      |  **+3**<br/> Reason  |  **+4**<br/> Intuition  |  **+5**<br/> Presence   |

<!-- -->
> 🏹 **Soulbind (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 holy damage; R < 3 the target is soulbound (save ends)
> - **12-16:** 20 holy damage; R < 4 the target is soulbound (save ends)
> - **17+:** 24 holy damage; R < 5 the target is soulbound (save ends)
>
> **Effect:** A soulbound creature can't benefit from edges or double edges, and can't gain or use surges.

<!-- -->
> 🔳 **Soulstorm (2 Malice)**
>
> | **Area, Magic, Ranged** |               **Main action** |
> | ----------------------- | ----------------------------: |
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 corruption damage; P < 3 weakened (EoT)
> - **12-16:** 12 corruption damage; P < 4 weakened (EoT)
> - **17+:** 15 corruption damage; P < 5 weakened (EoT)
>
> **Effect:** The area is difficult terrain until the start of Psyche's next turn At the start of each of her turns, Psyche can use a maneuver to maintain this effect, move the area up to 5 squares, and make the power roll against each creature in the area's new location.
>
> **1 Malice:** Until the start of Psyche's next turn, if this ability makes a creature weakened, that creature is also soulbound (save ends; see Soulbind above).

<!-- -->
> ❇️ **Command the Awakened**
>
> | **Magic, Ranged** |                            **Maneuver** |
> | ----------------- | --------------------------------------: |
> | **📏 5 burst**    | **🎯 Each soulbound enemy in the area** |
>
> **Effect:** Each target takes 5 damage from a self-inflicted wound, and if they have M < 4 Psyche slides them up to 5 squares.

<!-- -->
> ❗️ **Spirit Form**
>
> | **-**       | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** An enemy moves within 2 squares of Psyche.
>
> **Effect:** Psyche moves up to 5 squares, and has damage immunity 5 and ignores difficult terrain during this movement. The first time she moves through any creature during this movement, that creature takes 5 corruption damage.

<!-- -->
> ❗️ **Vengeance for the Slain**
>
> | **Ranged**       | **Free triggered action** |
> | ---------------- | ------------------------: |
> | **📏 Ranged 10** |          **🎯 One enemy** |
>
> **Trigger:** A war dog within distance is made winded or reduced to 0 Stamina.
>
> **Effect:** The target loses all their surges and takes 5 corruption damage.
>
> **1 Malice:** The target also takes a bane on their next strike.

<!-- -->
> ⭐️ **Immortal Soul**
>
> When Psyche is reduced to 0 Stamina, her spirit surrounds the nearest war dog, who has damage immunity 2, deals an extra 5 damage on strikes, and can use the following Immortal Flare maneuver until the end of the encounter. That war dog also gains the Immortal Soul trait, and transfers this effect to the nearest war dog when they die.

<!-- -->
> 🏹 **Immortal Flare**
>
> | **Magic, Ranged** |                  **Maneuver** |
> | ----------------- | ----------------------------: |
> | **📏 Ranged 10**  | **🎯 One creature or object** |
>
> **Effect:** The target takes 10 psychic damage.

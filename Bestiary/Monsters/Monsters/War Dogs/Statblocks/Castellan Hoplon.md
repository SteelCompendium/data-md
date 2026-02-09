---
agility: 2
ancestry:
  - Humanoid
  - Soulless
  - War Dog
ev: '48'
file_basename: Castellan Hoplon
file_dpath: Monsters/War Dogs/Statblocks
free_strike: 10
intuition: 3
item_id: castellan-hoplon
item_index: '37'
item_name: Castellan Hoplon
level: 10
might: 5
presence: 4
reason: 4
roles:
  - Elite Defender
scc:
  - mcdm.monsters.v1:monster.war-dogs.statblock:castellan-hoplon
scdc:
  - 1.1.1:2.50.1:37
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: '260'
type: monster/war-dogs/statblock
---

###### Castellan Hoplon

| Humanoid, Soulless, War Dog |          -          |       Level 10       |     Elite Defender      |          EV 48          |
| :-------------------------: | :-----------------: | :------------------: | :---------------------: | :---------------------: |
|      **1M**<br/> Size       |  **5**<br/> Speed   | **260**<br/> Stamina |  **3**<br/> Stability   | **10**<br/> Free Strike |
| **Damage 3**<br/> Immunity  | **-**<br/> Movement |          -           | **-**<br/> With Captain |   **-**<br/> Weakness   |
|      **+5**<br/> Might      | **+2**<br/> Agility |  **+4**<br/> Reason  |  **+3**<br/> Intuition  |  **+4**<br/> Presence   |

<!-- -->
> 🗡 **Inspiring Strike (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 damage
> - **12-16:** 20 damage; push 3
> - **17+:** 24 damage; push 5
>
> **Effect:** Two allies within 10 squares of Hoplon each shift up to their speed, then can take the Defend main action or make a free strike.

<!-- -->
> 🏹 **Summon the Onyx Tower (5 Malice)**
>
> | **Ranged**       |   **Maneuver** |
> | ---------------- | -------------: |
> | **📏 Ranged 15** | **🎯 Special** |
>
> **Effect:** A 10-square-tall tower made of black stone shimmers into being in an unoccupied space that is 5 squares on a side. The tower has three floors, an entrance in the middle of each side on the ground floor, and a crenelated rooftop. Any war dog inside or adjacent to the tower has damage immunity 2 and regains 5 Stamina at the start of each of their turns, and war dogs inside the tower can observe through and have line of effect through its walls. This ability can be used only once per encounter.

<!-- -->
> ❇️ **Shield Warden (2 Malice)**
>
> | **Area**       |                  **Maneuver** |
> | -------------- | ----------------------------: |
> | **📏 3 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** R < 3 taunted (EoT)
> - **12-16:** R < 4 taunted (EoT)
> - **17+:** R < 5 taunted (EoT)
>
> **Effect:** Until the start of Hoplon's next turn, any enemy ability that includes him as a target takes a bane.

<!-- -->
> ❗️ **Timely Intervention**
>
> | **Magic**   | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** An enemy within 10 squares targets an ally with an ability.
>
> **Effect:** Hoplon teleports to an unoccupied space adjacent to the enemy and becomes the new target of the ability. He can then make a free strike against the enemy, and if that enemy has R < 4 they are taunted until the end of their next turn.

<!-- -->
> ⭐️ **Hold the Line**
>
> Each ally within 3 squares of Hoplon has cover and damage immunity 2.

<!-- -->
> ⭐️ **Last Stand**
>
> The first time in an encounter that Hoplon is reduced to 0 Stamina, he instead has 1 Stamina and gains damage immunity 10 until the end of his next turn. When Hoplon is reduced to 0 Stamina again, each ally within 5 squares of him gains damage immunity 3 and deals an extra 5 damage on strikes, all until the end of the encounter.

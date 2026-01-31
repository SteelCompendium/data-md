---
agility: 3
ancestry:
  - Human
  - Humanoid
ev: '20'
file_basename: Human Bandit Chief
file_dpath: Monsters/Humans/Statblocks
free_strike: 5
intuition: 3
item_id: human-bandit-chief
item_index: 09
item_name: Human Bandit Chief
level: 3
might: 2
presence: 2
reason: 2
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.humans.statblock:human-bandit-chief
scdc:
  - 1.1.1:2.19.1:09
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: '120'
type: monster/humans/statblock
---

###### Human Bandit Chief

|              Human, Humanoid              |          -          |       Level 3        |         Leader          |         EV 20          |
| :---------------------------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|             **1M**<br/> Size              |  **5**<br/> Speed   | **120**<br/> Stamina |  **2**<br/> Stability   | **5**<br/> Free Strike |
| **Corruption 4, psychic 4**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|             **+2**<br/> Might             | **+3**<br/> Agility |  **+2**<br/> Reason  |  **+3**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🗡 **Whip and Magic Longsword (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |               **Main action** |
> | -------------------------------- | ----------------------------: |
> | **📏 Melee 2**                   | **🎯 Two enemies or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; pull 1
> - **12-16:** 12 damage; pull 2
> - **17+:** 15 damage; pull 3
>
> **Effect:** Any target who is adjacent to the bandit chief after the power roll is resolved takes 3 corruption damage.
>
> **2 Malice:** This ability targets one additional target.

<!-- -->
> 🗡 **Kneel, Peasant!**
>
> | **Melee**      |     **Maneuver** |
> | -------------- | ---------------: |
> | **📏 Melee 1** | **🎯 One enemy** |
>
> **Power Roll + 3:**
>
> - **≤11:** Push 1; M < 1 prone
> - **12-16:** Push 2; M < 2 prone
> - **17+:** Push 4; M < 3 prone
>
> **2 Malice:** The ability takes the Area keyword, loses the Melee keyword, and is a 1 burst that targets each enemy in the area.

<!-- -->
> ❗️ **Bloodstones**
>
> | **Magic**   | **Triggered action** |
> | ----------- | -------------------: |
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** The bandit chief makes a power roll.
>
> **Effect:** The bandit chief takes 5 corruption damage and increases the outcome of the power roll by one tier. This damage can't be reduced in any way.

<!-- -->
> ⭐️ **End Effect**
>
> At the end of each of their turns, the bandit chief can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

<!-- -->
> ⭐️ **Supernatural Insight**
>
> The bandit chief ignores concealment if it's granted by a supernatural effect.

<!-- -->
> ☠️ **Shoot! (Villain Action 1)**
>
> | **Area**        |                                  **-** |
> | --------------- | -------------------------------------: |
> | **📏 10 burst** | **🎯 Each artillery ally in the area** |
>
> **Effect:** Each target makes a ranged free strike.

<!-- -->
> ☠️ **Form Up! (Villain Action 2)**
>
> | **Area**        |                        **-** |
> | --------------- | ---------------------------: |
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target shifts up to their speed. Additionally, until the end of the encounter, while the bandit chief or any ally is adjacent to a target, they have damage immunity 2.

<!-- -->
> ☠️ **Lead From the Front (Villain Action 3)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The bandit chief shifts up to 10 squares regardless of their speed. During or after this movement, they can use their Whip and Magic Longsword against up to four targets. Additionally, one ally adjacent to each target can make a free strike against that target.

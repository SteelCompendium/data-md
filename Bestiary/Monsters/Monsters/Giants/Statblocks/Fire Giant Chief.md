---
agility: 3
ancestry:
  - Fire Giant
  - Giant
ev: '44'
file_basename: Fire Giant Chief
file_dpath: Monsters/Giants/Statblocks
free_strike: 9
intuition: 2
item_id: fire-giant-chief
item_index: '01'
item_name: Fire Giant Chief
level: 9
might: 5
presence: 3
reason: 0
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.giants.statblock:fire-giant-chief
scdc:
  - 1.1.1:2.22.1:01
size: '5'
source: mcdm.monsters.v1
speed: 10
stability: 10
stamina: '240'
type: monster/giants/statblock
---

###### Fire Giant Chief

|     Fire Giant, Giant     |          -          |       Level 9        |         Leader          |         EV 44          |
| :-----------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|      **5**<br/> Size      |  **10**<br/> Speed  | **240**<br/> Stamina |  **10**<br/> Stability  | **9**<br/> Free Strike |
| **Fire 10**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|     **+5**<br/> Might     | **+3**<br/> Agility |  **0**<br/> Reason   |  **+2**<br/> Intuition  |  **+3**<br/> Presence  |

<!-- -->
> 🔳 **Roiling Fist (Signature Ability)**
>
> | **Area, Ranged, Weapon** |                          **Main action** |
> | ------------------------ | ---------------------------------------: |
> | **📏 3 cube within 4**   | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes either an **Agility test** or an **Intuition test**.
>
> - **≤11:** 18 fire damage; prone; weakened (save ends)
> - **12-16:** 14 fire damage; prone
> - **17+:** 9 fire damage

<!-- -->
> 🗡 **Burning Kick**
>
> | **Charge, Melee, Strike, Weapon** |                 **Main action** |
> | --------------------------------- | ------------------------------: |
> | **📏 Melee 4**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 14 damage; push 5; A < 3 9 fire damage
> - **12-16:** 19 damage; push 10; A < 4 9 fire damage
> - **17+:** 23 damage; push 15; A < 5 9 fire damage

<!-- -->
> 🔳 **Lava Pillar (3 Malice)**
>
> | **Area, Ranged**        |                             **Maneuver** |
> | ----------------------- | ---------------------------------------: |
> | **📏 3 cube within 10** | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 5 fire damage; M < 3 vertical push 3
> - **12-16:** 7 fire damage; M < 4 vertical push 4
> - **17+:** 9 fire damage; M < 5 vertical push 5

<!-- -->
> ❗️ **Fuel the Fire (1 Malice)**
>
> | **Ranged**       |       **Triggered action** |
> | ---------------- | -------------------------: |
> | **📏 Ranged 12** | **🎯 The triggering ally** |
>
> **Trigger:** A fire giant ally within distance makes a strike.
>
> **Effect:** The strike has a double edge and deals an extra 10 fire damage.

<!-- -->
> ☠️ **Forward! (Villain Action 1)**
>
> | **Area**        |                                 **-** |
> | --------------- | ------------------------------------: |
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target shifts up to their speed and can make a free strike. Any enemy who takes damage from a free strike this way and who has A < 4 is burning (save ends). A burning enemy takes 1d6 fire damage at the start of each of their turns.

<!-- -->
> ☠️ **Burning Legion (Villain Action 2)**
>
> | **Ranged**       |          **-** |
> | ---------------- | -------------: |
> | **📏 Ranged 15** | **🎯 Special** |
>
> **Effect:** The chief shifts up to 10 squares. Five fire giant fireballer then arrive in unoccupied spaces within distance.

<!-- -->
> ☠️ **All to Cinders (Villain Action 3)**
>
> | **Area**        |                                            **-** |
> | --------------- | -----------------------------------------------: |
> | **📏 10 burst** | **🎯 Self and each fire giant ally in the area** |
>
> **Effect:** Each target unleashes a wave of fire, and each enemy within 2 squares of any target makes an Agility test. An enemy affected by two targets takes a bane on the test, while an enemy affected by three or more targets has a double bane.
>
> - **≤11:** 18 fire damage
> - **12-16:** 14 fire damage
> - **17+:** 9 fire damage

<!-- -->
> ⭐️ **Scorching Skin**
>
> Whenever an adjacent enemy grabs the chief or uses a melee ability against them, that enemy takes 9 fire damage, and if they have M < 4 they are weakened (save ends)

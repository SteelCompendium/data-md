---
agility: 2
ancestry:
  - Accursed
  - Humanoid
  - Minotaur
ev: '20'
file_basename: Minotaur
file_dpath: Monsters/Minotaurs/Statblocks
free_strike: 5
intuition: 1
item_id: minotaur
item_index: '02'
item_name: Minotaur
level: 3
might: 2
presence: -1
reason: 0
roles:
  - Elite Harrier
scc:
  - mcdm.monsters.v1:monster.minotaurs.statblock:minotaur
scdc:
  - 1.1.1:2.20.1:02
size: '2'
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: '100'
type: monster/minotaurs/statblock
---

###### Minotaur

| Accursed, Humanoid, Minotaur |          -          |       Level 3        |      Elite Harrier      |         EV 20          |
| :--------------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|       **2**<br/> Size        |  **8**<br/> Speed   | **100**<br/> Stamina |  **2**<br/> Stability   | **5**<br/> Free Strike |
|     **-**<br/> Immunity      | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|      **+2**<br/> Might       | **+2**<br/> Agility |  **0**<br/> Reason   |  **+1**<br/> Intuition  |  **-1**<br/> Presence  |

<!-- -->
> 🗡 **Flail and Blade (Signature Ability)**
>
> | **Charge, Melee, Strike, Weapon** |                 **Main action** |
> | --------------------------------- | ------------------------------: |
> | **📏 Melee 2**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; push 1
> - **12-16:** 11 damage; push 2
> - **17+:** 14 damage; push 3
>
> **Effect:** The minotaur shifts up to 3 squares.

<!-- -->
> 👤 **Primal Bay (3 Malice)**
>
> | **-**       | **Main action** |
> | ----------- | --------------: |
> | **📏 Self** |     **🎯 Self** |
>
> **Effect:** Until the end of their next turn, the minotaur has damage immunity 2 and deals an extra 5 damage with strikes. On their next turn, the minotaur can use one additional maneuver.

<!-- -->
> 🗡 **Goring Horns (5 Malice)**
>
> | **Charge, Melee, Strike, Weapon** |                  **Maneuver** |
> | --------------------------------- | ----------------------------: |
> | **📏 Melee 2**                    | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; I < 0 dazed (save ends)
> - **12-16:** 8 damage; I < 1 dazed (save ends)
> - **17+:** 9 damage; I < 2 dazed (save ends)
>
> **Effect:** If this ability is used as part of the Charge main action, its potency increases by 1.

<!-- -->
> ❗️ **Retaliatory Strike**
>
> | **Ranged**      |           **Triggered action** |
> | --------------- | -----------------------------: |
> | **📏 Ranged 8** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the minotaur.
>
> **Effect:** The minotaur uses the Charge main action and either Flail and Blade or Goring Horns against the target.

<!-- -->
> ⭐️ **Minotaur Sense**
>
> The minotaur can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.

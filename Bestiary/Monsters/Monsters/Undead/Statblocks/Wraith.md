---
agility: 2
ancestry:
  - Undead
ev: '6'
file_basename: Wraith
file_dpath: Monsters/Undead/Statblocks
free_strike: 2
intuition: 1
item_id: wraith
item_index: '21'
item_name: Wraith
level: 4
might: -2
presence: 3
reason: 1
roles:
  - Horde Hexer
scc:
  - mcdm.monsters.v1:monster.undead.statblock:wraith
scdc:
  - 1.1.1:2.8.1:21
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 1
stamina: '25'
type: monster/undead/statblock
---

###### Wraith

|                  Undead                  |              -               |       Level 4       |       Horde Hexer       |          EV 6          |
| :--------------------------------------: | :--------------------------: | :-----------------: | :---------------------: | :--------------------: |
|             **1M**<br/> Size             |       **8**<br/> Speed       | **25**<br/> Stamina |  **1**<br/> Stability   | **2**<br/> Free Strike |
| **Corruption 4, poison 4**<br/> Immunity | **Fly, hover**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|            **-2**<br/> Might             |     **+2**<br/> Agility      | **+1**<br/> Reason  |  **+1**<br/> Intuition  |  **+3**<br/> Presence  |

<!-- -->
> 🗡 **Chilling Gravetouch (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |               **Main action** |
> | -------------------------------- | ----------------------------: |
> | **📏 Melee 1**                   | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 cold damage; P < 1 slowed (save ends)
> - **12-16:** 7 cold damage; P < 2 slowed (save ends)
> - **17+:** 9 cold damage; P < 3 slowed (save ends)
>
> **Effect:** Any living creature who dies from this damage rises at the start of the next round as a ghoul craver under the Director's control.

<!-- -->
> 👤 **Hidden Movement**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The wraith turns invisible, moves up to their speed, and is visible again.

<!-- -->
> ❗️ **Stolen Vitality (1 Malice)**
>
> | **Magic, Ranged** |      **Free triggered action** |
> | ----------------- | -----------------------------: |
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** An enemy within distance regains Stamina.
>
> **Effect:** The target regains only half the Stamina, and the wraith regains the remaining Stamina.

<!-- -->
> ⭐️ **Agonizing Phasing**
>
> The wraith can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the wraith moves through a creature, that creature takes 5 corruption damage and takes a bane on their next strike. The wraith doesn't take damage from being force moved into objects.

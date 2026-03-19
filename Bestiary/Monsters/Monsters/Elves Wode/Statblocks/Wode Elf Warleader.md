---
agility: 3
ancestry:
  - Fey
  - Humanoid
  - Wode Elf
ev: '20'
file_basename: Wode Elf Warleader
file_dpath: Monsters/Elves Wode/Statblocks
free_strike: 5
intuition: 2
item_id: wode-elf-warleader
item_index: '12'
item_name: Wode Elf Warleader
level: 3
might: 2
presence: 2
reason: 2
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.elves-wode.statblock:wode-elf-warleader
scdc:
  - 1.1.1:2.28.1:12
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 2
stamina: '120'
type: monster/elves-wode/statblock
---

###### Wode Elf Warleader

| Fey, Humanoid, Wode Elf |             -              |       Level 3        |         Leader          |         EV 20          |
| :---------------------: | :------------------------: | :------------------: | :---------------------: | :--------------------: |
|    **1M**<br/> Size     |      **7**<br/> Speed      | **120**<br/> Stamina |  **2**<br/> Stability   | **5**<br/> Free Strike |
|   **-**<br/> Immunity   | **Teleport**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|    **+2**<br/> Might    |    **+3**<br/> Agility     |  **+2**<br/> Reason  |  **+2**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> 🗡 **Wodeblade (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |                 **Main action** |
> | -------------------------------- | ------------------------------: |
> | **📏 Melee 1**                   | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; M < 1 restrained (save ends)
> - **12-16:** 12 damage; M < 2 restrained (save ends)
> - **17+:** 15 damage; M < 3 restrained (save ends)
>
> **Effect:** The warleader can teleport up to 3 squares between each strike.
>
> **2 Malice:** A target restrained by this ability takes an extra 3 damage.

<!-- -->
> ❇️ **Fairness Is a Human Concept (5 Malice)**
>
> | **Area**        |                 **Maneuver** |
> | --------------- | ---------------------------: |
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each non-minion target can make a free strike, then each target shifts up to 3 squares. A target who has cover or concealment at the end of this shift can attempt to hide at the end of the warleader's turn.

<!-- -->
> ❗️ **Wode Sickness**
>
> | **Ranged**       | **Triggered action** |
> | ---------------- | -------------------: |
> | **📏 Ranged 10** |     **🎯 One enemy** |
>
> **Trigger:** An ally ends their turn.
>
> **Effect:** The target must not have taken their turn this round. The target takes their turn immediately, and if they have P < 2 they are bleeding and take a bane on strikes until the end of their turn.

<!-- -->
> ⭐️ **End Effect**
>
> At the end of each of their turns, the warleader can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

<!-- -->
> ⭐️ **Into the Green**
>
> The warleader can attempt to hide at the end of each of their turns.

<!-- -->
> ⭐️ **Masking Glamor**
>
> Abilities targeting the warleader that would take a bane from cover or concealment have a double bane instead.

<!-- -->
> ☠️ **You Will All Witness my Blade (Villain Action 1)**
>
> | **Area**       |                         **-** |
> | -------------- | ----------------------------: |
> | **📏 5 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** The warleader uses Wodeblade against each target and gains an edge on the power roll.

<!-- -->
> ☠️ **Suppressing Volley (Villain Action 2)**
>
> | **Area**       |                        **-** |
> | -------------- | ---------------------------: |
> | **📏 5 burst** | **🎯 Each ally in the area** |
>
> **Effect:** The warleader can use Wodeblade. Each target can then make a free strike.

<!-- -->
> ☠️ **Is It Now or Is It Then? (Villain Action 3)**
>
> | **Area**       |                                 **-** |
> | -------------- | ------------------------------------: |
> | **📏 5 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target is invisible until the start of the next round. The warleader then uses Wodeblade.

---
agility: 2
ancestry:
  - Fey
  - High Elf
  - Humanoid
ev: '20'
file_basename: High Elf Ordinator
file_dpath: Monsters/Elves High/Statblocks
free_strike: 5
intuition: 2
item_id: high-elf-ordinator
item_index: '07'
item_name: High Elf Ordinator
level: 3
might: 0
presence: 3
reason: 3
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.elves-high.statblock:high-elf-ordinator
scdc:
  - 1.1.1:2.13.1:07
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: '120'
type: monster/elves-high/statblock
---

###### High Elf Ordinator

| Fey, High Elf, Humanoid |           -           |       Level 3        |         Leader          |         EV 20          |
| :---------------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|    **1M**<br/> Size     |   **5**<br/> Speed    | **120**<br/> Stamina |  **0**<br/> Stability   | **5**<br/> Free Strike |
|   **-**<br/> Immunity   | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|    **0**<br/> Might     |  **+2**<br/> Agility  |  **+3**<br/> Reason  |  **+2**<br/> Intuition  |  **+3**<br/> Presence  |

<!-- -->
> 🏹 **Lightning Rod (Signature Ability)**
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 lightning damage; R < 1 dazed (save ends)
> - **12-16:** 14 lightning damage; R < 2 dazed (save ends)
> - **17+:** 17 lightning damage; R < 3 dazed (save ends)
>
> **Effect:** Until the start of the ordinator's next turn, each ally high elf in the encounter gains an edge on ability rolls against the target.

<!-- -->
> ❇️ **Elemental Uproar**
>
> | **Area, Magic** |                           **Maneuver** |
> | --------------- | -------------------------------------: |
> | **📏 10 burst** | **🎯 Each elemental ally in the area** |
>
> **Effect:** Each target can move up to their speed or make a free strike. Elemental mote targets can, instead, use their Spark of Life trait.

<!-- -->
> 🏹 **Summon Elemental (2 Malice)**
>
> | **Ranged**       |   **Maneuver** |
> | ---------------- | -------------: |
> | **📏 Ranged 10** | **🎯 Special** |
>
> **Effect:** The ordinator summons four elemental motes or four soot crows into unoccupied space within distance.
>
> **3 Malice:** The ordinator instead summons one ceramic horse or one winded brambleguard into an unoccupied space within distance.

<!-- -->
> ❗️ **Enough!**
>
> | **Ranged**       |        **Triggered action** |
> | ---------------- | --------------------------: |
> | **📏 Ranged 10** | **🎯 The triggering enemy** |
>
> **Trigger:** An enemy within distance uses an ability against the ordinator or any ally within distance.
>
> **Effect:** The ordinator uses Lightning Rod against the target after the ability is resolved.

<!-- -->
> ⭐️ **Otherworldly Blessing**
>
> At the start of each of their turns, the ordinator can choose one or more effects on them that can be ended by a saving throw. The effects instead end at the end of the ordinator's turn.

<!-- -->
> ☠️ **Fountains Roar, Now Free From the Earth (Villain Action 1)**
>
> | **Area, Magic** |                        **-** |
> | --------------- | ---------------------------: |
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target glows briefly, and can end one effect on themself then move up to their speed.

<!-- -->
> ☠️ **And the Sun Forsook Her Children (Villain Action 2)**
>
> | **Area, Magic, Ranged** |                         **-** |
> | ----------------------- | ----------------------------: |
> | **📏 5 cube within 10** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes a **Presence test**.
>
> - **≤11:** 12 corruption damage; pull 5 toward the center of the cube
> - **12-16:** 9 corruption damage; pull 3 toward the center of the cube
> - **17+:** Pull 1 toward the center of the cube
>
> **Effect:** The area turns dark and distorted, and is difficult terrain for enemies.

<!-- -->
> ☠️ **But We Will Change Her Mind (Villain Action 3)**
>
> | **Area, Magic** |                                 **-** |
> | --------------- | ------------------------------------: |
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target's free strike now has the Magic keyword and can target two creatures or objects. Additionally, each target glows with magic.

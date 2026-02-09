---
agility: 2
ancestry:
  - Devil
  - Infernal
ev: '28'
file_basename: Devil Jurist
file_dpath: Monsters/Devils/Statblocks
free_strike: 7
intuition: 1
item_id: devil-jurist
item_index: '06'
item_name: Devil Jurist
level: 5
might: 0
presence: 3
reason: 1
roles:
  - Elite Artillery
scc:
  - mcdm.monsters.v1:monster.devils.statblock:devil-jurist
scdc:
  - 1.1.1:2.38.1:06
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: '120'
type: monster/devils/statblock
---

###### Devil Jurist

|     Devil, Infernal      |           -           |       Level 5        |     Elite Artillery     |         EV 28          |
| :----------------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|     **1M**<br/> Size     |   **6**<br/> Speed    | **120**<br/> Stamina |  **0**<br/> Stability   | **7**<br/> Free Strike |
| **Fire 5**<br/> Immunity | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|    **+0**<br/> Might     |  **+2**<br/> Agility  |  **+1**<br/> Reason  |  **+1**<br/> Intuition  |  **+3**<br/> Presence  |

<!-- -->
> ⭐️ **Hellfire**
>
> Fire damage dealt by the jurist ignores damage immunity.

<!-- -->
> 🏹 **Fire and Brimstone (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Ranged 12**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 fire damage
> - **12-16:** 15 fire damage; A < 2 burning (save ends)
> - **17+:** 18 fire damage; A < 3 burning (save ends)
>
> **Effect:** A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.
>
> **1+ Malice:** The jurist can target one additional creature or object for each Malice spent.

<!-- -->
> ❇️ **Dismissal with Prejudice**
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 2 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3**
>
> - **≤11:** 6 damage; slide 1
> - **12-16:** 10 damage; slide 3
> - **17+:** 12 damage; slide 5
>
> **Effect:** If the target has M < 2, the forced distance movement gains a +3 bonus.

<!-- -->
> 🏹 **Ashes to Ashes**
>
> | **Magic, Ranged** |        **Maneuver** |
> | ----------------- | ------------------: |
> | **📏 Ranged 12**  | **🎯 One creature** |
>
> **Effect:** If the target is burning (see Fire and Brimstone), they take 6 fire damage.

<!-- -->
> ❗️ **Devilish Charm (2 Malice)**
>
> | **Magic, Ranged** |           **Triggered action** |
> | ----------------- | -----------------------------: |
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature targets the jurist with a strike.
>
> **Effect:** The target makes a Presence test.
>
> - **≤11:** The jurist chooses a new target for the strike.
> - **12-16:** The jurist halves the triggering damage.
> - **17+:** The target takes a bane on the strike.

<!-- -->
> ⭐️ **True Name**
>
> If a creature within 10 squares speaks the jurist's true name, the jurist loses their fire immunity, any nondamaging effects of their signature ability, and their Devilish Charm ability until the end of the encounter.

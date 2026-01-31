---
agility: 2
ancestry:
  - Bugbear
  - Fey
  - Goblin
  - Humanoid
ev: '16'
file_basename: Bugbear Sneak
file_dpath: Monsters/Bugbears/Statblocks
free_strike: 5
intuition: 0
item_id: bugbear-sneak
item_index: '01'
item_name: Bugbear Sneak
level: 2
might: 2
presence: 0
reason: 0
roles:
  - Elite Ambusher
scc:
  - mcdm.monsters.v1:monster.bugbears.statblock:bugbear-sneak
scdc:
  - 1.1.1:2.35.1:01
size: 1L
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: '80'
type: monster/bugbears/statblock
---

###### Bugbear Sneak

| Bugbear, Fey, Goblin, Humanoid |          -          |       Level 2       |     Elite Ambusher      |         EV 16          |
| :----------------------------: | :-----------------: | :-----------------: | :---------------------: | :--------------------: |
|        **1L**<br/> Size        |  **7**<br/> Speed   | **80**<br/> Stamina |  **0**<br/> Stability   | **5**<br/> Free Strike |
|      **-**<br/> Immunity       | **-**<br/> Movement |          -          | **-**<br/> With Captain |  **-**<br/> Weakness   |
|       **+2**<br/> Might        | **+2**<br/> Agility | **+0**<br/> Reason  |  **+0**<br/> Intuition  |  **+0**<br/> Presence  |

<!-- -->
> 🗡 **Sucker Punch (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 8 damage; A < 1 grabbed
> - **12-16:** 13 damage; A < 2 grabbed
> - **17+:** 16 damage; grabbed
>
> **Effect:** The target can't use triggered actions until the start of the next round. Additionally, if the sneak started their turn hidden from the target, this ability deals an extra 4 damage.

<!-- -->
> ❇️ **Shadow Cloak (3 Malice)**
>
> | **Area**       |               **Main action** |
> | -------------- | ----------------------------: |
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 2 damage; I < 0 the sneak has concealment from the target (save ends)
> - **12-16:** 3 damage; I < 1 the sneak has concealment from the target (save ends)
> - **17+:** 4 damage; I < 2 the sneak has concealment from the target (save ends)
>
> **Effect:** The sneak shifts up to their speed and can attempt to hide.

<!-- -->
> 🏹 **Carving Dagger**
>
> | **Ranged, Strike, Weapon** |                 **Main action** |
> | -------------------------- | ------------------------------: |
> | **📏 Ranged 8**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 7 damage; M < 0 bleeding (save ends)
> - **12-16:** 11 damage; M < 1 bleeding (save ends)
> - **17+:** 14 damage; M < 2 bleeding (save ends)
>
> **Effect:** While bleeding this way, the target can't hide from the sneak or their allies.

<!-- -->
> 🗡 **Throw**
>
> | **Melee, Strike** |                  **Maneuver** |
> | ----------------- | ----------------------------: |
> | **📏 Melee 1**    | **🎯 One creature or object** |
>
> **Special:** The target must be grabbed by the sneak.
>
> **Effect:** The target is vertical pushed up to 4 squares. An ally doesn't take damage from being force moved this way.

<!-- -->
> ❗️ **Catcher**
>
> | **Melee**      |                **Free triggered action** |
> | -------------- | ---------------------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature or object** |
>
> **Trigger:** A size 1 creature or object is force moved within distance, or a size 1 ally willingly moves within distance.
>
> **Effect:** The target is grabbed by the sneak.

<!-- -->
> ❗️ **Clever Trick (1 Malice)**
>
> | **-**          | **Triggered action** |
> | -------------- | -------------------: |
> | **📏 Special** |     **🎯 One enemy** |
>
> **Trigger:** The sneak is targeted by a strike.
>
> **Effect:** The sneak chooses one enemy within distance of the strike to become the target of the strike.

---
agility: 3
ancestry:
  - Beast
  - Manticore
ev: '72'
file_basename: Manticore
file_dpath: Monsters/Manticores/Statblocks
free_strike: 6
intuition: 0
item_id: manticore
item_index: '01'
item_name: Manticore
level: 4
might: 4
presence: -1
reason: 0
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.manticores.statblock:manticore
scdc:
  - 1.1.1:2.47.1:01
size: '2'
source: mcdm.monsters.v1
speed: 10
stability: 2
stamina: '350'
type: monster/manticores/statblock
---

###### Manticore

|  Beast, Manticore   |           -           |       Level 4        |          Solo           |         EV 72          |
| :-----------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|   **2**<br/> Size   |   **10**<br/> Speed   | **350**<br/> Stamina |  **2**<br/> Stability   | **6**<br/> Free Strike |
| **-**<br/> Immunity | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+4**<br/> Might  |  **+3**<br/> Agility  |  **0**<br/> Reason   |  **0**<br/> Intuition   |  **-1**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the manticore can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The manticore can take two turns each round. They can't take turns consecutively.

<!-- -->
> ⭐️ **Agile Predator**
>
> Whenever the manticore deals damage to a creature, they don't provoke opportunity attacks from that creature during that turn.

<!-- -->
> 🗡 **Carnivorous Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 12 damage; A < 2 bleeding (save ends)
> - **12-16:** 17 damage; A < 3 bleeding (save ends)
> - **17+:** 21 damage; A < 4 bleeding (save ends)
>
> **Effect:** If the target is frightened, this ability gains an edge.

<!-- -->
> 🏹 **Tail Spike**
>
> | **Ranged, Strike, Weapon** |                 **Main action** |
> | -------------------------- | ------------------------------: |
> | **📏 Ranged 10**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 damage; M < 2 4 poison damage
> - **12-16:** 11 damage; M < 3 4 poison damage, weakened (save ends)
> - **17+:** 14 damage; M < 4 8 poison damage, weakened (save ends)
>
> **1 Malice:** While weakened this way, a target takes 1d6 poison damage at the start of each of their turns.

<!-- -->
> 🗡 **Harrying Claws**
>
> | **Melee, Strike, Weapon** |                    **Maneuver** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** Slide 1; A < 2 3 damage
> - **12-16:** Slide 2; A < 3 5 damage
> - **17+:** Slide 4; A < 4 7 damage

<!-- -->
> ❗️ **Reflexive Instinct (2 Malice)**
>
> | **Ranged**       |           **Triggered action** |
> | ---------------- | -----------------------------: |
> | **📏 Ranged 10** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the manticore.
>
> **Effect:** The manticore shifts up to 5 squares into the air, then can use Tail Spike against the target.

<!-- -->
> ☠️ **Trumpeting Howl (Villain Action 1)**
>
> | **Area, Magic** |                            **-** |
> | --------------- | -------------------------------: |
> | **📏 5 burst**  | **🎯 Each creature in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** Frightened (EoT); if the target has I < 2 they are instead frightened (save ends)
> - **12-16:** Frightened (EoT); if the target has I < 3 they are instead frightened (save ends)
> - **17+:** Frightened (EoT); if the target has I < 4 they are instead dazed (save ends)

<!-- -->
> ☠️ **Cornered Predator (Villain Action 2)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The manticore shifts up to their speed, then can use Tail Spike against each enemy within distance of that ability.

<!-- -->
> ☠️ **Debilitating Poison (Villain Action 3)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The manticore sours their poison with enmity. Until the end of the encounter, the manticore has a double edge on power rolls against weakened creatures. Additionally, any creature weakened by the manticore's Tail Spike ability has their speed halved and takes an extra 3 poison damage at the start of each of their turns.

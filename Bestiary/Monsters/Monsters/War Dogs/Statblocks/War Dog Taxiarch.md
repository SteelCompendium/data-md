---
agility: 3
ancestry:
  - Humanoid
  - Soulless
  - War Dog
ev: '44'
file_basename: War Dog Taxiarch
file_dpath: Monsters/War Dogs/Statblocks
free_strike: 9
intuition: 4
item_id: war-dog-taxiarch
item_index: '24'
item_name: War Dog Taxiarch
level: 9
might: 1
presence: 3
reason: 5
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.war-dogs.statblock:war-dog-taxiarch
scdc:
  - 1.1.1:2.51.1:24
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: '240'
type: monster/war-dogs/statblock
---

###### War Dog Taxiarch

| Humanoid, Soulless, War Dog |             -              |       Level 9        |         Leader          |         EV 44          |
| :-------------------------: | :------------------------: | :------------------: | :---------------------: | :--------------------: |
|      **1M**<br/> Size       |      **7**<br/> Speed      | **240**<br/> Stamina |  **1**<br/> Stability   | **9**<br/> Free Strike |
|     **-**<br/> Immunity     | **Teleport**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|      **+1**<br/> Might      |    **+3**<br/> Agility     |  **+5**<br/> Reason  |  **+4**<br/> Intuition  |  **+3**<br/> Presence  |

<!-- -->
> 🏹 **Stunning Surge (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 14 lightning damage; the lightning spreads 1 square; I < 3 dazed (save ends)
> - **12-16:** 19 lightning damage; the lightning spreads 2 squares; I < 4 dazed (save ends)
> - **17+:** 23 lightning damage; the lightning spreads 3 squares; I < 5 dazed (save ends)
>
> **Effect:** The spread is the distance the charge arcs from a target to nearby enemies. Each enemy within spread takes 5 lightning damage.
>
> **2 Malice:** The lighting spread increases by 2 squares. Additionally, any creature who takes lightning damage from this ability and who has M < 4 is slowed until the end of their next turn.

<!-- -->
> 🔳 **Overcharge (2 Malice)**
>
> | **Area, Magic, Ranged** |                    **Maneuver** |
> | ----------------------- | ------------------------------: |
> | **📏 4 cube within 10** | **🎯 Each war dog in the area** |
>
> **Effect:** Each target shifts up to their speed and can make a free strike that deals an extra 5 lightning damage.

<!-- -->
> ❗️ **Thunderstruck**
>
> | **Magic, Melee** |        **Triggered action** |
> | ---------------- | --------------------------: |
> | **📏 Melee 1**   | **🎯 The triggering enemy** |
>
> **Trigger:** An enemy within distance deals damage to the taxiarch.
>
> **Effect:** After the ability is resolved, the target is teleported up to 5 squares and is thunderstruck (save ends). A thunderstruck creature has lightning weakness 5, and the taxiarch gains an edge on power rolls against them.

<!-- -->
> ⭐️ **End Effect**
>
> At the end of each of their turns, the taxiarch can take 15 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

<!-- -->
> ☠️ **Magnetic Trickery (Villain Action 1)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Slide 5, and if the the target has M < 4, they fall prone.

<!-- -->
> ☠️ **Conductor of Combat (Villain Action 2)**
>
> | **Area, Magic** |                           **-** |
> | --------------- | ------------------------------: |
> | **📏 5 burst**  | **🎯 Each war dog in the area** |
>
> **Effect:** Each target shifts up to their speed, then can make a free strike or use a maneuver.

<!-- -->
> ☠️ **Unlimited Power! (Villain Action 3)**
>
> | **Area, Magic** |                            **-** |
> | --------------- | -------------------------------: |
> | **📏 3 burst**  | **🎯 Each creature in the area** |
>
> **Effect:** Each target makes an Agility test.
>
> - **≤11:** 18 lightning damage; the target is thunderstruck (save ends)
> - **12-16:** 14 lightning damage; the target is thunderstruck (EoT)
> - **17+:** 9 lightning damage
>
> See Thunderstruck. Additionally, until the end of the encounter, any enemy who moves within 3 squares of the taxiarch for the first time in a round or starts their turn there takes 3 lightning damage.

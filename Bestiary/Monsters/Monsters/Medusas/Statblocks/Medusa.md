---
agility: 4
ancestry:
  - Accursed
  - Humanoid
  - Medusa
ev: '84'
file_basename: Medusa
file_dpath: Monsters/Medusas/Statblocks
free_strike: 8
intuition: 0
item_id: medusa
item_index: '01'
item_name: Medusa
level: 5
might: 2
presence: 0
reason: 0
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.medusas.statblock:medusa
scdc:
  - 1.1.1:2.30.1:01
size: 1M
source: mcdm.monsters.v1
speed: 10
stability: 5
stamina: '420'
type: monster/medusas/statblock
---

###### Medusa

| Accursed, Humanoid, Medusa |          -          |       Level 5        |          Solo           |         EV 84          |
| :------------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|      **1M**<br/> Size      |  **10**<br/> Speed  | **420**<br/> Stamina |  **5**<br/> Stability   | **8**<br/> Free Strike |
|    **-**<br/> Immunity     | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|     **+2**<br/> Might      | **+4**<br/> Agility |  **0**<br/> Reason   |  **0**<br/> Intuition   |  **0**<br/> Presence   |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the medusa can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The medusa can take two turns each round. They can't take turns consecutively.

<!-- -->
> 🗡 **Snake Bites (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; M < 2 slowed (save ends)
> - **12-16:** 16 damage; M < 3 slowed (save ends)
> - **17+:** 19 damage; M < 4 slowed (save ends)

<!-- -->
> 🏹 **Damning Gaze (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; push 3
> - **12-16:** 16 damage; push 5
> - **17+:** 19 damage; push 7
>
> **3 Malice:** The medusa targets two additional creatures or objects.

<!-- -->
> ❇️ **Petrify (5 Malice)**
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** M < 2 restrained (save ends)
> - **12-16:** M < 3 restrained (save ends)
> - **17+:** Slowed (save ends); or if M < 4 restrained (save ends)
>
> **Effect:** A target with cover reduces the potency by 1, while a slowed target increases the potency by 1. A target restrained this way magically begins to turn to stone, and a target who ends two consecutive turns restrained this way is petrified.

<!-- -->
> 👤 **Nimble Escape**
>
> | **-**       | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The medusa shifts up to 3 squares and can attempt to hide even if observed.

<!-- -->
> ❗️ **Venomous Spit (2 Malice)**
>
> | **Melee**      |           **Triggered action** |
> | -------------- | -----------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the medusa.
>
> **Power Roll + 4:**
>
> - **≤11:** 13 acid damage
> - **12-16:** 18 acid damage
> - **17+:** 22 acid damage

<!-- -->
> ⭐️ **Cunning Edge**
>
> The medusa gains an edge on power rolls against any creature who is restrained or slowed by Petrify.

<!-- -->
> ⭐️ **Many Peering Eyes**
>
> The medusa can't be flanked.

<!-- -->
> ☠️ **Mass Petrify (Villain Action 1)**
>
> | **Magic, Ranged** |             **-** |
> | ----------------- | ----------------: |
> | **📏 Ranged 50**  | **🎯 Each enemy** |
>
> **Effect:** The medusa can use Petrify against each target without spending Malice. A target who doesn't have cover increases the potency by 1.

<!-- -->
> ☠️ **Serpent Wings (Villain Action 2)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The medusa temporarily manifests wings and flies up to their speed without provoking opportunity attacks. During or after this movement, they can use Snake Bites and Damning Gaze once each.

<!-- -->
> ☠️ **Stone Puppets (Villain Action 3)**
>
> | **Area, Magic** |          **-** |
> | --------------- | -------------: |
> | **📏 10 burst** | **🎯 Special** |
>
> **Power Roll + 4:**
>
> - **≤11:** 8 acid damage; P < 3 weakened (save ends)
> - **12-16:** 13 acid damage; P < 4 weakened (save ends)
> - **17+:** 17 acid damage; P < 5 weakened (save ends)
>
> **Effect:** As a free triggered action, each stone statue and creature restrained or slowed by Petrify within distance moves up to their speed and uses a signature ability that gains an edge, targeting an enemy of the medusa's choice. A stone statue without its own statistics has speed 5 and uses the medusa's free strike.

---
agility: 4
ancestry:
  - Dragon
  - Elemental
ev: '120'
file_basename: Omen Dragon
file_dpath: Monsters/Dragons/Statblocks
free_strike: 9
intuition: 3
item_id: omen-dragon
item_index: '01'
item_name: Omen Dragon
level: 8
might: 3
presence: 5
reason: 2
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.dragons.statblock:omen-dragon
scdc:
  - 1.1.1:2.45.1:01
size: '5'
source: mcdm.monsters.v1
speed: 10
stability: 6
stamina: '550'
type: monster/dragons/statblock
---

###### Omen Dragon

|       Dragon, Elemental        |           -           |       Level 8        |          Solo           |         EV 120         |
| :----------------------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|        **5**<br/> Size         |   **10**<br/> Speed   | **550**<br/> Stamina |  **6**<br/> Stability   | **9**<br/> Free Strike |
| **Corruption 6**<br/> Immunity | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|       **+3**<br/> Might        |  **+4**<br/> Agility  |  **+2**<br/> Reason  |  **+3**<br/> Intuition  |  **+5**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the dragon can take 15 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

<!-- -->
> ⭐️ **Deathcount**
>
> Several of the dragon's abilities impose a Deathcount on a target. At the end of every turn, a creature with a Deathcount who is within the area of the dragon's Stagnant Wyrmscale Aura has that Deathcount reduced by 1. When a creature's Deathcount hits 0, they die. If multiple Deathcounts are imposed on a creature, they don't stack. Only the lowest Deathcount takes effect. All Deathcounts are lost when the dragon is reduced to 0 Stamina.

<!-- -->
> ❇️ **Stagnant Wyrmscale Aura**
>
> The dragon's scales create a 4 aura of supernatural stagnancy around them. The area is difficult terrain for enemies, and no creature except the omen dragon can regain Stamina while in the area. Any creature dragonsealed by the omen dragon who starts their turn in the dragon's aura and doesn't have a Deathcount gains a Deathcount of 12.

<!-- -->
> 🔳 **Corroding Breath (Signature Ability)**
>
> | **Area, Magic, Ranged** |                             **Main action** |
> | ----------------------- | ------------------------------------------: |
> | **📏 5 cube within 10** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target makes an **Agility test**.
>
> - **≤11:** 18 corruption damage; the target is dragonsealed (save ends)
> - **12-16:** 14 corruption damage; the target is dragonsealed (save ends)
> - **17+:** 9 corruption damage
>
> Only creatures with souls can be dragonsealed by the omen dragon. A dragonsealed creature appears ghastly and pale, their Presence score is treated as 1 lower for the purpose of resisting potencies, and they can't treat other creatures as allies.

<!-- -->
> 🗡 **Barbed Tail Swing**
>
> | **Charge, Melee, Strike, Weapon** |                 **Main action** |
> | --------------------------------- | ------------------------------: |
> | **📏 Melee 4**                    | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 14 damage; M < 3 bleeding (save ends)
> - **12-16:** 19 damage; M < 4 bleeding (save ends)
> - **17+:** 23 damage; M < 5 bleeding (save ends)
>
> **3 Malice:** The potency increases by 2, and each target is also pulled up to 5 squares.

<!-- -->
> ⭐️ **Death or Victory**
>
> Once per turn, the dragon chooses one creature with a Deathcount within line of effect. That creature can choose to take 1d6 damage and lose a recovery to increase their Deathcount by 5.

<!-- -->
> ❇️ **Detonation (5 Malice)**
>
> | **Area**        |                  **Maneuver** |
> | --------------- | ----------------------------: |
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. Each target takes 9 corruption damage, and the omen dragon regains Stamina equal to half the total damage dealt. The target then loses their dragonseal.

<!-- -->
> ❗️ **Don't Turn Away (1 Malice)**
>
> | **-**       | **Free triggered action** |
> | ----------- | ------------------------: |
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** A creature leaves the area of the dragon's Stagnant Wyrmscale Aura trait.
>
> **Effect:** The dragon shifts up to their speed, and the Deathcount of each dragonsealed creature who comes adjacent to the dragon during this shift is reduced by 1.

<!-- -->
> ❗️ **Repent! (2 Malice)**
>
> | **Ranged**      |      **Free triggered action** |
> | --------------- | -----------------------------: |
> | **📏 Ranged 5** | **🎯 The triggering creature** |
>
> **Trigger:** A dragonsealed creature within distance deals damage to the dragon.
>
> **Effect:** The target must choose between making a free strike against themself or gaining a Deathcount of 5.

<!-- -->
> ☠️ **What You Deserve (Villain Action 1)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** Pull 1; the target has a Deathcount of 10
> - **12-16:** Pull 2; the target has a Deathcount of 8
> - **17+:** Pull 3; the target has a Deathcount of 6
>
> **Effect:** Each target receives a premonition of their imminent death.

<!-- -->
> ☠️ **Souls of the Broken (Villain Action 2)**
>
> | **Magic, Ranged, Strike** |                 **-** |
> | ------------------------- | --------------------: |
> | **📏 Ranged 10**          | **🎯 Five creatures** |
>
> **Effect:** The dragon spits fragments of souls to attempt to possess the targets, making a separate power roll for each target.
>
> **Power Roll + 5:**
>
> - **≤11:** P < 5 frightened (save ends)
> - **12-16:** P < 5 the target moves up to their speed toward the dragon
> - **17+:** P < 5 the target makes a free strike against the nearest ally

<!-- -->
> ☠️ **So Long and Goodnight (Villain Action 3)**
>
> | **Area, Magic** |                            **-** |
> | --------------- | -------------------------------: |
> | **📏 6 burst**  | **🎯 Each creature in the area** |
>
> **Effect:** Each target must be dragonsealed. The dragon's eyes glow with unequalled malevolence, and any target who has a Deathcount has that Deathcount reduced to 1.

###### Omen Dragon Malice (Malice Features)

At the start of an omen dragon's turn, you can spend Malice to activate one of the following features.

<!-- -->
> ⭐️ **Black Skies (3 Malice)**
>
> The dragon expands their wings to create a shroud of shadow. Until the start of the dragon's next turn, any strike made against them takes a bane.

<!-- -->
> ❇️ **Rise and Fall (5 Malice)**
>
> The dragon flies up to 10 squares and carries fated souls with them. Each creature in the area of the dragon's Stagnant Wyrmscale Aura trait makes a **Presence test**.
>
> - **≤11:** Vertical pull 10
> - **12-16:** Vertical pull 6
> - **17+:** Vertical pull 4

<!-- -->
> ☠️ **Solo Action (5 Malice)**
>
> The dragon takes an additional main action on their turn. They can use this feature even if they are dazed.

<!-- -->
> 🌀 **Burn It Right Down (10 Malice)**
>
> Each edge of the encounter map burns with intangible purple flames until the end of the encounter. The flames expand by 1 square at the end of every turn. Any enemy takes 5 corruption damage for each square of flames they enter.

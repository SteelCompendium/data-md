---
agility: -1
ancestry:
  - Dragon
  - Elemental
ev: '96'
file_basename: Crucible Dragon
file_dpath: Monsters/Dragons/Statblocks
free_strike: 7
intuition: 3
item_id: crucible-dragon
item_index: '03'
item_name: Crucible Dragon
level: 6
might: 4
presence: 2
reason: 3
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.dragons.statblock:crucible-dragon
scdc:
  - 1.1.1:2.46.1:03
size: '4'
source: mcdm.monsters.v1
speed: 8
stability: 6
stamina: '450'
type: monster/dragons/statblock
---

###### Crucible Dragon

|    Dragon, Elemental     |          -          |       Level 6        |          Solo           |         EV 96          |
| :----------------------: | :-----------------: | :------------------: | :---------------------: | :--------------------: |
|     **4**<br/> Size      |  **8**<br/> Speed   | **450**<br/> Stamina |  **6**<br/> Stability   | **7**<br/> Free Strike |
| **Fire 6**<br/> Immunity | **-**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|    **+4**<br/> Might     | **-1**<br/> Agility |  **+3**<br/> Reason  |  **+3**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

<!-- -->
> ❇️ **Magnetized Wyrmscale Aura**
>
> The dragon's scales create a 3 aura of magnetism around them that affects large masses of metal. Any creature who enters the area for the first time in a round or starts their turn there while wearing metal or while slagged (see Slag Spew) is pulled up to 2 squares toward the dragon. A creature pulled this way who has M < 3 is unable to willingly move away from the dragon.

<!-- -->
> 🔳 **Slag Spew (Signature Ability)**
>
> | **Area, Magic**             |                             **Main action** |
> | --------------------------- | ------------------------------------------: |
> | **📏 10 x 2 line within 1** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target makes an Agility test.
>
> - **≤11:** 13 fire damage; the target is slagged (save ends)
> - **12-16:** 10 fire damage; the target is slagged (save ends)
> - **17+:** 6 fire damage
>
> A slagged target is coated in molten metal and takes 2d6 fire damage at the start of each of their turns. If a slagged target has M < 3 they are restrained (save ends) whenever they take cold damage.

<!-- -->
> 🗡 **Forge Hammer Tail Slam**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; M < 2 prone
> - **12-16:** 17 damage; M < 3 prone
> - **17+:** 20 damage; M < 4 prone
>
> **Effect:** The dragon can make a free strike against each slagged target knocked prone this way.
>
> **1 Malice:** The strike deals 1d6 cold damage.

<!-- -->
> ⭐️ **Heat Buffer**
>
> Once per round while the dragon is flying using their Thermodynamic Flight ability, they give off a blast of steam to extend the duration of their flight until the end of the next round. Each creature in a 4 cube within 1 underneath the dragon when they use this ability takes 7 fire damage.

<!-- -->
> ❇️ **Thermodynamic Flight (1 Malice)**
>
> | **Area**       |                  **Maneuver** |
> | -------------- | ----------------------------: |
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** The dragon expels blistering steam, dealing 7 fire damage to each target in the area. The dragon then shifts up to their speed vertically and can fly until the end of the round.

<!-- -->
> ❗️ **Hammer and Anvil (1 Malice)**
>
> | **-**       | **Free triggered action** |
> | ----------- | ------------------------: |
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** While flying, the dragon starts their turn or moves.
>
> **Effect:** The dragon drops to the ground and uses Forge Hammer Tail Slam, which deals an extra 4 damage for each square they descended.

<!-- -->
> ❗️ **Polarize Aura (1 Malice)**
>
> | **Area, Magic** |                        **Triggered action** |
> | --------------- | ------------------------------------------: |
> | **📏 3 burst**  | **🎯 Each creature and object in the area** |
>
> **Trigger:** The dragon is targeted by two melee strikes in the current turn.
>
> **Special:** The target must be size 2 or smaller.
>
> **Power Roll + 4:**
>
> - **≤11:** Push 5
> - **12-16:** Push 7
> - **17+:** Push 10, ignoring stability

<!-- -->
> ☠️ **Heart of the Forge (Villain Action 1)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 6 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 4 fire damage; I < 2 frightened (save ends)
> - **12-16:** 6 fire damage; I < 3 frightened (save ends)
> - **17+:** 8 fire damage; I < 4 frightened (save ends)

<!-- -->
> ☠️ **Subdermal Shielding (Villain Action 2)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** Shields embedded under the dragon's scales emerge, and the dragon gains damage immunity 6 at the start of each round until the end of the encounter. If the dragon takes any damage, they lose this immunity until the end of the current round.

<!-- -->
> ☠️ **Polarity Chaos (Villain Action 3)**
>
> | **-**           |                                       **-** |
> | --------------- | ------------------------------------------: |
> | **📏 10 burst** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target makes a **Might test**.
>
> - **≤11:** 16 damage; pull 10 or push 10
> - **12-16:** 13 damage; pull 8 or push 8
> - **17+:** 7 damage; pull 5 or push 5.

###### Crucible Dragon Malice (Malice Features)

At the start of a crucible dragon's turn, you can spend Malice to activate one of the following features.

<!-- -->
> 🔳 **Swordfall (3 Malice)**
>
> While the dragon is flying, they shape themself into a blade and fall. Each creature and object in the dragon's space when they hit the ground and in a 6 x 4 line within 1 square of the dragon takes 7 damage. A creature who takes this damage and has A < 4 takes 4 extra damage per square the dragon fell and is restrained (save ends). A creature not restrained this way can move into the nearest unoccupied space.

<!-- -->
> 🔳 **Shower of Blades (5 Malice)**
>
> The dragon shakes loose a cloud of shattered weapons in a 6 x 4 line within 1 square of them. Each creature and object in the area makes an **Agility test**.
>
> - **≤11:** 16 damage; bleeding (save ends)
> - **12-16:** 13 damage; bleeding (EoT)
> - **17+:** 7 damage

<!-- -->
> ☠️ **Solo Action (5 Malice)**
>
> The dragon takes an additional main action on their turn. They can use this feature even if they are dazed.

<!-- -->
> 🌀 **Meltdown (7 Malice)**
>
> The dragon superheats the ground across the encounter map until the end of the round. Any enemy who starts their turn on the ground is slagged as if affected by the dragon's Slag Spew ability.

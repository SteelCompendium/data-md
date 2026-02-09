---
agility: 5
ancestry:
  - Dragon
  - Elemental
ev: '144'
file_basename: Meteor Dragon
file_dpath: Monsters/Dragons/Statblocks
free_strike: 10
intuition: 3
item_id: meteor-dragon
item_index: '04'
item_name: Meteor Dragon
level: 10
might: 5
presence: 5
reason: 3
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.dragons.statblock:meteor-dragon
scdc:
  - 1.1.1:2.46.1:04
size: '3'
source: mcdm.monsters.v1
speed: 15
stability: 6
stamina: '650'
type: monster/dragons/statblock
---

###### Meteor Dragon

|  Dragon, Elemental  |           -           |       Level 10       |          Solo           |         EV 144          |
| :-----------------: | :-------------------: | :------------------: | :---------------------: | :---------------------: |
|   **3**<br/> Size   |   **15**<br/> Speed   | **650**<br/> Stamina |  **6**<br/> Stability   | **10**<br/> Free Strike |
| **-**<br/> Immunity | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |   **-**<br/> Weakness   |
|  **+5**<br/> Might  |  **+5**<br/> Agility  |  **+3**<br/> Reason  |  **+3**<br/> Intuition  |  **+5**<br/> Presence   |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the dragon can take 20 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

<!-- -->
> ❇️ **Voidshroud Wyrmscale Aura**
>
> The dragon's scales create a 1 aura of void space around them. Any enemy who starts their turn in the area takes 10 cold damage and is suffocating. Each time the dragon takes damage, the area of the aura increases by 1 (to a maximum of 5), and they deal an extra 5 damage the next time they use an ability that deals rolled damage.

<!-- -->
> 🔳 **Gravity Well (Signature Ability)**
>
> | **Area, Magic, Ranged** |                             **Main action** |
> | ----------------------- | ------------------------------------------: |
> | **📏 4 cube within 10** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target makes a **Might test**.
>
> - **≤11:** 20 sonic damage; the target is dragonsealed (save ends)
> - **12-16:** 16 sonic damage; the target is dragonsealed (save ends)
> - **17+:** 10 sonic damage
>
> A dragonsealed target emits a golden aura, and takes 2 damage per square moved when falling or when force moved into an obstacle.

<!-- -->
> ⚔️ **Cosmic Tail Ray**
>
> | **Magic, Melee, Ranged, Strike** |                 **Main action** |
> | -------------------------------- | ------------------------------: |
> | **📏 Melee 2 or ranged 15**      | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 holy damage; A < 4 weakened (save ends)
> - **12-16:** 21 holy damage; A < 5 weakened (save ends)
> - **17+:** 25 holy damage; A < 6 weakened (save ends)
>
> **Effect:** If a target made weakened this way is already weakened, they are instead dazed until the end of their next turn.

<!-- -->
> ⭐️ **Crescent Claws**
>
> Once per turn, the dragon chooses a target within 3 squares. The dragon can make a free strike against the target, and ignores banes when using abilities against the target until the start of their next turn.

<!-- -->
> ❇️ **Investiture of Gravity (5 Malice)**
>
> | **Area, Magic** |                  **Maneuver** |
> | --------------- | ----------------------------: |
> | **📏 15 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. The dragon chooses a direction and vertical slides each target 10 squares in that direction, ignoring stability. A target who strikes an obstacle takes damage as if they had fallen the forced movement distance.

<!-- -->
> ❗️ **Field Collapse**
>
> | **-**       | **Free triggered action** |
> | ----------- | ------------------------: |
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** The dragon takes damage from an ability while the area of their Voidshroud Wyrmscale Aura is 2 or more.
>
> **Effect:** The dragon halves the damage. Each enemy and object in the area of the dragon's Voidshroud Wyrmscale Aura trait takes 5 sonic damage and is pulled up to 5 squares toward the dragon. The area of the wyrmscale aura then resets to 1.

<!-- -->
> ❗️ **A Hero Faces the Void (2 Malice)**
>
> | **Magic, Ranged** |      **Free triggered action** |
> | ----------------- | -----------------------------: |
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance spends their Heroic Resource to use an ability.
>
> **Power Roll + 5:**
>
> - **≤11:** 10 psychic damage; P < 4 frightened (save ends)
> - **12-16:** 16 psychic damage; P < 5 frightened (save ends)
> - **17+:** 20 psychic damage; P < 6 frightened (save ends)
>
> **Effect:** While frightened this way, the target can't use the triggering ability.

<!-- -->
> ☠️ **Impactful Arrival (Villain Action 1)**
>
> | **Area, Magic**     |                                       **-** |
> | ------------------- | ------------------------------------------: |
> | **📏 1-mile burst** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target takes 30 fire damage, and if they have M < 5, they are knocked prone.
>
> **Special:** The dragon can use this ability before the encounter begins.

<!-- -->
> ☠️ **Burning Aurora (Villain Action 2)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** Until the end of the encounter, each enemy who is dragonsealed and weakened and who the dragon has line of effect to loses 1 of their Heroic Resource at the start of each of their turns (to a minimum of 0). The dragon then uses their Cosmic Tail Ray ability with a double edge, targeting four creatures or objects.

<!-- -->
> ☠️ **Voidlight Breath (Villain Action 3)**
>
> | **Area, Magic**            |                                    **-** |
> | -------------------------- | ---------------------------------------: |
> | **📏 ∞ x 3 line within 1** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes an Agility test.
>
> - **≤11:** 25 damage; I < 6 the target is annihilated
> - **12-16:** 21 damage; I < 5 the target is annihilated
> - **17+:** 15 damage; I < 4 the target is annihilated
>
> An annihilated target must make the test again, decreasing the potency for themself by 2 each time they are annihilated. A creature reduced to 0 Stamina by this dies and their soul is destroyed.

###### Meteor Dragon Malice (Malice Features)

At the start of a meteor dragon's turn, you can spend Malice to activate one of the following features.

<!-- -->
> ⭐️ **Liftoff (3 Malice)**
>
> The next time the dragon uses their Crescent Claws ability, they can also slide the target up to 5 squares. If the target is dragonsealed, the dragon can vertical slide them instead.

<!-- -->
> ☠️ **Solo Action (5 Malice)**
>
> The dragon takes an additional main action on their turn. They can use this feature even if they are dazed.

<!-- -->
> 🔳 **Starfall (5 Malice)**
>
> The dragon drops stars into five 2 cubes anywhere on the encounter map. The area is difficult terrain, and each creature and object in the area when it appears makes an **Agility test**.
>
> - **≤11:** 20 holy damage; slowed (save ends), prone
> - **12-16:** 16 holy damage; slowed (save ends)
> - **17+:** 10 holy damage

<!-- -->
> ☠️ **Event Horizon (10 Malice)**
>
> A black hole manifests as a 1 cube within 20 squares of the dragon in an unoccupied space. Each creature who has M < 5 and each object of size 3 or smaller is vertical pulled 2 squares toward the area at the start of each round, ignoring stability. Any creature who starts their turn in the area or any object in the area at the end of the round suffers the effect of the dragon's Voidlight Breath ability, and the black hole disappears.

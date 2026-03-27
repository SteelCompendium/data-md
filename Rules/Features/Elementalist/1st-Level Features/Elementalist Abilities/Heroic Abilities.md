---
action_type: feature
class: elementalist
feature_type: subtrait
file_basename: Heroic Abilities
file_dpath: Elementalist/1st-Level Features/Elementalist Abilities
item_id: heroic-abilities
item_index: '10'
item_name: Heroic Abilities
level: 1
scc:
  - mcdm.heroes.v1:feature.subtrait.elementalist.1st-level-feature:heroic-abilities
scdc:
  - 1.1.1:11.2.9.7:10
source: mcdm.heroes.v1
type: feature/subtrait/elementalist/1st-level-feature
---

##### Heroic Abilities

You channel a variety of heroic abilities, all of them fueled by your essence.

###### 3-Essence Ability

Choose one heroic ability from the following options, each of which costs 3 essence to use. (*Quick Build:* The Flesh, a Crucible.)

<!-- -->
> ###### Behold the Mystery (3 Essence)
>
> *You open a rift into the void to harry your foes.*
>
> | **Area, Magic, Ranged, Void** |               **Main action** |
> | ----------------------------- | ----------------------------: |
> | **📏 3 cube within 10**       | **🎯 Each enemy in the area** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 2 psychic damage
> - **12-16:** 4 psychic damage
> - **17+:** 6 psychic damage
>
> **Persistent 1:** At the start of your turn, you can use a maneuver to use this ability again without spending essence.

<!-- -->
> ###### The Flesh, a Crucible (3 Essence)
>
> *Fire engulfs your target and continues to churn.*
>
> | **Fire, Magic, Ranged, Strike** |               **Main action** |
> | ------------------------------- | ----------------------------: |
> | **📏 Ranged 10**                | **🎯 One creature or object** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 5 + R fire damage
> - **12-16:** 8 + R fire damage
> - **17+:** 11 + R fire damage
>
> **Persistent 1:** If the target is within distance at the start of your turn, you can make the power roll again without spending essence (no action required).

<!-- -->
> ###### Invigorating Growth (3 Essence)
>
> *Mushrooms erupt from a foe, sapping their vitality to spread strengthening spores.*
>
> | **Green, Magic, Ranged, Strike** |     **Main action** |
> | -------------------------------- | ------------------: |
> | **📏 Ranged 10**                 | **🎯 One creature** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 4 + R poison damage
> - **12-16:** 7 + R poison damage
> - **17+:** 11 + R poison damage
>
> **Effect:** Mushrooms cover the target's body. While the mushrooms are on the target, you and any ally adjacent to the target gain 1 surge whenever the target takes damage. The mushrooms can be removed by the target or an adjacent creature as a main action.

<!-- -->
> ###### Ripples in the Earth (3 Essence)
>
> *Like a stone was dropped into a pond, waves in the earth radiate from you.*
>
> | **Area, Earth, Magic** |               **Main action** |
> | ---------------------- | ----------------------------: |
> | **📏 2 burst**         | **🎯 Each enemy in the area** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 3 damage
> - **12-16:** 5 damage
> - **17+:** 8 damage; M < STRONG, prone
>
> **Effect:** You must be touching the ground to use this ability. Additionally, you can choose a square of ground in the area that is unoccupied or is occupied by you or any ally. A pillar of earth rises out of the ground in that square, with a height in squares up to your Reason score. The pillar can't collide with any creatures or objects, nor can it force creatures raised by it to collide with other creatures or objects.

###### 5-Essence Ability

Choose one heroic ability from the following options, each of which costs 5 essence to use. (*Quick Build:* Conflagration.)

<!-- -->
> ###### Conflagration (5 Essence)
>
> *A storm of fire descends upon your enemies.*
>
> | **Area, Fire, Magic, Ranged** |               **Main action** |
> | ----------------------------- | ----------------------------: |
> | **📏 3 cube within 10**       | **🎯 Each enemy in the area** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 4 fire damage
> - **12-16:** 6 fire damage
> - **17+:** 10 fire damage
>
> **Persistent 2:** At the start of your turn, you can use a maneuver to use this ability again without spending essence.

<!-- -->
> ###### Instantaneous Excavation (5 Essence)
>
> *The surface of the world around you opens up to swallow foes.*
>
> | **Earth, Magic, Ranged** |   **Maneuver** |
> | ------------------------ | -------------: |
> | **📏 Ranged 10**         | **🎯 Special** |
>
> **Effect:** You open up two holes with 1-square openings that are 4 squares deep, which can be placed on any mundane surface within distance. You can place these holes next to each other to create fewer holes with wider openings. When the holes open, make a separate power roll for each creature on the ground above a hole and small enough to fall in. (You can't score a critical hit with this ability because it uses a maneuver.)
>
> **Power Roll + Reason:**
>
> - **≤11:** The target can shift 1 square from the edge of the hole to the nearest unoccupied space of their choice.
> - **12-16:** The target falls into the hole.
> - **17+:** The target falls into the hole and can't reduce the height of the fall.
>
> **Persistent 1:** At the start of your turn, you open another hole, making a power roll against each creature who could fall into the hole when it opens without spending essence.

<!-- -->
> ###### No More Than a Breeze (5 Essence)
>
> *The material substance of a creature shreds away at your command.*
>
> | **Magic, Ranged, Void** |            **Maneuver** |
> | ----------------------- | ----------------------: |
> | **📏 Ranged 10**        | **🎯 Self or one ally** |
>
> **Effect:** Until the start of your next turn, the target can move through solid matter, they ignore difficult terrain, and their movement can't provoke opportunity attacks. If the target ends their turn inside solid matter, they are forced out into the space where they entered it and this effect ends.
>
> **Persistent 1:** The effect lasts until the start of your next turn.

<!-- -->
> ###### Test of Rain (5 Essence)
>
> *You call down a rain that burns your enemies and restores your allies.*
>
> | **Area, Green, Magic, Ranged** |               **Main action** |
> | ------------------------------ | ----------------------------: |
> | **📏 3 cube within 10**        | **🎯 Each enemy in the area** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 4 acid damage
> - **12-16:** 6 acid damage
> - **17+:** 10 acid damage
>
> **Effect:** You can end one effect on yourself that is ended by a saving throw or that ends at the end of your turn. Each ally in the area also gains this benefit.

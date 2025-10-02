---
action_type: Main action
class: elementalist
distance: Ranged 10
feature_type: ability
file_basename: Summon Source of Earth
file_dpath: Abilities/Elementalist/5th-Level Features
flavor: The ground rumbles as an elemental bursts forth, ready to serve.
item_id: summon-source-of-earth
item_index: '10'
item_name: Summon Source of Earth
keywords:
  - Earth
  - Magic
  - Ranged
level: 5
scc:
  - mcdm.heroes.v1:feature.ability.elementalist.5th-level-feature:summon-source-of-earth
scdc:
  - 1.1.1:11.2.9.4:10
source: mcdm.heroes.v1
target: Special
type: feature/ability/elementalist/5th-level-feature
---

###### Summon Source of Earth

*The ground rumbles as an elemental bursts forth, ready to serve.*

| **Earth, Magic, Ranged** | **Main action** |
| ------------------------ | --------------: |
| **📏 Ranged 10**         |  **🎯 Special** |

**Effect:** A **source of earth** emerges from an unoccupied space within distance. The source takes their turn immediately after you, moving up to their speed and either taking a main action or a maneuver. The source is dismissed at the start of your next turn.

The source starts an encounter at full Stamina, but maintains their current Stamina throughout the encounter, even if they are dismissed and you use this ability again. They can't regain Stamina during the encounter. When the source's Stamina is reduced to 0, you can't use this ability again until you earn 1 or more Victories.

**Persistent 2:** The source takes another turn. They are dismissed at the start of your next turn.

###### Source of Earth Statblock

**Source of Earth**

|       Elemental       |            -             |       Level 8       |          BRUTE          |          EV -          |
| :-------------------: | :----------------------: | :-----------------: | :---------------------: | :--------------------: |
|    **2**<br/> Size    |     **6**<br/> Speed     | **45**<br/> Stamina |  **5**<br/> Stability   | **5**<br/> Free Strike |
| **-**<br/> Immunities | **Burrow**<br/> Movement |                     | **-**<br/> With Captain | **-**<br/> Weaknesses  |
|   **+3**<br/> Might   |   **+1**<br/> Agility    | **-5**<br/> Reason  |  **-5**<br/> Intuition  |  **-3**<br/> Presence  |

<!-- -->
> **Earthwalk**
>
> Difficult terrain composed of earth and stone doesn't cost the source extra movement.

<!-- -->
> **Tunneler**
>
> When the source burrows, they create a size 2 tunnel.

<!-- -->
> **Earth Harness**
>
> A creature that has the Earth Accepts Me ability can use it as a free action to meld into the source.

<!-- -->
> **Boulder Bash**
>
> | **Melee, Ranged, Strike, Weapon** |                 **Signature** |
> | --------------------------------- | ----------------------------: |
> | **📏 Melee 2 or ranged 10**       | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 damage; push 3
> - **12-16:** 9 damage; push 4
> - **17+:** 12 damage; push 5

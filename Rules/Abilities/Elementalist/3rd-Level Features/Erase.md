---
action_type: Main action
class: elementalist
cost: 7 Essence
cost_amount: 7
cost_resource: Essence
distance: Ranged 10
feature_type: ability
file_basename: Erase
file_dpath: Abilities/Elementalist/3rd-Level Features
flavor: With a flick of the wrist, you phase creatures out of existence.
item_id: erase-7-essence
item_index: '06'
item_name: Erase (7 Essence)
keywords:
  - Magic
  - Ranged
  - Strike
  - Void
level: 3
scc:
  - mcdm.heroes.v1:feature.ability.elementalist.3rd-level-feature:erase-7-essence
scdc:
  - 1.1.1:11.2.9.6:06
source: mcdm.heroes.v1
target: Special
type: feature/ability/elementalist/3rd-level-feature
---

###### Erase (7 Essence)

*With a flick of the wrist, you phase creatures out of existence.*

| **Magic, Ranged, Strike, Void** | **Main action** |
| ------------------------------- | --------------: |
| **📏 Ranged 10**                |  **🎯 Special** |

**Special:** The number of creatures you target with this ability is determined by your power roll.

**Power Roll + Reason:**

- **≤11:** One creature
- **12-16:** Two creatures
- **17+:** Three creatures

**Effect:** Each target begins to fade from existence (save ends). On their first turn while fading from existence, a target takes a bane on power rolls. At the end of their first turn, they have a double bane on power rolls. At the end of their second turn, they fade from existence for 1 hour, after which they reappear in their original space or the nearest unoccupied space.

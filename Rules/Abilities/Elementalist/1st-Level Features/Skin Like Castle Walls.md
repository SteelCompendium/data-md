---
action_type: Triggered
class: elementalist
distance: Ranged 10
feature_type: ability
file_basename: Skin Like Castle Walls
file_dpath: Abilities/Elementalist/1st-Level Features
flavor: You cover yourself or an ally in protective stone.
item_id: skin-like-castle-walls
item_index: '14'
item_name: Skin Like Castle Walls
keywords:
  - Earth
  - Magic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.elementalist.1st-level-feature:skin-like-castle-walls
scdc:
  - 1.1.1:11.2.9.1:14
source: mcdm.heroes.v1
subclass: Earth
target: Self or one ally
type: feature/ability/elementalist/1st-level-feature
---

###### Skin Like Castle Walls

*You cover yourself or an ally in protective stone.*

| **Earth, Magic, Ranged** |           **Triggered** |
| ------------------------ | ----------------------: |
| **📏 Ranged 10**         | **🎯 Self or one ally** |

**Trigger:** The target takes damage.

**Effect:** The target takes half the damage.

**Spend 1 Essence:** If the damage has any potency effects associated with it, the potency is reduced by 1 for the target.

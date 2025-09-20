---
action_type: Main action
class: elementalist
cost: 9 Essence
cost_amount: 9
cost_resource: Essence
distance: Ranged 10
feature_type: ability
file_basename: Meteor
file_dpath: Abilities/Elementalist/5th-Level Features
flavor: You teleport the target into the air and let the ground and the elemental force of fire do the rest.
item_id: meteor-9-essence
item_index: '01'
item_name: Meteor (9 Essence)
keywords:
  - Earth
  - Fire
  - Magic
  - Ranged
  - Void
level: 5
scc:
  - mcdm.heroes.v1:feature.ability.elementalist.5th-level-feature:meteor-9-essence
scdc:
  - 1.1.1:11.2.9.4:01
source: mcdm.heroes.v1
target: One creature or object
type: feature/ability/elementalist/5th-level-feature
---

###### Meteor (9 Essence)

*You teleport the target into the air and let the ground and the elemental force of fire do the rest.*

| **Earth, Fire, Magic, Ranged, Void** |               **Main action** |
| ------------------------------------ | ----------------------------: |
| **📏 Ranged 10**                     | **🎯 One creature or object** |

**Power Roll + Reason:**

- **≤11:** You teleport the target up to 4 squares.
- **12-16:** You teleport the target up to 6 squares.
- **17+:** You teleport the target up to 8 squares.

**Effect:** If the target is teleported to a space where they would fall, they immediately do so, treating the fall as if their Agility score were 0. The target takes fire damage from the fall, and each enemy within 3 squares of where they land takes the same amount of fire damage. The ground within 3 squares of where the target lands is difficult terrain.

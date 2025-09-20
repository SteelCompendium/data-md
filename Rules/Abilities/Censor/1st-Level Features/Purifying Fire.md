---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: 5
cost_resource: Wrath
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: Purifying Fire
file_dpath: Abilities/Censor/1st-Level Features
flavor: The gods judge, fire cleanses.
item_id: purifying-fire-5-wrath
item_index: '14'
item_name: Purifying Fire (5 Wrath)
keywords:
  - Magic
  - Melee
  - Ranged
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.censor.1st-level-feature:purifying-fire-5-wrath
scdc:
  - 1.1.1:11.2.7.1:14
source: mcdm.heroes.v1
target: One creature
type: feature/ability/censor/1st-level-feature
---

###### Purifying Fire (5 Wrath)

*The gods judge, fire cleanses.*

| **Magic, Melee, Ranged, Strike, Weapon** |     **Main action** |
| ---------------------------------------- | ------------------: |
| **📏 Melee 1 or ranged 5**               | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 5 + M holy damage; M < WEAK, the target has fire weakness 3 (save ends)
- **12-16:** 9 + M holy damage; M < AVERAGE, the target has fire weakness 5 (save ends)
- **17+:** 12 + M holy damage; M < STRONG, the target has fire weakness 7 (save ends)

**Effect:** While the target has fire weakness from this ability, you can choose to have your abilities deal fire damage to the target instead of holy damage.

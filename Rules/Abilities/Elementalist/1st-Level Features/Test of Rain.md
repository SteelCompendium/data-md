---
action_type: Main action
class: elementalist
cost: 5 Essence
cost_amount: 5
cost_resource: Essence
distance: 3 cube within 10
feature_type: ability
file_basename: Test of Rain
file_dpath: Abilities/Elementalist/1st-Level Features
flavor: You call down a rain that burns your enemies and restores your allies.
item_id: test-of-rain-5-essence
item_index: '15'
item_name: Test of Rain (5 Essence)
keywords:
  - Area
  - Green
  - Magic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.elementalist.1st-level-feature:test-of-rain-5-essence
scdc:
  - 1.1.1:11.2.9.1:15
source: mcdm.heroes.v1
target: Each enemy in the area
type: feature/ability/elementalist/1st-level-feature
---

###### Test of Rain (5 Essence)

*You call down a rain that burns your enemies and restores your allies.*

| **Area, Green, Magic, Ranged** |               **Main action** |
| ------------------------------ | ----------------------------: |
| **📏 3 cube within 10**        | **🎯 Each enemy in the area** |

**Power Roll + Reason:**

- **≤11:** 4 acid damage
- **12-16:** 6 acid damage
- **17+:** 10 acid damage

**Effect:** You can end one effect on yourself that is ended by a saving throw or that ends at the end of your turn. Each ally in the area also gains this benefit.

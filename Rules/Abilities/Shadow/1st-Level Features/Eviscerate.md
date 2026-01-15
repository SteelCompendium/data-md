---
action_type: Main action
class: shadow
cost: 3 Insight
cost_amount: 3
cost_resource: Insight
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: Eviscerate
file_dpath: Abilities/Shadow/1st-Level Features
flavor: You leave your foe bleeding out after a devastating attack.
item_id: eviscerate-3-insight
item_index: '02'
item_name: Eviscerate (3 Insight)
keywords:
  - Melee
  - Ranged
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.shadow.1st-level-feature:eviscerate-3-insight
scdc:
  - 1.1.1:11.2.2.1:02
source: mcdm.heroes.v1
target: One creature
type: feature/ability/shadow/1st-level-feature
---

###### Eviscerate (3 Insight)

*You leave your foe bleeding out after a devastating attack.*

| **Melee, Ranged, Strike, Weapon** |     **Main action** |
| --------------------------------- | ------------------: |
| **📏 Melee 1 or ranged 5**        | **🎯 One creature** |

**Power Roll + Agility:**

- **≤11:** 4 + A damage; A < WEAK, bleeding (save ends)
- **12-16:** 6 + A damage; A < AVERAGE, bleeding (save ends)
- **17+:** 10 + A damage; A < STRONG, bleeding (save ends)

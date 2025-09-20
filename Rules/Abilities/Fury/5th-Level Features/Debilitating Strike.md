---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: 9
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: Debilitating Strike
file_dpath: Abilities/Fury/5th-Level Features
flavor: You need just one blow to sabotage your target.
item_id: debilitating-strike-9-ferocity
item_index: '01'
item_name: Debilitating Strike (9 Ferocity)
keywords:
  - Melee
  - Strike
  - Weapon
level: 5
scc:
  - mcdm.heroes.v1:feature.ability.fury.5th-level-feature:debilitating-strike-9-ferocity
scdc:
  - 1.1.1:11.2.5.4:01
source: mcdm.heroes.v1
target: One creature
type: feature/ability/fury/5th-level-feature
---

###### Debilitating Strike (9 Ferocity)

*You need just one blow to sabotage your target.*

| **Melee, Strike, Weapon** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Melee 1**            | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 10 + M damage; M < WEAK, slowed (save ends)
- **12-16:** 14 + M damage; M < AVERAGE, slowed (save ends)
- **17+:** 20 + M damage; M < STRONG, slowed (save ends)

**Effect:** While slowed this way, the target takes 1 damage for every square they move, including from forced movement.

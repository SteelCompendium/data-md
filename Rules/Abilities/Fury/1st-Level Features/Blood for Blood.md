---
action_type: Main action
class: fury
cost: 5 Ferocity
cost_amount: 5
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: Blood for Blood
file_dpath: Abilities/Fury/1st-Level Features
flavor: See how well they fight after you've bled them dry.
item_id: blood-for-blood-5-ferocity
item_index: '13'
item_name: Blood for Blood! (5 Ferocity)
keywords:
  - Melee
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.fury.1st-level-feature:blood-for-blood-5-ferocity
scdc:
  - 1.1.1:11.2.5.1:13
source: mcdm.heroes.v1
target: One creature or object
type: feature/ability/fury/1st-level-feature
---

###### Blood for Blood! (5 Ferocity)

*See how well they fight after you've bled them dry.*

| **Melee, Strike, Weapon** |               **Main action** |
| ------------------------- | ----------------------------: |
| **📏 Melee 1**            | **🎯 One creature or object** |

**Power Roll + Might:**

- **≤11:** 4 + M damage; M < WEAK, bleeding and weakened (save ends)
- **12-16:** 6 + M damage; M < AVERAGE, bleeding and weakened (save ends)
- **17+:** 10 + M damage; M < STRONG, bleeding and weakened (save ends)

**Effect:** You can deal 1d6 damage to yourself to deal an extra 1d6 damage to the target.

---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: 11
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: Overkill
file_dpath: Abilities/Fury/8th-Level Features
flavor: You strike so no damage is wasted.
item_id: overkill-11-ferocity
item_index: '02'
item_name: Overkill (11 Ferocity)
keywords:
  - Magic
  - Melee
  - Strike
  - Weapon
level: 8
scc:
  - mcdm.heroes.v1:feature.ability.fury.8th-level-feature:overkill-11-ferocity
scdc:
  - 1.1.1:11.2.5.2:02
source: mcdm.heroes.v1
target: One creature
type: feature/ability/fury/8th-level-feature
---

###### Overkill (11 Ferocity)

*You strike so no damage is wasted.*

| **Magic, Melee, Strike, Weapon** |     **Main action** |
| -------------------------------- | ------------------: |
| **📏 Melee 1**                   | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 6 + M damage
- **12-16:** 10 + M damage
- **17+:** 14 + M damage

**Effect:** If the target is a minion or is winded but isn't a leader or solo creature, they are reduced to 0 Stamina before this ability's damage is dealt. If the target is killed by this damage, you can deal any damage over what was required to kill them to another creature within 5 squares of the target.

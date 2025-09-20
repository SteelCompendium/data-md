---
action_type: Free triggered
class: tactician
cost: 9 Focus
cost_amount: 9
cost_resource: Focus
distance: Ranged 10
feature_type: ability
file_basename: Coordinated Execution
file_dpath: Abilities/Tactician/6th-Level Features
flavor: You direct your ally to make a killing blow.
item_id: coordinated-execution-9-focus
item_index: '04'
item_name: Coordinated Execution (9 Focus)
keywords:
  - Ranged
level: 6
scc:
  - mcdm.heroes.v1:feature.ability.tactician.6th-level-feature:coordinated-execution-9-focus
scdc:
  - 1.1.1:11.2.4.3:04
source: mcdm.heroes.v1
subclass: Insurgent
target: One ally
type: feature/ability/tactician/6th-level-feature
---

###### Coordinated Execution (9 Focus)

*You direct your ally to make a killing blow.*

| **Ranged**       | **Free triggered** |
| ---------------- | -----------------: |
| **📏 Ranged 10** |    **🎯 One ally** |

**Trigger:** The target uses an ability to deal rolled damage to a creature while hidden.

**Effect:** If the target of the triggering ability is not a leader or solo creature, they are reduced to 0 Stamina. If the target of the triggering ability is a minion, the entire squad is killed. If the target of the triggering ability is a leader or solo creature, the triggering ability's power roll automatically obtains a tier 3 outcome.

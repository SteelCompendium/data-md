---
action_type: Triggered
class: tactician
distance: Ranged 10
feature_type: ability
file_basename: Advanced Tactics
file_dpath: Abilities/Tactician/1st-Level Features
flavor: Your leadership aids an ally.
item_id: advanced-tactics
item_index: '05'
item_name: Advanced Tactics
keywords:
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.tactician.1st-level-feature:advanced-tactics
scdc:
  - 1.1.1:11.3.4.1:05
source: mcdm.heroes.v1
subclass: Insurgent
target: One ally
type: feature/ability/tactician/1st-level-feature
---

###### Advanced Tactics

*Your leadership aids an ally.*

| **Ranged**       |   **Triggered** |
| ---------------- | --------------: |
| **📏 Ranged 10** | **🎯 One ally** |

**Trigger:** The target deals damage to another creature.

**Effect:** The target gains 2 surges, which they can use on the triggering damage.

**Spend 1 Focus:** If the damage has any potency effect associated with it, the potency is increased by 1.

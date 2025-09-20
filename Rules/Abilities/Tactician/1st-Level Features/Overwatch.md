---
action_type: Triggered
class: tactician
distance: Ranged 10
feature_type: ability
file_basename: Overwatch
file_dpath: Abilities/Tactician/1st-Level Features
flavor: Under your direction, an ally waits for just the right moment to strike.
item_id: overwatch
item_index: '13'
item_name: Overwatch
keywords:
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.tactician.1st-level-feature:overwatch
scdc:
  - 1.1.1:11.2.4.1:13
source: mcdm.heroes.v1
subclass: Mastermind
target: One creature
type: feature/ability/tactician/1st-level-feature
---

###### Overwatch

*Under your direction, an ally waits for just the right moment to strike.*

| **Ranged**       |       **Triggered** |
| ---------------- | ------------------: |
| **📏 Ranged 10** | **🎯 One creature** |

**Trigger:** The target moves.

**Effect:** At any time during the target's movement, one ally can make a free strike against them.

**Spend 1 Focus:** If the target has R < AVERAGE, they are slowed (EoT).

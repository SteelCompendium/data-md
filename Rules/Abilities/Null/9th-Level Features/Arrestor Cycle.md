---
action_type: Free triggered
class: 'null'
cost: 11 Discipline
cost_amount: 11
cost_resource: Discipline
distance: Ranged 10
feature_type: ability
file_basename: Arrestor Cycle
file_dpath: Abilities/Null/9th-Level Features
flavor: You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.
item_id: arrestor-cycle-11-discipline
item_index: '03'
item_name: Arrestor Cycle (11 Discipline)
keywords:
  - Psionic
  - Ranged
level: 9
scc:
  - mcdm.heroes.v1:feature.ability.null.9th-level-feature:arrestor-cycle-11-discipline
scdc:
  - 1.1.1:11.2.6.7:03
source: mcdm.heroes.v1
subclass: Chronokinetic
target: One creature
type: feature/ability/null/9th-level-feature
---

###### Arrestor Cycle (11 Discipline)

*You trap your foe in a looping cycle of time, where they relive the last few seconds over and over again.*

| **Psionic, Ranged** |  **Free triggered** |
| ------------------- | ------------------: |
| **📏 Ranged 10**    | **🎯 One creature** |

**Trigger:** The triggering creature starts their turn.

**Power Roll + Intuition:**

- **≤11:** I < WEAK, the target loses their turn
- **12-16:** I < AVERAGE, the target loses their turn
- **17+:** I < STRONG, the target loses their turn

**Effect:** If the target loses their turn, the round continues as if they had acted. A target who doesn't lose their turn takes psychic damage equal to twice your Intuition score for each main action they take until the end of their next turn.

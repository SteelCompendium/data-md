---
action_type: Maneuver
class: 'null'
cost: 11 Discipline
cost_amount: 11
cost_resource: Discipline
distance: Melee 1
feature_type: ability
file_basename: Heat Drain
file_dpath: Abilities/Null/9th-Level Features
flavor: You drain all the heat from the target.
item_id: heat-drain-11-discipline
item_index: '05'
item_name: Heat Drain (11 Discipline)
keywords:
  - Melee
  - Psionic
  - Strike
level: 9
scc:
  - mcdm.heroes.v1:feature.ability.null.9th-level-feature:heat-drain-11-discipline
scdc:
  - 1.1.1:11.2.6.7:05
source: mcdm.heroes.v1
subclass: Cryokinetic
target: One creature
type: feature/ability/null/9th-level-feature
---

###### Heat Drain (11 Discipline)

*You drain all the heat from the target.*

| **Melee, Psionic, Strike** |        **Maneuver** |
| -------------------------- | ------------------: |
| **📏 Melee 1**             | **🎯 One creature** |

**Power Roll + Intuition:**

- **≤11:** 8 + I cold damage; M < WEAK, restrained (save ends)
- **12-16:** 11 + I cold damage; M < AVERAGE, restrained (save ends)
- **17+:** 15 + I cold damage; M < STRONG, restrained (save ends)

**Effect:** While restrained this way, the target takes cold damage equal to your Intuition score at the start of each of your turns. Additionally, whenever the target damages another creature while restrained this way, any potency associated with the damage is reduced by 2.

---
action_type: Main action
class: 'null'
cost: 5 Discipline
cost_amount: 5
cost_resource: Discipline
distance: Melee 1
feature_type: ability
file_basename: Phase Strike
file_dpath: Abilities/Null/1st-Level Features
flavor: For a moment, your foe slips out of phase with this manifold.
item_id: phase-strike-5-discipline
item_index: '02'
item_name: Phase Strike (5 Discipline)
keywords:
  - Melee
  - Psionic
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.null.1st-level-feature:phase-strike-5-discipline
scdc:
  - 1.1.1:11.2.6.1:02
source: mcdm.heroes.v1
target: One creature
type: feature/ability/null/1st-level-feature
---

###### Phase Strike (5 Discipline)

*For a moment, your foe slips out of phase with this manifold.*

| **Melee, Psionic, Strike, Weapon** |     **Main action** |
| ---------------------------------- | ------------------: |
| **📏 Melee 1**                     | **🎯 One creature** |

**Power Roll + Agility:**

- **≤11:** 3 + A psychic damage; I < WEAK, the target goes out of phase (save ends)
- **12-16:** 4 + A psychic damage; I < AVERAGE, the target goes out of phase (save ends)
- **17+:** 6 + A psychic damage; I < STRONG, the target goes out of phase (save ends)

**Effect:** A target who goes out of phase is slowed, has their stability reduced by 2, and can't obtain a tier 3 outcome on ability rolls.

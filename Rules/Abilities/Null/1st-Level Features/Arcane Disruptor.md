---
action_type: Main action
class: 'null'
cost: 5 Discipline
cost_amount: 5
cost_resource: Discipline
distance: Melee 1
feature_type: ability
file_basename: Arcane Disruptor
file_dpath: Abilities/Null/1st-Level Features
flavor: Your blow reorders a foe's body, causing pain if they attempt to channel sorcery.
item_id: arcane-disruptor-5-discipline
item_index: '15'
item_name: Arcane Disruptor (5 Discipline)
keywords:
  - Melee
  - Psionic
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.null.1st-level-feature:arcane-disruptor-5-discipline
scdc:
  - 1.1.1:11.2.6.1:15
source: mcdm.heroes.v1
target: One creature
type: feature/ability/null/1st-level-feature
---

###### Arcane Disruptor (5 Discipline)

*Your blow reorders a foe's body, causing pain if they attempt to channel sorcery.*

| **Melee, Psionic, Strike, Weapon** |     **Main action** |
| ---------------------------------- | ------------------: |
| **📏 Melee 1**                     | **🎯 One creature** |

**Power Roll + Agility:**

- **≤11:** 8 + **A** psychic damage; M < WEAK, weakened (save ends)
- **12-16:** 12 + **A** psychic damage; M < AVERAGE, weakened (save ends)
- **17+:** 16 + **A** psychic damage; M < STRONG, weakened (save ends)

**Effect:** While weakened this way, the target takes damage equal to your Intuition score whenever they use a supernatural ability that costs Malice.

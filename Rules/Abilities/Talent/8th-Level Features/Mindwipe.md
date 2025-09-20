---
action_type: Main action
class: talent
cost: 11 Clarity
cost_amount: 11
cost_resource: Clarity
distance: Melee 2
feature_type: ability
file_basename: Mindwipe
file_dpath: Abilities/Talent/8th-Level Features
flavor: You attempt to make them forget all their training.
item_id: mindwipe-11-clarity
item_index: '03'
item_name: Mindwipe (11 Clarity)
keywords:
  - Melee
  - Psionic
  - Strike
  - Telepathy
level: 8
scc:
  - mcdm.heroes.v1:feature.ability.talent.8th-level-feature:mindwipe-11-clarity
scdc:
  - 1.1.1:11.2.1.2:03
source: mcdm.heroes.v1
target: One creature
type: feature/ability/talent/8th-level-feature
---

###### Mindwipe (11 Clarity)

*You attempt to make them forget all their training.*

| **Melee, Psionic, Strike, Telepathy** |     **Main action** |
| ------------------------------------- | ------------------: |
| **📏 Melee 2**                        | **🎯 One creature** |

**Power Roll + Reason:**

- **≤11:** 12 + R damage; R < WEAK, the target takes a bane on their next power roll
- **12-16:** 17 + R damage; R < AVERAGE, the target takes a bane on power rolls (save ends)
- **17+:** 23 + R damage; R < STRONG, the target has a double bane on power rolls (save ends)

**Effect:** The target can't communicate with anyone until the end of the encounter.

**Strained:** You take 3d6 damage.

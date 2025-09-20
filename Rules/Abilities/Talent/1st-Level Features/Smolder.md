---
action_type: Main action
class: talent
cost: 3 Clarity
cost_amount: 3
cost_resource: Clarity
distance: Ranged 10
feature_type: ability
file_basename: Smolder
file_dpath: Abilities/Talent/1st-Level Features
flavor: Smoke flows from your enemy like tears as their skin begins to blacken and flake.
item_id: smolder-3-clarity
item_index: 09
item_name: Smolder (3 Clarity)
keywords:
  - Psionic
  - Pyrokinesis
  - Ranged
  - Strike
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.talent.1st-level-feature:smolder-3-clarity
scdc:
  - 1.1.1:11.2.1.1:09
source: mcdm.heroes.v1
target: One creature
type: feature/ability/talent/1st-level-feature
---

###### Smolder (3 Clarity)

*Smoke flows from your enemy like tears as their skin begins to blacken and flake.*

| **Psionic, Pyrokinesis, Ranged, Strike** |     **Main action** |
| ---------------------------------------- | ------------------: |
| **📏 Ranged 10**                         | **🎯 One creature** |

**Effect:** Choose the damage type and the weakness for this ability from one of the following: acid, corruption, or fire. The target takes damage before this ability imposes any weakness.

**Power Roll + Reason:**

- **≤11:** 3 + R damage; R < WEAK, the target has weakness 5 (save ends)
- **12-16:** 6 + R damage; R < AVERAGE, the target has weakness 5 (save ends)
- **17+:** 9 + R damage; R < STRONG, the target has weakness equal to 5 + your Reason score (save ends)

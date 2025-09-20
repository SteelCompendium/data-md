---
action_type: Main action
class: tactician
cost: 3 Focus
cost_amount: 3
cost_resource: Focus
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: Concussive Strike
file_dpath: Abilities/Tactician/1st-Level Features
flavor: Your precise strike leaves your foe struggling to respond.
item_id: concussive-strike-3-focus
item_index: '10'
item_name: Concussive Strike (3 Focus)
keywords:
  - Melee
  - Ranged
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.tactician.1st-level-feature:concussive-strike-3-focus
scdc:
  - 1.1.1:11.2.4.1:10
source: mcdm.heroes.v1
target: One creature or object
type: feature/ability/tactician/1st-level-feature
---

###### Concussive Strike (3 Focus)

*Your precise strike leaves your foe struggling to respond.*

| **Melee, Ranged, Strike, Weapon** |               **Main action** |
| --------------------------------- | ----------------------------: |
| **📏 Melee 1 or ranged 5**        | **🎯 One creature or object** |

**Power Roll + Might:**

- **≤11:** 3 + M damage; M < WEAK, dazed (save ends)
- **12-16:** 5 + M damage; M < AVERAGE, dazed (save ends)
- **17+:** 8 + M damage; M < STRONG, dazed (save ends)

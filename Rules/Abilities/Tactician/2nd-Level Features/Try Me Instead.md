---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: 5
cost_resource: Focus
distance: Self; see below
feature_type: ability
file_basename: Try Me Instead
file_dpath: Abilities/Tactician/2nd-Level Features
flavor: '"Try picking on someone my size."'
item_id: try-me-instead-5-focus
item_index: '01'
item_name: Try Me Instead (5 Focus)
keywords:
  - Melee
  - Strike
  - Weapon
level: 2
scc:
  - mcdm.heroes.v1:feature.ability.tactician.2nd-level-feature:try-me-instead-5-focus
scdc:
  - 1.1.1:11.2.4.5:01
source: mcdm.heroes.v1
subclass: Insurgent
target: Self
type: feature/ability/tactician/2nd-level-feature
---

###### Try Me Instead (5 Focus)

*"Try picking on someone my size."*

| **Melee, Strike, Weapon** | **Main action** |
| ------------------------- | --------------: |
| **📏 Self; see below**    |     **🎯 Self** |

**Effect:** You shift up to your speed directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a Recovery, and you can make the following weapon strike with a distance of melee 1 against a creature.

**Power Roll + Reason:**

- **≤11:** 2 + R damage; R < WEAK, frightened (save ends)
- **12-16:** 3 + R damage; R < AVERAGE, frightened (save ends)
- **17+:** 4 + R damage; R < STRONG, frightened (save ends)

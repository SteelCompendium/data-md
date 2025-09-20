---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: 5
cost_resource: Focus
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: Mind Game
file_dpath: Abilities/Tactician/1st-Level Features
flavor: Your attack demoralizes your foe. Your allies begin to think you can win.
item_id: mind-game-5-focus
item_index: '12'
item_name: Mind Game (5 Focus)
keywords:
  - Melee
  - Ranged
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.tactician.1st-level-feature:mind-game-5-focus
scdc:
  - 1.1.1:11.2.4.1:12
source: mcdm.heroes.v1
target: One creature or object
type: feature/ability/tactician/1st-level-feature
---

###### Mind Game (5 Focus)

*Your attack demoralizes your foe. Your allies begin to think you can win.*

| **Melee, Ranged, Strike, Weapon** |               **Main action** |
| --------------------------------- | ----------------------------: |
| **📏 Melee 1 or ranged 5**        | **🎯 One creature or object** |

**Effect:** You mark the target.

**Power Roll + Might:**

- **≤11:** 4 + M damage; R < WEAK, weakened (save ends)
- **12-16:** 6 + M damage; R < AVERAGE, weakened (save ends)
- **17+:** 10 + M damage; R < STRONG, weakened (save ends)

**Effect:** Before the start of your next turn, the first time any ally deals damage to any target marked by you, that ally can spend a Recovery.

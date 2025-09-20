---
action_type: Main action
class: troubadour
cost: 3 Drama
cost_amount: 3
cost_resource: Drama
distance: 3 cube within 10
feature_type: ability
file_basename: Quick Rewrite
file_dpath: Abilities/Troubadour/1st-Level Features
flavor: You write something unexpected into the scene that hinders your enemy.
item_id: quick-rewrite-3-drama
item_index: '01'
item_name: Quick Rewrite (3 Drama)
keywords:
  - Area
  - Magic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.troubadour.1st-level-feature:quick-rewrite-3-drama
scdc:
  - 1.1.1:11.2.3.1:01
source: mcdm.heroes.v1
target: Each enemy in the area
type: feature/ability/troubadour/1st-level-feature
---

###### Quick Rewrite (3 Drama)

*You write something unexpected into the scene that hinders your enemy.*

| **Area, Magic, Ranged** |               **Main action** |
| ----------------------- | ----------------------------: |
| **📏 3 cube within 10** | **🎯 Each enemy in the area** |

**Power Roll + Presence:**

- **≤11:** 4 damage; P < WEAK, slowed (save ends)
- **12-16:** 5 damage; P < AVERAGE, slowed (save ends)
- **17+:** 6 damage; P < STRONG, restrained (save ends)

**Effect:** The area is difficult terrain for enemies.

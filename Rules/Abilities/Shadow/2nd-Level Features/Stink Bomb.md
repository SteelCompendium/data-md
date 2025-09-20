---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: 5
cost_resource: Insight
distance: 3 cube within 10
feature_type: ability
file_basename: Stink Bomb
file_dpath: Abilities/Shadow/2nd-Level Features
flavor: Putrid yellow gas explodes from a bomb you toss.
item_id: stink-bomb-5-insight
item_index: '06'
item_name: Stink Bomb (5 Insight)
keywords:
  - Area
  - Ranged
level: 2
scc:
  - mcdm.heroes.v1:feature.ability.shadow.2nd-level-feature:stink-bomb-5-insight
scdc:
  - 1.1.1:11.2.2.5:06
source: mcdm.heroes.v1
subclass: Caustic Alchemy
target: Each creature in the area
type: feature/ability/shadow/2nd-level-feature
---

###### Stink Bomb (5 Insight)

*Putrid yellow gas explodes from a bomb you toss.*

| **Area, Ranged**        |                  **Main action** |
| ----------------------- | -------------------------------: |
| **📏 3 cube within 10** | **🎯 Each creature in the area** |

**Power Roll + Agility:**

- **≤11:** 2 poison damage
- **12-16:** 5 poison damage
- **17+:** 7 poison damage

**Effect:** The gas remains in the area until the end of the encounter. Any creature who starts their turn in the area and has M < AVERAGE is weakened (save ends).

---
action_type: Maneuver
class: troubadour
cost: 11 Drama
cost_amount: 11
cost_resource: Drama
distance: 5 cube within 10
feature_type: ability
file_basename: The Show Must Go On
file_dpath: Abilities/Troubadour/8th-Level Features
flavor: You shine a bright light on the players on the stage and compel them to finish the performance.
item_id: the-show-must-go-on-11-drama
item_index: '04'
item_name: The Show Must Go On (11 Drama)
keywords:
  - Area
  - Magic
  - Ranged
level: 8
scc:
  - mcdm.heroes.v1:feature.ability.troubadour.8th-level-feature:the-show-must-go-on-11-drama
scdc:
  - 1.1.1:11.2.3.2:04
source: mcdm.heroes.v1
target: Each enemy in the area
type: feature/ability/troubadour/8th-level-feature
---

###### The Show Must Go On (11 Drama)

*You shine a bright light on the players on the stage and compel them to finish the performance.*

| **Area, Magic, Ranged** | **Maneuver**                  |
| ----------------------- | ----------------------------- |
| **📏 5 cube within 10** | **🎯 Each enemy in the area** |

**Power Roll + Presence:**

- **≤11:** 6 damage; P < WEAK, the target can't willingly leave the area (EoT)
- **12-16:** 8 damage; P < AVERAGE, the target can't willingly leave the area (save ends)
- **17+:** 12 damage; the target can't willingly leave the area (EoT); if P < STRONG, they can't willingly leave the area (save ends)

**Effect:** Each ally within distance can't obtain lower than a tier 2 outcome on the next test they make before the start of your next turn.

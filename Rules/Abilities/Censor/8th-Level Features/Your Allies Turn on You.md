---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: 11
cost_resource: Wrath
distance: Ranged 10
feature_type: ability
file_basename: Your Allies Turn on You
file_dpath: Abilities/Censor/8th-Level Features
flavor: You turn your enemies' ire to the target.
item_id: your-allies-turn-on-you-11-wrath
item_index: '03'
item_name: Your Allies Turn on You! (11 Wrath)
keywords:
  - Ranged
  - Strike
  - Weapon
level: 8
scc:
  - mcdm.heroes.v1:feature.ability.censor.8th-level-feature:your-allies-turn-on-you-11-wrath
scdc:
  - 1.1.1:11.2.7.2:03
source: mcdm.heroes.v1
target: One creature
type: feature/ability/censor/8th-level-feature
---

###### Your Allies Turn on You! (11 Wrath)

*You turn your enemies' ire to the target.*

| **Ranged, Strike, Weapon** |     **Main action** |
| -------------------------- | ------------------: |
| **📏 Ranged 10**           | **🎯 One creature** |

**Power Roll + Presence:**

- **≤11:** 5 + P damage; I < WEAK, slowed (save ends)
- **12-16:** 9 + P damage; I < AVERAGE, slowed (save ends)
- **17+:** 12 + P damage; I < STRONG, slowed (save ends)

**Effect:** While the target is slowed this way, each of their allies who starts their turn within 5 squares of them must use a free maneuver to make a free strike against the target. Additionally, while the target is slowed this way, each of their allies within 5 squares of them who can make a triggered free strike against a different creature must make the free strike against the target instead.

---
ability_type: Signature
action_type: Main action
class: censor
distance: Ranged 10
feature_type: ability
file_basename: Every Step Death
file_dpath: Abilities/Censor/1st-Level Features
flavor: You show your foe a glimpse of their fate after death.
item_id: every-step-death
item_index: '15'
item_name: Every Step... Death!
keywords:
  - Magic
  - Ranged
  - Strike
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.censor.1st-level-feature:every-step-death
scdc:
  - 1.1.1:11.2.7.1:15
source: mcdm.heroes.v1
target: One creature
type: feature/ability/censor/1st-level-feature
---

###### Every Step... Death!

*You show your foe a glimpse of their fate after death.*

| **Magic, Ranged, Strike** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Ranged 10**          | **🎯 One creature** |

**Power Roll + Presence:**

- **≤11:** 5 + P psychic damage
- **12-16:** 7 + P psychic damage
- **17+:** 10 + P psychic damage

**Effect:** Each time the target willingly moves before the end of your next turn, they take 1 psychic damage for each square they move.

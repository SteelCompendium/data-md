---
ability_type: Signature
action_type: Main action
class: shadow
distance: Melee 1
feature_type: ability
file_basename: Gasping in Pain
file_dpath: Abilities/Shadow/1st-Level Features
flavor: Your precise strikes let your allies take advantage of a target's agony.
item_id: gasping-in-pain
item_index: '01'
item_name: Gasping in Pain
keywords:
  - Melee
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.shadow.1st-level-feature:gasping-in-pain
scdc:
  - 1.1.1:11.2.2.1:01
source: mcdm.heroes.v1
target: One creature
type: feature/ability/shadow/1st-level-feature
---

###### Gasping in Pain

*Your precise strikes let your allies take advantage of a target's agony.*

| **Melee, Strike, Weapon** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Melee 1**            | **🎯 One creature** |

**Power Roll + Agility:**

- **≤11:** 3 + A damage
- **12-16:** 5 + A damage
- **17+:** 8 + A damage; I < STRONG, prone

**Effect:** One ally within 5 squares of the target gains 1 surge.

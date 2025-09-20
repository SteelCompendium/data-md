---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: 11
cost_resource: Wrath
distance: Melee 1
feature_type: ability
file_basename: Excommunication
file_dpath: Abilities/Censor/8th-Level Features
flavor: You curse your foe to become a bane to their allies.
item_id: excommunication-11-wrath
item_index: '04'
item_name: Excommunication (11 Wrath)
keywords:
  - Melee
  - Strike
  - Weapon
level: 8
scc:
  - mcdm.heroes.v1:feature.ability.censor.8th-level-feature:excommunication-11-wrath
scdc:
  - 1.1.1:11.2.7.2:04
source: mcdm.heroes.v1
target: One creature
type: feature/ability/censor/8th-level-feature
---

###### Excommunication (11 Wrath)

*You curse your foe to become a bane to their allies.*

| **Melee, Strike, Weapon** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Melee 1**            | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 9 + M damage; I < WEAK, weakened (save ends)
- **12-16:** 13 + M damage; I < AVERAGE, weakened (save ends)
- **17+:** 18 + M damage; I < STRONG, weakened (save ends)

**Effect:** At the end of each of your turns, a target weakened this way deals holy damage equal to twice your Presence score to each enemy within 2 squares of them. Additionally, a target weakened this way can't be targeted by their allies' abilities.

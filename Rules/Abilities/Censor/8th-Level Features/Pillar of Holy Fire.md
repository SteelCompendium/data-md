---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: 11
cost_resource: Wrath
distance: Melee 1
feature_type: ability
file_basename: Pillar of Holy Fire
file_dpath: Abilities/Censor/8th-Level Features
flavor: Your enemy's guilt fuels a holy flame that burns your foes.
item_id: pillar-of-holy-fire-11-wrath
item_index: '01'
item_name: Pillar of Holy Fire (11 Wrath)
keywords:
  - Melee
  - Strike
  - Weapon
level: 8
scc:
  - mcdm.heroes.v1:feature.ability.censor.8th-level-feature:pillar-of-holy-fire-11-wrath
scdc:
  - 1.1.1:11.2.7.2:01
source: mcdm.heroes.v1
target: One creature
type: feature/ability/censor/8th-level-feature
---

###### Pillar of Holy Fire (11 Wrath)

*Your enemy's guilt fuels a holy flame that burns your foes.*

| **Melee, Strike, Weapon** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Melee 1**            | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 9 + M damage; I < WEAK, dazed (save ends)
- **12-16:** 13 + M damage; I < AVERAGE, dazed (save ends)
- **17+:** 18 + M damage; I < STRONG, dazed (save ends)

**Effect:** At the end of each of your turns, a target dazed this way deals holy damage equal to twice your Presence score to each enemy within 2 squares of them.

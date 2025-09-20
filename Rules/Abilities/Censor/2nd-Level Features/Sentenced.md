---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: 5
cost_resource: Wrath
distance: Melee 1
feature_type: ability
file_basename: Sentenced
file_dpath: Abilities/Censor/2nd-Level Features
flavor: The shock of your condemnation freezes your enemy in their boots.
item_id: sentenced-5-wrath
item_index: '02'
item_name: Sentenced (5 Wrath)
keywords:
  - Magic
  - Melee
  - Strike
  - Weapon
level: 2
scc:
  - mcdm.heroes.v1:feature.ability.censor.2nd-level-feature:sentenced-5-wrath
scdc:
  - 1.1.1:11.2.7.5:02
source: mcdm.heroes.v1
subclass: Paragon
target: One creature
type: feature/ability/censor/2nd-level-feature
---

###### Sentenced (5 Wrath)

*The shock of your condemnation freezes your enemy in their boots.*

| **Magic, Melee, Strike, Weapon** |     **Main action** |
| -------------------------------- | ------------------: |
| **📏 Melee 1**                   | **🎯 One creature** |

**Power Roll + Presence:**

- **≤11:** 5 + P damage; P < WEAK, restrained (save ends)
- **12-16:** 9 + P damage; P < AVERAGE, restrained (save ends)
- **17+:** 12 + P damage; P < STRONG, restrained (save ends)

**Effect:** While the target is restrained this way, your abilities that impose forced movement can still move them.

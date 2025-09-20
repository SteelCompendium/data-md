---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: 9
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: To Stone
file_dpath: Abilities/Fury/5th-Level Features
flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
item_id: to-stone-9-ferocity
item_index: '03'
item_name: To Stone! (9 Ferocity)
keywords:
  - Magic
  - Melee
  - Strike
  - Weapon
level: 5
scc:
  - mcdm.heroes.v1:feature.ability.fury.5th-level-feature:to-stone-9-ferocity
scdc:
  - 1.1.1:11.2.5.4:03
source: mcdm.heroes.v1
target: One creature
type: feature/ability/fury/5th-level-feature
---

###### To Stone! (9 Ferocity)

*You channel the Primordial Chaos into blows that petrify your foe... literally.*

| **Magic, Melee, Strike, Weapon** |     **Main action** |
| -------------------------------- | ------------------: |
| **📏 Melee 1**                   | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 9 + M damage; M < WEAK, slowed (save ends)
- **12-16:** 13 + M damage; M < AVERAGE, slowed (save ends)
- **17+:** 18 + M damage; M < STRONG, restrained (save ends)

**Effect:** While the target is slowed this way, any other effect that would make the target slowed instead makes them restrained by this ability. Additionally, a creature who fails the saving throw while restrained this way is petrified until they are given a supernatural cure or you choose to reverse the effect (no action required).

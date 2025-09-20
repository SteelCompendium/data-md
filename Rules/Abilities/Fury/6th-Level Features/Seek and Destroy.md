---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: 9
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: Seek and Destroy
file_dpath: Abilities/Fury/6th-Level Features
flavor: You break through the enemy lines to make an example.
item_id: seek-and-destroy-9-ferocity
item_index: '06'
item_name: Seek and Destroy (9 Ferocity)
keywords:
  - Melee
  - Strike
  - Weapon
level: 6
scc:
  - mcdm.heroes.v1:feature.ability.fury.6th-level-feature:seek-and-destroy-9-ferocity
scdc:
  - 1.1.1:11.2.5.3:06
source: mcdm.heroes.v1
subclass: Reaver
target: One creature
type: feature/ability/fury/6th-level-feature
---

###### Seek and Destroy (9 Ferocity)

*You break through the enemy lines to make an example.*

| **Melee, Strike, Weapon** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Melee 1**            | **🎯 One creature** |

**Effect:** You shift up to your speed.

**Power Roll + Might:**

- **≤11:** 4 + M damage; P < WEAK, frightened (save ends)
- **12-16:** 6 + M damage; P < AVERAGE, frightened (save ends)
- **17+:** 10 + M damage; P < STRONG, frightened (save ends)

**Effect:** If a target who is not a leader or solo creature is winded by this strike, they are reduced to 0 Stamina and you choose an enemy within 5 squares of you. If that enemy has P < AVERAGE, they are frightened of you (save ends).

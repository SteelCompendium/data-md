---
action_type: Free triggered
class: fury
cost: 9 Ferocity
cost_amount: 9
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: My Turn
file_dpath: Abilities/Fury/5th-Level Features
flavor: You quickly strike back at a foe.
item_id: my-turn-9-ferocity
item_index: '04'
item_name: My Turn! (9 Ferocity)
keywords:
  - Melee
  - Strike
  - Weapon
level: 5
scc:
  - mcdm.heroes.v1:feature.ability.fury.5th-level-feature:my-turn-9-ferocity
scdc:
  - 1.1.1:11.2.5.4:04
source: mcdm.heroes.v1
target: The triggering creature
type: feature/ability/fury/5th-level-feature
---

###### My Turn! (9 Ferocity)

*You quickly strike back at a foe.*

| **Melee, Strike, Weapon** |             **Free triggered** |
| ------------------------- | -----------------------------: |
| **📏 Melee 1**            | **🎯 The triggering creature** |

**Trigger:** A creature causes you to be winded or dying, or damages you while you are winded or dying.

**Power Roll + Might:**

- **≤11:** 6 + M damage
- **12-16:** 9 + M damage
- **17+:** 13 + M damage

**Effect:** You can spend a Recovery.

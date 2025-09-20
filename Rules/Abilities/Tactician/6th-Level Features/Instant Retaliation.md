---
action_type: Free triggered
class: tactician
cost: 9 Focus
cost_amount: 9
cost_resource: Focus
distance: Melee 1
feature_type: ability
file_basename: Instant Retaliation
file_dpath: Abilities/Tactician/6th-Level Features
flavor: You parry with almost supernatural speed.
item_id: instant-retaliation-9-focus
item_index: '05'
item_name: Instant Retaliation (9 Focus)
keywords:
  - Melee
  - Weapon
level: 6
scc:
  - mcdm.heroes.v1:feature.ability.tactician.6th-level-feature:instant-retaliation-9-focus
scdc:
  - 1.1.1:11.2.4.3:05
source: mcdm.heroes.v1
subclass: Vanguard
target: One ally
type: feature/ability/tactician/6th-level-feature
---

###### Instant Retaliation (9 Focus)

*You parry with almost supernatural speed.*

| **Melee, Weapon** | **Free triggered** |
| ----------------- | -----------------: |
| **📏 Melee 1**    |    **🎯 One ally** |

**Trigger:** A creature deals damage to the target.

**Effect:** The target takes half the damage. You then make a power roll against the triggering creature.

**Power Roll + Might:**

- **≤11:** A < WEAK, dazed (save ends)
- **12-16:** A < AVERAGE, dazed (save ends)
- **17+:** A < STRONG, dazed (save ends)

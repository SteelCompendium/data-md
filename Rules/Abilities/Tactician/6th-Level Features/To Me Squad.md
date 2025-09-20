---
action_type: Main action
class: tactician
cost: 9 Focus
cost_amount: 9
cost_resource: Focus
distance: Melee 1
feature_type: ability
file_basename: To Me Squad
file_dpath: Abilities/Tactician/6th-Level Features
flavor: You lead your allies in a charge.
item_id: to-me-squad-9-focus
item_index: '06'
item_name: To Me Squad! (9 Focus)
keywords:
  - Charge
  - Melee
  - Strike
  - Weapon
level: 6
scc:
  - mcdm.heroes.v1:feature.ability.tactician.6th-level-feature:to-me-squad-9-focus
scdc:
  - 1.1.1:11.2.4.3:06
source: mcdm.heroes.v1
subclass: Vanguard
target: One creature
type: feature/ability/tactician/6th-level-feature
---

###### To Me Squad! (9 Focus)

*You lead your allies in a charge.*

| **Charge, Melee, Strike, Weapon** |     **Main action** |
| --------------------------------- | ------------------: |
| **📏 Melee 1**                    | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 6 + M damage; one ally within 10 squares can use the Charge main action as a free triggered action, and can use a melee strike signature ability instead of a free strike for the charge
- **12-16:** 9 + M damage; one ally within 10 squares can use the Charge main action as a free triggered action, and can use a melee strike signature ability that gains an edge instead of a free strike for the charge
- **17+:** 13 + M damage; two allies within 10 squares can use the Charge main action as a free triggered action, and can each use a melee strike signature ability that gains an edge instead of a free strike for the charge

**Effect:** If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are dazed (save ends). If the target is reduced to 0 Stamina before one or both allies has made their strike, the ally or allies can pick a different target.

---
action_type: Triggered
class: censor
cost: 5 Wrath
cost_amount: 5
cost_resource: Wrath
distance: Ranged 10
feature_type: ability
file_basename: Prescient Grace
file_dpath: Abilities/Censor/2nd-Level Features
flavor: Gifted by a prescient vision, you warn an ally of an impending attack.
item_id: prescient-grace-5-wrath
item_index: '06'
item_name: Prescient Grace (5 Wrath)
keywords:
  - Magic
  - Ranged
level: 2
scc:
  - mcdm.heroes.v1:feature.ability.censor.2nd-level-feature:prescient-grace-5-wrath
scdc:
  - 1.1.1:11.2.7.5:06
source: mcdm.heroes.v1
subclass: Oracle
target: Self or one ally
type: feature/ability/censor/2nd-level-feature
---

###### Prescient Grace (5 Wrath)

*Gifted by a prescient vision, you warn an ally of an impending attack.*

| **Magic, Ranged** |           **Triggered** |
| ----------------- | ----------------------: |
| **📏 Ranged 10**  | **🎯 Self or one ally** |

**Trigger:** An enemy within 10 squares starts their turn.

**Effect:** You can spend a Recovery to allow the target to regain Stamina equal to your recovery value. The target can then take their turn immediately before the triggering enemy.

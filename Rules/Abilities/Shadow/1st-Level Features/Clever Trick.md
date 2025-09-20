---
action_type: Triggered
class: shadow
cost: 1 Insight
cost_amount: 1
cost_resource: Insight
distance: Self
feature_type: ability
file_basename: Clever Trick
file_dpath: Abilities/Shadow/1st-Level Features
flavor: You sow a moment of confusion in combat, to your enemy's peril.
item_id: clever-trick-1-insight
item_index: '06'
item_name: Clever Trick (1 Insight)
keywords:
  - Magic
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.shadow.1st-level-feature:clever-trick-1-insight
scdc:
  - 1.1.1:11.2.2.1:06
source: mcdm.heroes.v1
subclass: Harlequin Mask
target: Self
type: feature/ability/shadow/1st-level-feature
---

###### Clever Trick (1 Insight)

*You sow a moment of confusion in combat, to your enemy's peril.*

| **Magic**   | **Triggered** |
| ----------- | ------------: |
| **📏 Self** |   **🎯 Self** |

**Trigger:** An enemy targets you with a strike.

**Effect:** Choose an enemy within distance of the triggering strike, including the enemy who targeted you. The strike targets that enemy instead.

---
action_type: Triggered
class: troubadour
cost: 3 Drama
cost_amount: 3
cost_resource: Drama
distance: Ranged 5
feature_type: ability
file_basename: Harmonize
file_dpath: Abilities/Troubadour/1st-Level Features
flavor: Give the chorus a little punch.
item_id: harmonize-3-drama
item_index: '23'
item_name: Harmonize (3 Drama)
keywords:
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.troubadour.1st-level-feature:harmonize-3-drama
scdc:
  - 1.1.1:11.2.3.1:23
source: mcdm.heroes.v1
subclass: Virtuoso
target: One ally
type: feature/ability/troubadour/1st-level-feature
---

###### Harmonize (3 Drama)

*Give the chorus a little punch.*

| **Ranged**      |   **Triggered** |
| --------------- | --------------: |
| **📏 Ranged 5** | **🎯 One ally** |

**Trigger:** The target uses an ability that targets only one enemy and costs 3 or fewer of their Heroic Resource.

**Effect:** The target can choose one additional target for the triggering ability. Any damage dealt to the additional target is sonic damage.

**Spend 1+ Drama:** You can trigger this ability when a target uses an ability that has a Heroic Resource cost of 3 + each additional drama spent.

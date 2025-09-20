---
action_type: Triggered
class: talent
distance: Ranged 10
feature_type: ability
file_basename: Repel
file_dpath: Abilities/Talent/1st-Level Features
flavor: They aren't going anywhere, but you might!
item_id: repel
item_index: '18'
item_name: Repel
keywords:
  - Psionic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.talent.1st-level-feature:repel
scdc:
  - 1.1.1:11.2.1.1:18
source: mcdm.heroes.v1
subclass: Telekinesis
target: Self or one ally
type: feature/ability/talent/1st-level-feature
---

###### Repel

*They aren't going anywhere, but you might!*

| **Psionic, Ranged** |           **Triggered** |
| ------------------- | ----------------------: |
| **📏 Ranged 10**    | **🎯 Self or one ally** |

**Trigger:** The target takes damage or is force moved.

**Effect:** The target takes half the triggering damage, or the distance of the triggering forced movement is reduced by a number of squares equal to your Reason score. If the target took damage and was force moved, you choose the effect. If the forced movement is reduced to 0 squares, the target can push the source of the forced movement a number of squares equal to your Reason score.

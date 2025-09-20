---
action_type: Triggered
class: censor
distance: Ranged 10
feature_type: ability
file_basename: My Life for Yours
file_dpath: Abilities/Censor/1st-Level Features
flavor: You channel some of your vitality into more resilience for you or an ally.
item_id: my-life-for-yours
item_index: '02'
item_name: My Life for Yours
keywords:
  - Magic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.censor.1st-level-feature:my-life-for-yours
scdc:
  - 1.1.1:11.2.7.1:02
source: mcdm.heroes.v1
target: Self or one ally
type: feature/ability/censor/1st-level-feature
---

###### My Life for Yours

*You channel some of your vitality into more resilience for you or an ally.*

| **Magic, Ranged** |           **Triggered** |
| ----------------- | ----------------------: |
| **📏 Ranged 10**  | **🎯 Self or one ally** |

**Trigger:** The target starts their turn or takes damage.

**Effect:** You spend a Recovery and the target regains Stamina equal to your recovery value.

**Spend 1 Wrath:** You can end one effect on the target that is ended by a saving throw or that ends at the end of their turn, or a prone target can stand up.

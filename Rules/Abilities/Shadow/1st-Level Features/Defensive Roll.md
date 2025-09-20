---
action_type: Triggered
class: shadow
distance: Self
feature_type: ability
file_basename: Defensive Roll
file_dpath: Abilities/Shadow/1st-Level Features
flavor: When an enemy attacks, you roll with the impact to reduce the harm.
item_id: defensive-roll
item_index: '13'
item_name: Defensive Roll
keywords:
  - '-'
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.shadow.1st-level-feature:defensive-roll
scdc:
  - 1.1.1:11.2.2.1:13
source: mcdm.heroes.v1
subclass: Caustic Alchemy
target: Self
type: feature/ability/shadow/1st-level-feature
---

###### Defensive Roll

*When an enemy attacks, you roll with the impact to reduce the harm.*

| **-**       | **Triggered** |
| ----------- | ------------: |
| **📏 Self** |   **🎯 Self** |

**Trigger:** Another creature damages you.

**Effect:** You take half the triggering damage, then can shift up to 2 squares after the triggering effect resolves. If you end this shift with concealment or cover, you can use the Hide maneuver even if you are observed.

**Spend 1 Insight:** The potency of any effects associated with the damage are reduced by 1 for you.

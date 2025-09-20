---
action_type: Free triggered
class: 'null'
cost: 11 Discipline
cost_amount: 11
cost_resource: Discipline
distance: Self; see below
feature_type: ability
file_basename: Synaptic Anchor
file_dpath: Abilities/Null/8th-Level Features
flavor: You disrupt an enemy's strike and create a feedback loop in their mind, preventing them from focusing on future attacks.
item_id: synaptic-anchor-11-discipline
item_index: '01'
item_name: Synaptic Anchor (11 Discipline)
keywords:
  - Psionic
level: 8
scc:
  - mcdm.heroes.v1:feature.ability.null.8th-level-feature:synaptic-anchor-11-discipline
scdc:
  - 1.1.1:11.2.6.2:01
source: mcdm.heroes.v1
target: Self or one creature
type: feature/ability/null/8th-level-feature
---

###### Synaptic Anchor (11 Discipline)

*You disrupt an enemy's strike and create a feedback loop in their mind, preventing them from focusing on future attacks.*

| **Psionic**            |          **Free triggered** |
| ---------------------- | --------------------------: |
| **📏 Self; see below** | **🎯 Self or one creature** |

**Trigger:** The target takes damage from another creature's ability while in the area of your Null Field ability.

**Effect:** The target takes half the damage, and if the triggering creature has I < AVERAGE, they are dazed (save ends). While the triggering creature is dazed this way, they take psychic damage equal to your Intuition score whenever they use a main action.

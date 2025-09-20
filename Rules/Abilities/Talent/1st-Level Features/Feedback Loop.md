---
action_type: Triggered
class: talent
distance: Ranged 10
feature_type: ability
file_basename: Feedback Loop
file_dpath: Abilities/Talent/1st-Level Features
flavor: Creating a brief psychic link between an enemy and their target gives that foe a taste of their own medicine.
item_id: feedback-loop
item_index: '20'
item_name: Feedback Loop
keywords:
  - Psionic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.talent.1st-level-feature:feedback-loop
scdc:
  - 1.1.1:11.2.1.1:20
source: mcdm.heroes.v1
subclass: Telepathy
target: One creature
type: feature/ability/talent/1st-level-feature
---

###### Feedback Loop

*Creating a brief psychic link between an enemy and their target gives that foe a taste of their own medicine.*

| **Psionic, Ranged** |       **Triggered** |
| ------------------- | ------------------: |
| **📏 Ranged 10**    | **🎯 One creature** |

**Trigger:** The target deals damage to an ally.

**Effect:** The target takes psychic damage equal to half the triggering damage.

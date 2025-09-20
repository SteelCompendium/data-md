---
action_type: Triggered
class: conduit
distance: Ranged 10
feature_type: ability
file_basename: Word of Judgment
file_dpath: Abilities/Conduit/1st-Level Features
flavor: Your holy word saps an attacking enemy's strength.
item_id: word-of-judgment
item_index: '16'
item_name: Word of Judgment
keywords:
  - Magic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.conduit.1st-level-feature:word-of-judgment
scdc:
  - 1.1.1:11.2.8.1:16
source: mcdm.heroes.v1
target: One ally
type: feature/ability/conduit/1st-level-feature
---

###### Word of Judgment

*Your holy word saps an attacking enemy's strength.*

| **Magic, Ranged** |   **Triggered** |
| ----------------- | --------------: |
| **📏 Ranged 10**  | **🎯 One ally** |

**Trigger:** The target would take damage from an ability that uses a power roll.

**Effect:** The power roll takes a bane against the target.

**Spend 1 Piety:** The power roll has a double bane against the target.

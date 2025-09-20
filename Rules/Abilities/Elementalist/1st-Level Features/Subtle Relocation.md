---
action_type: Triggered
class: elementalist
distance: Ranged 10
feature_type: ability
file_basename: Subtle Relocation
file_dpath: Abilities/Elementalist/1st-Level Features
flavor: You call on the void to swallow and spit out an ally.
item_id: subtle-relocation
item_index: '02'
item_name: Subtle Relocation
keywords:
  - Magic
  - Ranged
  - Void
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.elementalist.1st-level-feature:subtle-relocation
scdc:
  - 1.1.1:11.2.9.1:02
source: mcdm.heroes.v1
subclass: Void
target: Self or one ally
type: feature/ability/elementalist/1st-level-feature
---

###### Subtle Relocation

*You call on the void to swallow and spit out an ally.*

| **Magic, Ranged, Void** |           **Triggered** |
| ----------------------- | ----------------------: |
| **📏 Ranged 10**        | **🎯 Self or one ally** |

**Trigger:** The target starts their turn, moves, or is force moved.

**Effect:** You teleport the target up to a number of squares equal to your Reason score. If the target moves to trigger this ability, you can teleport them at any point during the move.

**Spend 1 Essence:** You teleport the target up to a number of squares equal to twice your Reason score instead.

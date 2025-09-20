---
action_type: Triggered
class: fury
distance: Melee 1
feature_type: ability
file_basename: Lines of Force
file_dpath: Abilities/Fury/1st-Level Features
flavor: You redirect the energy of motion.
item_id: lines-of-force
item_index: '11'
item_name: Lines of Force
keywords:
  - Magic
  - Melee
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.fury.1st-level-feature:lines-of-force
scdc:
  - 1.1.1:11.2.5.1:11
source: mcdm.heroes.v1
subclass: Berserker
target: Self or one creature
type: feature/ability/fury/1st-level-feature
---

###### Lines of Force

*You redirect the energy of motion.*

| **Magic, Melee** |               **Triggered** |
| ---------------- | --------------------------: |
| **📏 Melee 1**   | **🎯 Self or one creature** |

**Trigger:** The target would be force moved.

**Effect:** You can select a new target of the same size or smaller within distance to be force moved instead. You become the source of the forced movement, determine the new target's destination, and can push the target instead of using the original forced movement type. Additionally, the forced movement distance gains a bonus equal to your Might score.

**Spend 1 Ferocity:** The forced movement distance gains a bonus equal to twice your Might score instead.

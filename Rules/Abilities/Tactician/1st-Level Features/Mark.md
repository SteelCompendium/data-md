---
action_type: Maneuver
class: tactician
distance: Ranged 10
feature_type: ability
file_basename: Mark
file_dpath: Abilities/Tactician/1st-Level Features
flavor: You draw your allies' attention to a specific foe—with devastating effect.
item_id: mark
item_index: '11'
item_name: Mark
keywords:
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.tactician.1st-level-feature:mark
scdc:
  - 1.1.1:11.2.4.1:11
source: mcdm.heroes.v1
target: One creature
type: feature/ability/tactician/1st-level-feature
---

###### Mark

*You draw your allies' attention to a specific foe—with devastating effect.*

| **Ranged**       |        **Maneuver** |
| ---------------- | ------------------: |
| **📏 Ranged 10** | **🎯 One creature** |

**Effect:** The target is marked by you until the end of the encounter, until you are dying, or until you use this ability again. You can willingly end your mark on a creature (no action required), and if another tactician marks a creature, your mark on that creature ends. When a creature marked by you is reduced to 0 Stamina, you can use a free triggered action to mark a new target within distance.

You can initially mark only one creature using this ability, though other tactician abilities allow you to mark additional creatures at the same time. The mastermind tactical doctrine's Anticipation feature allows you to target additional creatures with this ability starting at 5th level.

While a creature marked by you is within your line of effect, you and allies within your line of effect gain an edge on power rolls made against that creature. Additionally, whenever you or any ally uses an ability to deal rolled damage to a creature marked by you, you can spend 1 focus to gain one of the following benefits as a free triggered action:

- The ability deals extra damage equal to twice your Reason score.
- The creature dealing the damage can spend a Recovery.
- The creature dealing the damage can shift up to a number of squares equal to your Reason score.
- If you damage a creature marked by you with a melee ability, the creature is taunted by you until the end of their next turn.

You can't gain more than one benefit from the same trigger.

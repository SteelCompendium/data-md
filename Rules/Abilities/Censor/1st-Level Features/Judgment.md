---
action_type: Maneuver
class: censor
distance: Ranged 10
feature_type: ability
file_basename: Judgment
file_dpath: Abilities/Censor/1st-Level Features
flavor: You utter a prayer that outlines your foe in holy energy.
item_id: judgment
item_index: 09
item_name: Judgment
keywords:
  - Magic
  - Ranged
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.censor.1st-level-feature:judgment
scdc:
  - 1.1.1:11.2.7.1:09
source: mcdm.heroes.v1
target: One enemy
type: feature/ability/censor/1st-level-feature
---

###### Judgment

*You utter a prayer that outlines your foe in holy energy.*

| **Magic, Ranged** |     **Maneuver** |
| ----------------- | ---------------: |
| **📏 Ranged 10**  | **🎯 One enemy** |

**Effect:** The target is judged by you until the end of the encounter, you use this ability again, you willingly end this effect (no action required), or another censor judges the target.

Whenever a creature judged by you uses a main action and is within your line of effect, you can use a free triggered action to deal holy damage equal to twice your Presence score to them.

When a creature judged by you is reduced to 0 Stamina, you can use a free triggered action to use this ability against a new target.

Additionally, you can spend 1 wrath to take one of the following free triggered actions:

- When an adjacent creature judged by you starts to shift, you make a melee free strike against them and their speed becomes 0 until the end of the current turn, preventing them from shifting.
- When a creature judged by you within 10 squares makes a power roll, you cause them to take a bane on the roll.
- When a creature judged by you within 10 squares uses an ability with a potency that targets only one creature, the potency is reduced by 1 for that creature.
- If you damage a creature judged by you with a melee ability, the creature is taunted by you until the end of their next turn.

You can choose only one free triggered action option at a time, even if multiple options are triggered by the same effect.

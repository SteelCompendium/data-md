---
action_type: Triggered
class: tactician
cost: 5 Focus
cost_amount: 5
cost_resource: Focus
distance: Ranged 5
feature_type: ability
file_basename: No Dying on My Watch
file_dpath: Abilities/Tactician/2nd-Level Features
flavor: You prioritize saving an ally over your own safety.
item_id: no-dying-on-my-watch-5-focus
item_index: '02'
item_name: No Dying on My Watch (5 Focus)
keywords:
  - Ranged
  - Strike
  - Weapon
level: 2
scc:
  - mcdm.heroes.v1:feature.ability.tactician.2nd-level-feature:no-dying-on-my-watch-5-focus
scdc:
  - 1.1.1:11.2.4.5:02
source: mcdm.heroes.v1
subclass: Vanguard
target: One enemy
type: feature/ability/tactician/2nd-level-feature
---

###### No Dying on My Watch (5 Focus)

*You prioritize saving an ally over your own safety.*

| **Ranged, Strike, Weapon** |    **Triggered** |
| -------------------------- | ---------------: |
| **📏 Ranged 5**            | **🎯 One enemy** |

**Trigger:** The target deals damage to an ally.

**Effect:** You move up to your speed toward the triggering ally, ending this movement adjacent to them or in the nearest square if you can't reach an adjacent square. The triggering ally can spend a Recovery and gains 5 temporary Stamina for each enemy you came adjacent to during the move. You then make a power roll against the target.

**Power Roll + Might:**

- **≤11:** R < WEAK, the target is frightened of the triggering ally (save ends)
- **12-16:** R < AVERAGE, the target is frightened of the triggering ally (save ends)
- **17+:** R < STRONG, the target is frightened of the triggering ally (save ends)

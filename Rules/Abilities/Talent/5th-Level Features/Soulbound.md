---
action_type: Main action
class: talent
cost: 9 Clarity
cost_amount: 9
cost_resource: Clarity
distance: Ranged 10
feature_type: ability
file_basename: Soulbound
file_dpath: Abilities/Talent/5th-Level Features
flavor: You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.
item_id: soulbound-9-clarity
item_index: '03'
item_name: Soulbound (9 Clarity)
keywords:
  - Animapathy
  - Psionic
  - Ranged
  - Strike
level: 5
scc:
  - mcdm.heroes.v1:feature.ability.talent.5th-level-feature:soulbound-9-clarity
scdc:
  - 1.1.1:11.2.1.4:03
source: mcdm.heroes.v1
target: Two enemies
type: feature/ability/talent/5th-level-feature
---

###### Soulbound (9 Clarity)

*You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.*

| **Animapathy, Psionic, Ranged, Strike** |    **Main action** |
| --------------------------------------- | -----------------: |
| **📏 Ranged 10**                        | **🎯 Two enemies** |

**Power Roll + Presence:**

- **≤11:** 8 damage; A < WEAK, the target is stitched to the other target (save ends)
- **12-16:** 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
- **17+:** 17 damage; A < STRONG, the target is stitched to the other target (save ends)

**Effect:** If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a bane on power rolls while not adjacent to a creature they're stitched to. Whenever a stitched target takes damage that wasn't dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.

**Strained:** You target yourself and three enemies instead.

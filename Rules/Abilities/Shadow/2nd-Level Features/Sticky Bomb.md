---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: 5
cost_resource: Insight
distance: Ranged 10
feature_type: ability
file_basename: Sticky Bomb
file_dpath: Abilities/Shadow/2nd-Level Features
flavor: Explosives are best when they're attached to an enemy.
item_id: sticky-bomb-5-insight
item_index: '01'
item_name: Sticky Bomb (5 Insight)
keywords:
  - Ranged
level: 2
scc:
  - mcdm.heroes.v1:feature.ability.shadow.2nd-level-feature:sticky-bomb-5-insight
scdc:
  - 1.1.1:11.2.2.5:01
source: mcdm.heroes.v1
subclass: Caustic Alchemy
target: One creature
type: feature/ability/shadow/2nd-level-feature
---

###### Sticky Bomb (5 Insight)

*Explosives are best when they're attached to an enemy.*

| **Ranged**       |     **Main action** |
| ---------------- | ------------------: |
| **📏 Ranged 10** | **🎯 One creature** |

**Effect:** You attach a small bomb to a creature. If you are hidden from the creature, they don't notice the bomb and you remain hidden. The creature otherwise notices the bomb and can disarm and remove it as a main action. If they don't, at the end of your next turn, the bomb detonates. When the bomb detonates, you make a power roll targeting each enemy within 2 squares of it.

**Power Roll + Agility:**

- **≤11:** 4 + A fire damage
- **12-16:** 7 + A fire damage
- **17+:** 11 + A fire damage

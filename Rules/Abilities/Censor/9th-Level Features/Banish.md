---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: 11
cost_resource: Wrath
distance: Melee 1
feature_type: ability
file_basename: Banish
file_dpath: Abilities/Censor/9th-Level Features
flavor: You sever the target's tenuous connection to the world.
item_id: banish-11-wrath
item_index: '05'
item_name: Banish (11 Wrath)
keywords:
  - Melee
  - Strike
  - Weapon
level: 9
scc:
  - mcdm.heroes.v1:feature.ability.censor.9th-level-feature:banish-11-wrath
scdc:
  - 1.1.1:11.2.7.7:05
source: mcdm.heroes.v1
subclass: Exorcist
target: One creature
type: feature/ability/censor/9th-level-feature
---

###### Banish (11 Wrath)

*You sever the target's tenuous connection to the world.*

| **Melee, Strike, Weapon** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Melee 1**            | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 5 + M damage; P < WEAK, the target is banished (save ends)
- **12-16:** 8 + M damage; P < AVERAGE, the target is banished (save ends)
- **17+:** 11 + M damage; P < STRONG, the target is banished (save ends)

**Effect:** This ability gains an edge against demons, devils, undead, and creatures not native to your current world. If you know the target's true name, this ability has a double edge. While banished, the target is sent to another manifold in the timescape and removed from the encounter map. A banished target can do nothing but make saving throws, and takes 10 holy damage each time they do so. If the target is reduced to 0 Stamina while banished, they are lost to the timescape.

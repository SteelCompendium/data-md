---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: 9
cost_resource: Piety
distance: Ranged 10
feature_type: ability
file_basename: Beacon of Grace
file_dpath: Abilities/Conduit/4th-Level Features
flavor: You ignite a foe with holy radiance, rewarding allies who attack them.
item_id: beacon-of-grace-9-piety
item_index: '05'
item_name: Beacon of Grace (9 Piety)
keywords:
  - Magic
  - Ranged
  - Strike
level: 4
scc:
  - mcdm.heroes.v1:feature.ability.conduit.4th-level-feature:beacon-of-grace-9-piety
scdc:
  - 1.1.1:11.2.8.9:05
source: mcdm.heroes.v1
target: One creature
type: feature/ability/conduit/4th-level-feature
---

###### Beacon of Grace (9 Piety)

*You ignite a foe with holy radiance, rewarding allies who attack them.*

| **Magic, Ranged, Strike** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Ranged 10**          | **🎯 One creature** |

**Power Roll + Intuition:**

- **≤11:** 8 + I holy damage
- **12-16:** 13 + I holy damage
- **17+:** 17 + I holy damage

**Effect:** Until the end of the encounter, whenever you or any ally damages the target using an ability, that creature can spend a Recovery. If the target is reduced to 0 Stamina before the end of the encounter, you can use a free triggered action to move this effect to another creature within distance.

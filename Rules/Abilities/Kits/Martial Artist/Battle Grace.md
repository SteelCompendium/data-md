---
ability_type: Signature
action_type: Main action
class: ignored
distance: Melee 1
file_basename: Battle Grace
file_dpath: Abilities/Kits/Martial Artist
flavor: You feint to move your enemies into perfect position.
item_id: battle-grace
item_index: '01'
item_name: Battle Grace
keywords:
  - Melee
  - Strike
  - Weapon
scc:
  - mcdm.heroes.v1:kit-ability.martial-artist:battle-grace
scdc:
  - 1.1.1:14.16:01
source: mcdm.heroes.v1
target: One creature
type: kit-ability/martial-artist
---

###### Battle Grace

*You feint to move your enemies into perfect position.*

| **Melee, Strike, Weapon** |     **Main action** |
| ------------------------- | ------------------: |
| **📏 Melee 1**            | **🎯 One creature** |

**Power Roll + Might or Agility:**

- **≤11:** 5 + M or A damage
- **12-16:** 8 + M or A damage; you can swap places with the target
- **17+:** 11 + M or A damage; you can swap places with the target

**Effect:** If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.

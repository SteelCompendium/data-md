---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: 5
cost_resource: Wrath
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: Behold the Face of Justice
file_dpath: Abilities/Censor/1st-Level Features
flavor: You attack a foe and your enemies behold a vision of the true nature of your resolve.
item_id: behold-the-face-of-justice-5-wrath
item_index: '03'
item_name: Behold the Face of Justice! (5 Wrath)
keywords:
  - Magic
  - Melee
  - Ranged
  - Strike
  - Weapon
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.censor.1st-level-feature:behold-the-face-of-justice-5-wrath
scdc:
  - 1.1.1:11.2.7.1:03
source: mcdm.heroes.v1
target: One creature
type: feature/ability/censor/1st-level-feature
---

###### Behold the Face of Justice! (5 Wrath)

*You attack a foe and your enemies behold a vision of the true nature of your resolve.*

| **Magic, Melee, Ranged, Strike, Weapon** |     **Main action** |
| ---------------------------------------- | ------------------: |
| **📏 Melee 1 or ranged 5**               | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 3 + M holy damage; if the target has P < WEAK, each enemy within 2 squares of them is frightened of you (save ends)
- **12-16:** 5 + M holy damage; if the target has P < AVERAGE, each enemy within 2 squares of them is frightened of you (save ends)
- **17+:** 8 + M holy damage; if the target has P < STRONG, each enemy within 2 squares of them is frightened of you (save ends)

**Effect:** Each enemy frightened this way is pushed up to 2 squares away from the target and takes psychic damage equal to your Presence score.

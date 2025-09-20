---
action_type: Main action
class: talent
cost: 3 Clarity
cost_amount: 3
cost_resource: Clarity
distance: Ranged 10
feature_type: ability
file_basename: Awe
file_dpath: Abilities/Talent/1st-Level Features
flavor: You project psionic energy out to a creature and take on a new visage in their mind.
item_id: awe-3-clarity
item_index: '17'
item_name: Awe (3 Clarity)
keywords:
  - Psionic
  - Ranged
  - Strike
  - Telepathy
level: 1
scc:
  - mcdm.heroes.v1:feature.ability.talent.1st-level-feature:awe-3-clarity
scdc:
  - 1.1.1:11.2.1.1:17
source: mcdm.heroes.v1
target: One creature
type: feature/ability/talent/1st-level-feature
---

###### Awe (3 Clarity)

*You project psionic energy out to a creature and take on a new visage in their mind.*

| **Psionic, Ranged, Strike, Telepathy** |     **Main action** |
| -------------------------------------- | ------------------: |
| **📏 Ranged 10**                       | **🎯 One creature** |

**Effect:** If you target an ally, they gain temporary Stamina equal to three times your Presence score, and they can end one effect on them that is ended by a saving throw or that ends at the end of their turn. If you target an enemy, you make a power roll.

**Power Roll + Presence:**

- **≤11:** 3 + P psychic damage; I < WEAK, frightened (save ends)
- **12-16:** 6 + P psychic damage; I < AVERAGE, frightened (save ends)
- **17+:** 9 + P psychic damage; I < STRONG, frightened (save ends)

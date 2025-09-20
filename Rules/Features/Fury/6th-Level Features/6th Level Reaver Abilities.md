---
action_type: feature
class: fury
feature_type: trait
file_basename: 6th Level Reaver Abilities
file_dpath: Fury/6th-Level Features
item_id: 6th-level-reaver-abilities
item_index: '06'
item_name: 6th-Level Reaver Abilities
level: 6
scc:
  - mcdm.heroes.v1:feature.trait.fury.6th-level-feature:6th-level-reaver-abilities
scdc:
  - 1.1.1:11.1.5.3:06
source: mcdm.heroes.v1
type: feature/trait/fury/6th-level-feature
---

##### 6th-Level Reaver Abilities

Choose one of the following abilities.

<!-- -->
> ###### Death Strike (9 Ferocity)
>
> *Once you taste your foe's blood, you become more efficient and turn every killing blow into an opportunity.*
>
> | **Melee, Strike, Weapon** | **Free triggered** |
> | ------------------------- | -----------------: |
> | **📏 Melee 1**            |        **🎯 Self** |
>
> **Trigger:** You reduce a creature to 0 Stamina with a strike.
>
> **Effect:** You target a creature adjacent to you with the same strike, using the same power roll as the triggering strike.

<!-- -->
> ###### Seek and Destroy (9 Ferocity)
>
> *You break through the enemy lines to make an example.*
>
> | **Melee, Strike, Weapon** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Effect:** You shift up to your speed.
>
> **Power Roll + Might:**
>
> - **≤11:** 4 + M damage; P < WEAK, frightened (save ends)
> - **12-16:** 6 + M damage; P < AVERAGE, frightened (save ends)
> - **17+:** 10 + M damage; P < STRONG, frightened (save ends)
>
> **Effect:** If a target who is not a leader or solo creature is winded by this strike, they are reduced to 0 Stamina and you choose an enemy within 5 squares of you. If that enemy has P < AVERAGE, they are frightened of you (save ends).

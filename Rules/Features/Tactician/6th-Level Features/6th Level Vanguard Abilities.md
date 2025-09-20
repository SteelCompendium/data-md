---
action_type: feature
class: tactician
feature_type: trait
file_basename: 6th Level Vanguard Abilities
file_dpath: Tactician/6th-Level Features
item_id: 6th-level-vanguard-abilities
item_index: '02'
item_name: 6th-Level Vanguard Abilities
level: 6
scc:
  - mcdm.heroes.v1:feature.trait.tactician.6th-level-feature:6th-level-vanguard-abilities
scdc:
  - 1.1.1:11.1.4.3:02
source: mcdm.heroes.v1
type: feature/trait/tactician/6th-level-feature
---

##### 6th-Level Vanguard Abilities

Choose one of the following abilities.

<!-- -->
> ###### Instant Retaliation (9 Focus)
>
> *You parry with almost supernatural speed.*
>
> | **Melee, Weapon** | **Free triggered** |
> | ----------------- | -----------------: |
> | **📏 Melee 1**    |    **🎯 One ally** |
>
> **Trigger:** A creature deals damage to the target.
>
> **Effect:** The target takes half the damage. You then make a power roll against the triggering creature.
>
> **Power Roll + Might:**
>
> - **≤11:** A < WEAK, dazed (save ends)
> - **12-16:** A < AVERAGE, dazed (save ends)
> - **17+:** A < STRONG, dazed (save ends)

<!-- -->
> ###### To Me Squad! (9 Focus)
>
> *You lead your allies in a charge.*
>
> | **Charge, Melee, Strike, Weapon** |     **Main action** |
> | --------------------------------- | ------------------: |
> | **📏 Melee 1**                    | **🎯 One creature** |
>
> **Power Roll + Might:**
>
> - **≤11:** 6 + M damage; one ally within 10 squares can use the Charge main action as a free triggered action, and can use a melee strike signature ability instead of a free strike for the charge
> - **12-16:** 9 + M damage; one ally within 10 squares can use the Charge main action as a free triggered action, and can use a melee strike signature ability that gains an edge instead of a free strike for the charge
> - **17+:** 13 + M damage; two allies within 10 squares can use the Charge main action as a free triggered action, and can each use a melee strike signature ability that gains an edge instead of a free strike for the charge
>
> **Effect:** If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are dazed (save ends). If the target is reduced to 0 Stamina before one or both allies has made their strike, the ally or allies can pick a different target.

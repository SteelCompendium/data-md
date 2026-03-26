---
action_type: feature
class: tactician
feature_type: trait
file_basename: Doctrine Triggered Action
file_dpath: Features/Tactician/1st-Level Features
item_id: doctrine-triggered-action
item_index: '03'
item_name: Doctrine Triggered Action
level: 1
scc:
  - mcdm.heroes.v1:feature.trait.tactician.1st-level-feature:doctrine-triggered-action
scdc:
  - 1.1.1:11.1.4.1:03
source: mcdm.heroes.v1
type: feature/trait/tactician/1st-level-feature
---

#### Doctrine Triggered Action

Your tactical doctrine grants you a triggered action, as shown on the Doctrine Triggered Actions table.

###### Doctrine Triggered Actions Table

| Doctrine   | Triggered Action |
| ---------- | ---------------- |
| Insurgent  | Advanced Tactics |
| Mastermind | Overwatch        |
| Vanguard   | Parry            |

<!-- -->
> ###### Advanced Tactics
>
> *Your leadership aids an ally.*
>
> | **Ranged**       |   **Triggered** |
> | ---------------- | --------------: |
> | **📏 Ranged 10** | **🎯 One ally** |
>
> **Trigger:** The target deals damage to another creature.
>
> **Effect:** The target gains 2 surges, which they can use on the triggering damage.
>
> **Spend 1 Focus:** If the damage has any potency effect associated with it, the potency is increased by 1.

<!-- -->
> ###### Overwatch
>
> *Under your direction, an ally waits for just the right moment to strike.*
>
> | **Ranged**       |       **Triggered** |
> | ---------------- | ------------------: |
> | **📏 Ranged 10** | **🎯 One creature** |
>
> **Trigger:** The target moves.
>
> **Effect:** At any time during the target's movement, one ally can make a free strike against them.
>
> **Spend 1 Focus:** If the target has R < AVERAGE, they are slowed (EoT).

<!-- -->
> ###### Parry
>
> *Your quick reflexes cost an enemy the precision they seek.*
>
> | **Melee, Weapon** |           **Triggered** |
> | ----------------- | ----------------------: |
> | **📏 Melee 2**    | **🎯 Self or one ally** |
>
> **Trigger:** A creature deals damage to the target.
>
> **Effect:** You can shift 1 square. If the target is you, or if you end this shift adjacent to the target, the target takes half the damage. If the damage has any potency effect associated with it, the potency is decreased by 1.
>
> **Spend 1 Focus:** This ability's distance becomes Melee 1 + your Reason score, and you can shift up to a number of squares equal to your Reason score instead of 1 square.

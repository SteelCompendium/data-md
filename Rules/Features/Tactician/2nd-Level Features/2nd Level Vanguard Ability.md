---
action_type: feature
class: tactician
feature_type: trait
file_basename: 2nd Level Vanguard Ability
file_dpath: Tactician/2nd-Level Features
item_id: 2nd-level-vanguard-ability
item_index: '05'
item_name: 2nd-Level Vanguard Ability
level: 2
scc:
  - mcdm.heroes.v1:feature.trait.tactician.2nd-level-feature:2nd-level-vanguard-ability
scdc:
  - 1.1.1:11.1.4.6:05
source: mcdm.heroes.v1
type: feature/trait/tactician/2nd-level-feature
---

##### 2nd-Level Vanguard Ability

Choose one of the following abilities.

<!-- -->
> ###### No Dying on My Watch (5 Focus)
>
> *You prioritize saving an ally over your own safety.*
>
> | **Ranged, Strike, Weapon** |    **Triggered** |
> | -------------------------- | ---------------: |
> | **📏 Ranged 5**            | **🎯 One enemy** |
>
> **Trigger:** The target deals damage to an ally.
>
> **Effect:** You move up to your speed toward the triggering ally, ending this movement adjacent to them or in the nearest square if you can't reach an adjacent square. The triggering ally can spend a Recovery and gains 5 temporary Stamina for each enemy you came adjacent to during the move. You then make a power roll against the target.
>
> **Power Roll + Might:**
>
> - **≤11:** R < WEAK, the target is frightened of the triggering ally (save ends)
> - **12-16:** R < AVERAGE, the target is frightened of the triggering ally (save ends)
> - **17+:** R < STRONG, the target is frightened of the triggering ally (save ends)

<!-- -->
> ###### Squad! On Me! (5 Focus)
>
> *Together we are invincible!*
>
> | **Area**       |                          **Maneuver** |
> | -------------- | ------------------------------------: |
> | **📏 1 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Until the start of your next turn, each target has a bonus to stability equal to your Might score. Additionally, each target gains 2 surges.

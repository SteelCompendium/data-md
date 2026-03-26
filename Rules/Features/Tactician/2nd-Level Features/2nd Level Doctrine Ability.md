---
action_type: feature
class: tactician
feature_type: trait
file_basename: 2nd Level Doctrine Ability
file_dpath: Tactician/2nd-Level Features
item_id: 2nd-level-doctrine-ability
item_index: '01'
item_name: 2nd-Level Doctrine Ability
level: 2
scc:
  - mcdm.heroes.v1:feature.trait.tactician.2nd-level-feature:2nd-level-doctrine-ability
scdc:
  - 1.1.1:11.1.4.6:01
source: mcdm.heroes.v1
type: feature/trait/tactician/2nd-level-feature
---

#### 2nd-Level Doctrine Ability

Your tactical doctrine grants your choice of one of two heroic abilities.

##### 2nd-Level Insurgent Ability

Choose one of the following abilities.

<!-- -->
> ###### Fog of War (5 Focus)
>
> *Your unorthodox strategy causes enemies to lash out in fear, heedless of who they might be attacking.*
>
> | **Ranged**       |         **Maneuver** |
> | ---------------- | -------------------: |
> | **📏 Ranged 10** | **🎯 Two creatures** |
>
> **Effect:** Each target is marked by you, and must immediately make a free strike against a creature of your choice within 5 squares of them.
>
> **Mark Benefit:** Until the end of the encounter, whenever you or any ally makes a strike against a creature marked by you, you can spend 2 focus to force that target to make a free strike against a creature of your choice within 5 squares of them.

<!-- -->
> ###### Try Me Instead (5 Focus)
>
> *"Try picking on someone my size."*
>
> | **Melee, Strike, Weapon** | **Main action** |
> | ------------------------- | --------------: |
> | **📏 Self; see below**    |     **🎯 Self** |
>
> **Effect:** You shift up to your speed directly toward an ally, ending adjacent to them, then swapping locations with that ally as long as you can fit into each other's spaces. The ally can spend a Recovery, and you can make the following weapon strike with a distance of melee 1 against a creature.
>
> **Power Roll + Reason:**
>
> - **≤11:** 2 + R damage; R < WEAK, frightened (save ends)
> - **12-16:** 3 + R damage; R < AVERAGE, frightened (save ends)
> - **17+:** 4 + R damage; R < STRONG, frightened (save ends)

##### 2nd-Level Mastermind Ability

Choose one of the following abilities.

<!-- -->
> ###### I've Got Your Back (5 Focus)
>
> *Your enemy will think twice about attacking your friend.*
>
> | **Ranged, Strike, Weapon** |     **Main action** |
> | -------------------------- | ------------------: |
> | **📏 Ranged 5**            | **🎯 One creature** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 5 + R damage; taunted (EoT)
> - **12-16:** 9 + R damage; taunted (EoT)
> - **17+:** 12 + R damage; taunted (EoT)
>
> **Effect:** One ally adjacent to the target can spend a Recovery.

<!-- -->
> ###### Targets of Opportunity (5 Focus)
>
> *You point out easy targets to your friends, allowing them to include more enemies in their attacks.*
>
> | **Ranged**      |         **Maneuver** |
> | --------------- | -------------------: |
> | **📏 Ranged 5** | **🎯 Two creatures** |
>
> **Effect:** Each target is marked by you, and you gain two surges.
>
> **Mark Benefit:** Until the end of the encounter, whenever you or any ally makes a strike against a creature marked by you, you can spend 2 focus to add one additional target to the strike.

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

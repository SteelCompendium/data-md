---
action_type: feature
class: talent
feature_type: subtrait
file_basename: Heroic Abilities
file_dpath: Features/Talent/1st-Level Features/Talent Abilities
item_id: heroic-abilities
item_index: '02'
item_name: Heroic Abilities
level: 1
scc:
  - mcdm.heroes.v1:feature.subtrait.talent.1st-level-feature:heroic-abilities
scdc:
  - 1.1.1:11.2.1.6:02
source: mcdm.heroes.v1
type: feature/subtrait/talent/1st-level-feature
---

##### Heroic Abilities

You know a range of heroic abilities, all of which cost clarity to fuel them.

###### 3-Clarity Ability

Choose one heroic ability from the following options, each of which costs 3 clarity to use. (*Quick Build:* Choke.)

<!-- -->
> ###### Awe (3 Clarity)
>
> *You project psionic energy out to a creature and take on a new visage in their mind.*
>
> | **Psionic, Ranged, Strike, Telepathy** |     **Main action** |
> | -------------------------------------- | ------------------: |
> | **📏 Ranged 10**                       | **🎯 One creature** |
>
> **Effect:** If you target an ally, they gain temporary Stamina equal to three times your Presence score, and they can end one effect on them that is ended by a saving throw or that ends at the end of their turn. If you target an enemy, you make a power roll.
>
> **Power Roll + Presence:**
>
> - **≤11:** 3 + P psychic damage; I < WEAK, frightened (save ends)
> - **12-16:** 6 + P psychic damage; I < AVERAGE, frightened (save ends)
> - **17+:** 9 + P psychic damage; I < STRONG, frightened (save ends)

<!-- -->
> ###### Choke (3 Clarity)
>
> *You crush a foe in a telekinetic grip.*
>
> | **Psionic, Ranged**, **Strike, Telekinesis** |     **Main action** |
> | -------------------------------------------- | ------------------: |
> | **📏 Ranged 10**                             | **🎯 One creature** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 3 + R damage; M < WEAK, slowed (save ends)
> - **12-16:** 5 + R damage; M < AVERAGE, slowed (save ends)
> - **17+:** 8 + R damage; M < STRONG, restrained (save ends)
>
> **Effect:** You can vertical pull the target up to 2 squares. If the target is made restrained by this ability, this forced movement ignores their stability.

<!-- -->
> ###### Precognition (3 Clarity)
>
> *You give a target a glimpse into the future so that they're ready for what comes next.*
>
> | **Chronopathy, Melee, Psionic** |         **Main action** |
> | ------------------------------- | ----------------------: |
> | **📏 Melee 2**                  | **🎯 Self or one ally** |
>
> **Effect:** Ability rolls made against the target take a bane until the start of your next turn. Whenever the target takes damage while under this effect, they can use a triggered action to make a free strike against the source of the damage.

<!-- -->
> ###### Smolder (3 Clarity)
>
> *Smoke flows from your enemy like tears as their skin begins to blacken and flake.*
>
> | **Psionic, Pyrokinesis, Ranged, Strike** |     **Main action** |
> | ---------------------------------------- | ------------------: |
> | **📏 Ranged 10**                         | **🎯 One creature** |
>
> **Effect:** Choose the damage type and the weakness for this ability from one of the following: acid, corruption, or fire. The target takes damage before this ability imposes any weakness.
>
> **Power Roll + Reason:**
>
> - **≤11:** 3 + R damage; R < WEAK, the target has weakness 5 (save ends)
> - **12-16:** 6 + R damage; R < AVERAGE, the target has weakness 5 (save ends)
> - **17+:** 9 + R damage; R < STRONG, the target has weakness equal to 5 + your Reason score (save ends)

###### 5-Clarity Ability

Choose one heroic ability from the following options, each of which costs 5 clarity to use. (*Quick Build:* Inertia Soak.)

<!-- -->
> ###### Flashback (5 Clarity)
>
> *The target is thrown several seconds back through time and gets to do it all again.*
>
> | **Chronopathy, Psionic, Ranged** |            **Maneuver** |
> | -------------------------------- | ----------------------: |
> | **📏 Ranged 10**                 | **🎯 Self or one ally** |
>
> **Effect:** The target uses an ability with a base Heroic Resource cost of 7 or lower that they've previously used this round, without needing to spend the base cost. Augmentations to the ability can be paid for as usual.
>
> **Strained:** You take 1d6 damage and are slowed (save ends).

<!-- -->
> ###### Inertia Soak (5 Clarity)
>
> *Your psionic energy surrounds the target and pushes everything else away from them.*
>
> | **Psionic, Ranged, Telekinesis** |            **Maneuver** |
> | -------------------------------- | ----------------------: |
> | **📏 Ranged 10**                 | **🎯 Self or one ally** |
>
> **Effect:** The target ignores difficult terrain and takes no damage from forced movement until the start of your next turn. Whenever the target enters a square while under this effect, they can push one adjacent creature up to a number of squares equal to your Reason score. When pushing an ally, the target can ignore that ally's stability. A creature can only be force moved this way once a turn.
>
> **Strained:** You are weakened (save ends). While you are weakened this way, whenever you are force moved, the forced movement distance gains a +5 bonus.

<!-- -->
> ###### Iron (5 Clarity)
>
> *The target's skin turns to hard, dark metal, impenetrable and dense.*
>
> | **Metamorphosis, Psionic, Ranged** |            **Maneuver** |
> | ---------------------------------- | ----------------------: |
> | **📏 Ranged 10**                   | **🎯 Self or one ally** |
>
> **Effect:** The target's stability increases by an amount equal to your Reason score, and they gain 10 temporary Stamina and 2 surges. This stability increase lasts until the target no longer has temporary Stamina from this ability.
>
> **Strained:** You can't use maneuvers (save ends).

<!-- -->
> ###### Perfect Clarity (5 Clarity)
>
> *You clear the mind of nothing but the goal.*
>
> | **Psionic, Ranged, Telepathy** |            **Maneuver** |
> | ------------------------------ | ----------------------: |
> | **📏 Ranged 10**               | **🎯 Self or one ally** |
>
> **Effect:** Until the start of your next turn, the target gains a +3 bonus to speed, and they have a double edge on the next power roll they make. If the target obtains a tier 3 outcome on that roll, you gain 1 clarity.
>
> **Strained:** You take 1d6 damage, and you can't use triggered actions (save ends).

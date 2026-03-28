---
action_type: feature
class: talent
feature_type: trait
file_basename: 2nd Level Tradition Ability
file_dpath: Features/Talent/2nd-Level Features
item_id: 2nd-level-tradition-ability
item_index: '01'
item_name: 2nd-Level Tradition Ability
level: 2
scc:
  - mcdm.heroes.v1:feature.trait.talent.2nd-level-feature:2nd-level-tradition-ability
scdc:
  - 1.1.1:11.1.1.6:01
source: mcdm.heroes.v1
type: feature/trait/talent/2nd-level-feature
---

#### 2nd-Level Tradition Ability

Your talent tradition grants your choice of one of two heroic abilities.

##### 2nd-Level Chronopathy Ability

Choose one of the following abilities.

<!-- -->
> ###### Applied Chronometrics (5 Clarity)
>
> *Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.*
>
> | **Chronopathy, Psionic, Ranged** |   **Maneuver** |
> | -------------------------------- | -------------: |
> | **📏 Ranged 10**                 | **🎯 Special** |
>
> **Power Roll + Presence:**
>
> - **≤11:** You target two creatures, one of which can be you.
> - **12-16:** You target three creatures, one of which can be you.
> - **17+:** You target four creatures, one of which can be you.
>
> **Effect:** Until the start of your next turn, each target gains a +5 bonus to speed, they can't be made dazed, and they can use an additional maneuver on their turn. If a target is already dazed, that condition ends for them.
>
> **Strained:** Your speed is halved until the end of the encounter.

<!-- -->
> ###### Slow (5 Clarity)
>
> *Perhaps they wonder why everyone else is moving so quickly?*
>
> | **Chronopathy, Psionic, Ranged** |                      **Maneuver** |
> | -------------------------------- | --------------------------------: |
> | **📏 Ranged 10**                 | **🎯 Three creatures or objects** |
>
> **Power Roll + Presence:**
>
> - **≤11:** The target's speed is halved (save ends), or if P < WEAK, the target is slowed (save ends).
> - **12-16:** The target is slowed (save ends), or if P < AVERAGE, the target's speed is 0 (save ends).
> - **17+:** The target is slowed (save ends), or if P < STRONG, the target's speed is 0 (save ends).
>
> **Effect:** A target can't use triggered actions while their speed is reduced this way.
>
> **Strained:** The potency of this ability increases by 1 and you take 1d6 damage. At the start of each combat round while any target is affected by this ability, you take 1d6 damage. You can end the effect on all affected targets at any time (no action required).

##### 2nd-Level Telekinesis Ability

Choose one of the following abilities.

<!-- -->
> ###### Gravitic Burst (5 Clarity)
>
> *Everyone get away from me!*
>
> | **Area, Psionic, Telekinesis** |               **Main action** |
> | ------------------------------ | ----------------------------: |
> | **📏 1 burst**                 | **🎯 Each enemy in the area** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 3 damage; vertical push 2
> - **12-16:** 6 damage; vertical push 4
> - **17+:** 9 damage; vertical push 6
>
> **Strained:** The size of the burst increases by 1, and you are weakened until the end of your turn.

<!-- -->
> ###### Levity and Gravity (5 Clarity)
>
> *You raise the target slightly into the air, then smother them against the ground.*
>
> | **Psionic, Ranged, Strike, Telekinesis** |               **Main action** |
> | ---------------------------------------- | ----------------------------: |
> | **📏 Ranged 10**                         | **🎯 One creature or object** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 6 + R damage; M < WEAK, prone
> - **12-16:** 10 + R damage; M < AVERAGE, prone
> - **17+:** 14 + R damage; M < STRONG, prone and can't stand (save ends)
>
> **Strained:** You take half the damage the target takes.

##### 2nd-Level Telepathy Ability

Choose one of the following abilities.

<!-- -->
> ###### Overwhelm (5 Clarity)
>
> *You overload their senses, turning all their subconscious thoughts into conscious ones.*
>
> | **Psionic, Ranged, Strike, Telepathy** |     **Main action** |
> | -------------------------------------- | ------------------: |
> | **📏 Ranged 10**                       | **🎯 One creature** |
>
> **Power Roll + Reason:**
>
> - **≤11:** 6 + R psychic damage; I < WEAK, slowed (save ends)
> - **12-16:** 10 + R psychic damage; I < AVERAGE, weakened (save ends)
> - **17+:** 14 + R psychic damage; I < STRONG, dazed (save ends)
>
> **Strained:** You start crying, and you can't use triggered actions or make free strikes until the end of the target's next turn.

<!-- -->
> ###### Synaptic Override (5 Clarity)
>
> *You control an enemy's nervous system. How pleasant for them.*
>
> | **Psionic, Ranged, Telepathy** |  **Main action** |
> | ------------------------------ | ---------------: |
> | **📏 Ranged 10**               | **🎯 One enemy** |
>
> **Power Roll + Reason:**
>
> - **≤11:** The target makes a free strike against one enemy of your choice.
> - **12-16:** The target shifts up to their speed and uses their signature ability against any enemies of your choice.
> - **17+:** The target moves up to their speed and uses their signature ability against any enemies of your choice.
>
> **Effect:** You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them dying, or result in them suffering a condition or other negative effect. However, you can move them to provoke opportunity attacks.
>
> **Strained:** You take 1d6 damage and are weakened until the end of your turn.

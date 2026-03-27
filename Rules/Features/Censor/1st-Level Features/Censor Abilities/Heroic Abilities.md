---
action_type: feature
class: censor
feature_type: trait
file_basename: Heroic Abilities
file_dpath: Censor/1st-Level Features/Censor Abilities
item_id: heroic-abilities
item_index: '16'
item_name: Heroic Abilities
level: 1
scc:
  - mcdm.heroes.v1:subfeature.trait.censor.1st-level-feature:heroic-abilities
scdc:
  - 1.1.1:12.1.7.8:16
source: mcdm.heroes.v1
type: subfeature/trait/censor/1st-level-feature
---

##### Heroic Abilities

You call upon a number of heroic abilities, all of them bound to your wrath.

###### 3-Wrath Ability

Choose one heroic ability from the following options, each of which costs 3 wrath to use. (*Quick Build:* The Gods Punish and Defend.)

<!-- -->
> ###### Behold a Shield of Faith! (3 Wrath)
>
> *A mighty blow turns your foe's vitality into a holy light that envelops you and an ally, discouraging enemies who might attack you.*
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + Might:**
>
> - **≤11:** 3 + M holy damage
> - **12-16:** 6 + M holy damage
> - **17+:** 9 + M holy damage
>
> **Effect:** Until the start of your next turn, enemies take a bane on ability rolls made against you or any ally adjacent to you.

<!-- -->
> ###### Driving Assault (3 Wrath)
>
> *As you force your enemy back with your weapon, you use your faith to stay close.*
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + Might:**
>
> - **≤11:** 3 + M damage; push 1
> - **12-16:** 6 + M damage; push 3
> - **17+:** 9 + M damage; push 5
>
> **Effect:** You can shift up to your speed in a straight line toward the target after pushing them.

<!-- -->
> ###### The Gods Punish and Defend (3 Wrath)
>
> *You channel holy energy to smite a foe and heal an ally.*
>
> | **Magic, Melee, Strike, Weapon** |               **Main action** |
> | -------------------------------- | ----------------------------: |
> | **📏 Melee 1**                   | **🎯 One creature or object** |
>
> **Power Roll + Might:**
>
> - **≤11:** 5 + M holy damage
> - **12-16:** 8 + M holy damage
> - **17+:** 11 + M holy damage
>
> **Effect:** You can spend a Recovery to allow yourself or one ally within 10 squares to regain Stamina equal to your recovery value.

<!-- -->
> ###### Repent! (3 Wrath)
>
> *You conjure memories of their sins to harry your foes.*
>
> | **Magic, Ranged, Strike** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + Presence:**
>
> - **≤11:** 5 + P holy damage; I < WEAK, dazed (save ends)
> - **12-16:** 8 + P holy damage; I < AVERAGE, dazed (save ends)
> - **17+:** 11 + P holy damage; I < STRONG, dazed (save ends)

###### 5-Wrath Ability

Choose one heroic ability from the following options, each of which costs 5 wrath to use. (*Quick Build:* Purifying Fire.)

<!-- -->
> ###### Arrest (5 Wrath)
>
> *"I got you, you son of a bitch."*
>
> | **Magic, Melee, Strike, Weapon** |     **Main action** |
> | -------------------------------- | ------------------: |
> | **📏 Melee 1**                   | **🎯 One creature** |
>
> **Power Roll + Might:**
>
> - **≤11:** 6 + M holy damage; grabbed
> - **12-16:** 9 + M holy damage; grabbed
> - **17+:** 13 + M holy damage; grabbed
>
> **Effect:** If the target makes a strike against a creature while grabbed this way, you can spend 3 wrath to deal holy damage to them equal to your Presence score, then change the target of the strike to another target within the strike's distance.

<!-- -->
> ###### Behold the Face of Justice! (5 Wrath)
>
> *You attack a foe and your enemies behold a vision of the true nature of your resolve.*
>
> | **Magic, Melee, Ranged, Strike, Weapon** |     **Main action** |
> | ---------------------------------------- | ------------------: |
> | **📏 Melee 1 or ranged 5**               | **🎯 One creature** |
>
> **Power Roll + Might:**
>
> - **≤11:** 3 + M holy damage; if the target has P < WEAK, each enemy within 2 squares of them is frightened of you (save ends)
> - **12-16:** 5 + M holy damage; if the target has P < AVERAGE, each enemy within 2 squares of them is frightened of you (save ends)
> - **17+:** 8 + M holy damage; if the target has P < STRONG, each enemy within 2 squares of them is frightened of you (save ends)
>
> **Effect:** Each enemy frightened this way is pushed up to 2 squares away from the target and takes psychic damage equal to your Presence score.

<!-- -->
> ###### Censored (5 Wrath)
>
> *Judged and sentenced.*
>
> | **Melee, Strike, Weapon** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + Might:**
>
> - **≤11:** 2 + M holy damage
> - **12-16:** 3 + M holy damage
> - **17+:** 5 + M holy damage
>
> **Effect:** When a target who is not a leader or solo creature is made winded by this ability, they are reduced to 0 Stamina.

<!-- -->
> ###### Purifying Fire (5 Wrath)
>
> *The gods judge, fire cleanses.*
>
> | **Magic, Melee, Ranged, Strike, Weapon** |     **Main action** |
> | ---------------------------------------- | ------------------: |
> | **📏 Melee 1 or ranged 5**               | **🎯 One creature** |
>
> **Power Roll + Might:**
>
> - **≤11:** 5 + M holy damage; M < WEAK, the target has fire weakness 3 (save ends)
> - **12-16:** 9 + M holy damage; M < AVERAGE, the target has fire weakness 5 (save ends)
> - **17+:** 12 + M holy damage; M < STRONG, the target has fire weakness 7 (save ends)
>
> **Effect:** While the target has fire weakness from this ability, you can choose to have your abilities deal fire damage to the target instead of holy damage.

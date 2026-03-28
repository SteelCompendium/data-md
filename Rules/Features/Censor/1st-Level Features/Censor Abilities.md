---
action_type: feature
class: censor
feature_type: trait
file_basename: Censor Abilities
file_dpath: Features/Censor/1st-Level Features
item_id: censor-abilities
item_index: '06'
item_name: Censor Abilities
level: 1
scc:
  - mcdm.heroes.v1:feature.trait.censor.1st-level-feature:censor-abilities
scdc:
  - 1.1.1:11.1.7.1:06
source: mcdm.heroes.v1
type: feature/trait/censor/1st-level-feature
---

#### Censor Abilities

You use a blend of martial techniques and divine magic to attack your foes and defend your allies.

##### Signature Ability

Choose one signature ability from the following options. Signature abilities can be used at will. (*Quick Build:* Your Allies Cannot Save You!)

<!-- -->
> ###### Back Blasphemer!
>
> *You channel power through your weapon to repel foes.*
>
> | **Area, Magic, Melee, Weapon** |               **Main action** |
> | ------------------------------ | ----------------------------: |
> | **📏 2 cube within 1**         | **🎯 Each enemy in the area** |
>
> **Power Roll + Presence:**
>
> - **≤11:** 2 holy damage; push 1
> - **12-16:** 4 holy damage; push 2
> - **17+:** 6 holy damage; push 3

<!-- -->
> ###### Every Step... Death!
>
> *You show your foe a glimpse of their fate after death.*
>
> | **Magic, Ranged, Strike** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + Presence:**
>
> - **≤11:** 5 + P psychic damage
> - **12-16:** 7 + P psychic damage
> - **17+:** 10 + P psychic damage
>
> **Effect:** Each time the target willingly moves before the end of your next turn, they take 1 psychic damage for each square they move.

<!-- -->
> ###### Halt Miscreant!
>
> *You infuse your weapon with holy magic that makes it difficult for your foe to get away.*
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + Might:**
>
> - **≤11:** 2 + M holy damage; P < WEAK, slowed (save ends)
> - **12-16:** 5 + M holy damage; P < AVERAGE, slowed (save ends)
> - **17+:** 7 + M holy damage; P < STRONG, slowed (save ends)

<!-- -->
> ###### Your Allies Cannot Save You!
>
> *Your magic strike turns your foe's guilt into a burst of holy power.*
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + Might:**
>
> - **≤11:** 3 + M holy damage
> - **12-16:** 5 + M holy damage
> - **17+:** 8 + M holy damage
>
> **Effect:** Each enemy adjacent to the target is pushed away from the target up to a number of squares equal to your Presence score.

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

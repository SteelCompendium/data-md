---
action_type: feature
class: conduit
feature_type: trait
file_basename: Conduit Abilities
file_dpath: Conduit/1st-Level Features
item_id: conduit-abilities
item_index: '02'
item_name: Conduit Abilities
level: 1
scc:
  - mcdm.heroes.v1:feature.trait.conduit.1st-level-feature:conduit-abilities
scdc:
  - 1.1.1:11.1.8.1:02
source: mcdm.heroes.v1
type: feature/trait/conduit/1st-level-feature
---

#### Conduit Abilities

Your training and faith let you specialize in magic that buffs your allies, debuffs your foes, and allows you to hold your own in combat alongside your friends.

##### Signature Abilities

Choose two signature abilities from the following options. Signature abilities can be used at will. (*Quick Build:* Blessed Light, Staggering Curse.)

<!-- -->
> ###### Blessed Light
>
> *Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.*
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I holy damage
> - **12-16:** 5 + I holy damage
> - **17+:** 8 + I holy damage
>
> **Effect:** One ally within distance gains a number of surges equal to the tier outcome of your power roll.

<!-- -->
> ###### Drain
>
> *You drain the energy from your target to revitalize yourself or an ally.*
>
> | **Magic, Melee, Strike** |     **Main action** |
> | ------------------------ | ------------------: |
> | **📏 Melee 1**           | **🎯 One creature** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 2 + I corruption damage
> - **12-16:** 5 + I corruption damage
> - **17+:** 7 + I corruption damage
>
> **Effect:** You or one ally within distance can spend a Recovery.

<!-- -->
> ###### Holy Lash
>
> *A tendril of divine energy shoots forth to draw in your foe.*
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I holy damage; vertical pull 2
> - **12-16:** 5 + I holy damage; vertical pull 3
> - **17+:** 8 + I holy damage; vertical pull 4

<!-- -->
> ###### Lightfall
>
> *A rain of holy light scours your enemies and repositions your allies.*
>
> | **Area, Magic** |               **Main action** |
> | --------------- | ----------------------------: |
> | **📏 2 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 2 holy damage
> - **12-16:** 3 holy damage
> - **17+:** 5 holy damage
>
> **Effect:** You can teleport yourself and each ally in the area to unoccupied spaces in the area.

<!-- -->
> ###### Sacrificial Offer
>
> *Divine magic tears at your foe and defends a nearby friend.*
>
> | **Magic, Ranged, Strike** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 2 + I corruption damage
> - **12-16:** 4 + I corruption damage
> - **17+:** 6 + I corruption damage
>
> **Effect:** Choose yourself or one ally within distance. That character can impose a bane on one power roll made against them before the end of their next turn.

<!-- -->
> ###### Staggering Curse
>
> *A blast of judgment disorients your foe.*
>
> | **Magic, Melee, Strike** |               **Main action** |
> | ------------------------ | ----------------------------: |
> | **📏 Melee 1**           | **🎯 One creature or object** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I holy damage; slide 1
> - **12-16:** 5 + I holy damage; slide 2
> - **17+:** 8 + I holy damage; slide 3

<!-- -->
> ###### Warrior's Prayer
>
> *Your quickly uttered prayer lends aggressive divine energy to a friend engaged in melee.*
>
> | **Magic, Ranged, Strike** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I holy damage
> - **12-16:** 6 + I holy damage
> - **17+:** 9 + I holy damage
>
> **Effect:** You or one ally within distance gains temporary Stamina equal to your Intuition score.

<!-- -->
> ###### Wither
>
> *A bolt of holy energy saps the life from a foe.*
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I corruption damage; P < WEAK, the target takes a bane on their next power roll
> - **12-16:** 5 + I corruption damage; P < AVERAGE, the target takes a bane on their next power roll
> - **17+:** 8 + I corruption damage; P < STRONG, the target takes a bane on their next power roll

##### Heroic Abilities

You make use of a number of heroic abilities, all of which channel piety to empower them.

###### 3-Piety Ability

Choose one heroic ability from the following options, each of which costs 3 piety to use. (*Quick Build:* Violence Will Not Aid Thee.)

<!-- -->
> ###### Call the Thunder Down (3 Piety)
>
> *You ask your saint for thunder and your prayer is answered.*
>
> | **Area, Magic, Ranged** |               **Main action** |
> | ----------------------- | ----------------------------: |
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 2 sonic damage; push 1
> - **12-16:** 3 sonic damage; push 2
> - **17+:** 5 sonic damage; push 3
>
> **Effect:** You can push each willing ally in the area the same distance, ignoring stability.

<!-- -->
> ###### Font of Wrath (3 Piety)
>
> *A brilliant column of holy light appears on the battlefield, striking out at nearby enemies.*
>
> | **Magic, Ranged** | **Main action** |
> | ----------------- | --------------: |
> | **📏 Ranged 10**  |  **🎯 Special** |
>
> **Effect:** You summon a spirit of size 2 who can't be harmed, and who appears in an unoccupied space within distance. The spirit lasts until the end of your next turn. You and your allies can move through the spirit's space, but enemies can't. Any enemy who moves within 2 squares of the spirit for the first time in a combat round or starts their turn there takes holy damage equal to your Intuition score.

<!-- -->
> ###### Judgment's Hammer (3 Piety)
>
> *Your divine fury is a hammer that crashes down upon the unrighteous.*
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I holy damage; A < WEAK, prone
> - **12-16:** 6 + I holy damage; A < AVERAGE, prone
> - **17+:** 9 + I holy damage; A < STRONG, prone and can't stand (save ends)

<!-- -->
> ###### Violence Will Not Aid Thee (3 Piety)
>
> *After some holy lightning, your enemy will think twice about their next attack.*
>
> | **Magic, Ranged, Strike** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I lightning damage
> - **12-16:** 6 + I lightning damage
> - **17+:** 9 + I lightning damage
>
> **Effect:** The first time on a turn that the target deals damage to another creature, the target of this ability takes 1d10 lightning damage (save ends).

###### 5-Piety Ability

Choose one heroic ability from the following options, each of which costs 5 piety to use. (*Quick Build:* Curse of Terror.)

<!-- -->
> ###### Corruption's Curse (5 Piety)
>
> *Cursed by you, your enemy takes more damage from your allies.*
>
> | **Magic, Ranged, Strike** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 10**          | **🎯 One creature or object** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 3 + I corruption damage; M < WEAK, damage weakness 5 (save ends)
> - **12-16:** 6 + I corruption damage; M < AVERAGE, damage weakness 5 (save ends)
> - **17+:** 9 + I corruption damage; M < STRONG, damage weakness 5 (save ends)

<!-- -->
> ###### Curse of Terror (5 Piety)
>
> *Fear of divine judgment overwhelms your foe.*
>
> | **Magic, Ranged, Strike** |     **Main action** |
> | ------------------------- | ------------------: |
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + Intuition:**
>
> - **≤11:** 6 + I holy damage; I < WEAK, frightened (save ends)
> - **12-16:** 9 + I holy damage; I < AVERAGE, frightened (save ends)
> - **17+:** 13 + I holy damage; I < STRONG, frightened (save ends)

<!-- -->
> ###### Faith Is Our Armor (5 Piety)
>
> *The heroes' armor glows with golden light, granting divine protection.*
>
> | **Magic, Ranged** |       **Maneuver** |
> | ----------------- | -----------------: |
> | **📏 Ranged 10**  | **🎯 Four allies** |
>
> **Effect:** You can target yourself instead of one ally with this ability.
>
> **Power Roll + Intuition:**
>
> - **≤11:** The target gains 5 temporary Stamina.
> - **12-16:** The target gains 10 temporary Stamina.
> - **17+:** The target gains 15 temporary Stamina.

<!-- -->
> ###### Sermon of Grace (5 Piety)
>
> *You inspire your allies with tales of your saint's great deeds.*
>
> | **Area, Magic** |              **Main action** |
> | --------------- | ---------------------------: |
> | **📏 4 burst**  | **🎯 Each ally in the area** |
>
> **Effect:** Each target can spend a Recovery. Additionally, each target can use a free triggered action to end one effect on them that is ended by a saving throw or that ends at the end of their turn, or to stand up if prone.

---
file_basename: Manticore
file_dpath: Monsters/Manticores
item_id: manticore
item_index: '07'
item_name: Manticore
scc:
  - mcdm.monsters.v1:monster.section:manticore
scdc:
  - 1.1.1:2.1:07
source: mcdm.monsters.v1
type: monster/section
---

## Manticore

A weary traveler hears a call through the forest or friendly voices from a rocky shelter, and their heart leaps at the promise of refuge—only to find themself at the mercy of serrated teeth and poisonous spikes. In a manticore's territory, people go missing without a trace. These fearsome creatures carve out their hunting grounds in forests near small villages, mountain passes where caravans travel, and other locations with plentiful wildlife. Though manticores can subsist on a carnivorous diet of any nearby prey, their choicest meal is humanoid flesh.

#### Uncanny Appearances

A manticore has a lion's body, a dragon's wings, and a scorpion's tail barbed with spines, but their most unnerving trait is their humanoid face. Owing to a quirk of magical evolution, manticores develop the features of common ancestries that populate their region of birth. For example, a manticore in an area densely populated by devils inherits fiendish eyes and devilish horns. Manticores are born with an inherent understanding of a regional language, but they can speak only through mimicking that which they've heard—a talent manticores use to lure in prey.

#### Heralds of Death

Manticores have a magical howl like a trumpet blast. This haunting sound unnerves and terrifies creatures, making them more susceptible to the manticore's bite. While on the hunt, manticores often take to the skies, shooting poison-tipped spikes from their tail to weaken their victims before howling and closing in.

#### Ferocious Companions

A manticore who develops a taste for humanoids can rarely be tamed. But a young manticore who has yet to cut their teeth on such flesh can be raised into a fearsome ally. Even after a trained manticore companion finally tastes delicious humanoid flesh, they typically remain loyal to their caregiver.

#### Manticore Languages

Most manticores can mimic Caelian and one language commonly spoken in the region where they dwell. Except in rare cases, manticores don't communicate in full sentences and are too driven by hunger to engage in negotiation.

###### Manticore Malice (Malice Features)

At the start of any manticore's turn, you can spend Malice to activate one of the following features.

<!-- -->
> 🌀 **Uncanny Mimicry (3 Malice)**
>
> The manticore uses their mimicry in an attempt to unnerve one creature within their line of effect. If the target has R < 4, they take a bane on power rolls against the manticore (save ends). Each time this feature is used against the same target during the encounter, its potency decreases by 2.

<!-- -->
> ☠️ **Solo Action (5 Malice)**
>
> The manticore takes an additional main action on their turn. They can use this feature even if they are dazed.

<!-- -->
> 🌀 **Desperate Howl (5 Malice)**
>
> The manticore lets out an unnerving cry. Each enemy within the manticore's line of effect makes an **Intuition test**.
>
> - **≤11:** Frightened (save ends)
> - **12-16:** Frightened (EoT)
> - **17+:** No effect.

<!-- -->
> ❇️ **Barrage of Barbs (7 Malice)**
>
> The manticore sprays tail spikes across the ground within 5 squares of them. Each enemy in that area who has A < 3 is bleeding (save ends). Additionally, the area is difficult terrain, and any enemy takes 3 poison damage for each square of the area they enter. An enemy who takes 9 poison damage this way on one turn is weakened until the end of the encounter.

###### Manticore

|  Beast, Manticore   |           -           |       Level 4        |          Solo           |         EV 72          |
| :-----------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|   **2**<br/> Size   |   **10**<br/> Speed   | **350**<br/> Stamina |  **2**<br/> Stability   | **6**<br/> Free Strike |
| **-**<br/> Immunity | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+4**<br/> Might  |  **+3**<br/> Agility  |  **0**<br/> Reason   |  **0**<br/> Intuition   |  **-1**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the manticore can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The manticore can take two turns each round. They can't take turns consecutively.

<!-- -->
> ⭐️ **Agile Predator**
>
> Whenever the manticore deals damage to a creature, they don't provoke opportunity attacks from that creature during that turn.

<!-- -->
> 🗡 **Carnivorous Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> | ------------------------- | ----------------------------: |
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 12 damage; A < 2 bleeding (save ends)
> - **12-16:** 17 damage; A < 3 bleeding (save ends)
> - **17+:** 21 damage; A < 4 bleeding (save ends)
>
> **Effect:** If the target is frightened, this ability gains an edge.

<!-- -->
> 🏹 **Tail Spike**
>
> | **Ranged, Strike, Weapon** |                 **Main action** |
> | -------------------------- | ------------------------------: |
> | **📏 Ranged 10**           | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 6 damage; M < 2 4 poison damage
> - **12-16:** 11 damage; M < 3 4 poison damage, weakened (save ends)
> - **17+:** 14 damage; M < 4 8 poison damage, weakened (save ends)
>
> **1 Malice:** While weakened this way, a target takes 1d6 poison damage at the start of each of their turns.

<!-- -->
> 🗡 **Harrying Claws**
>
> | **Melee, Strike, Weapon** |                    **Maneuver** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** Slide 1; A < 2 3 damage
> - **12-16:** Slide 2; A < 3 5 damage
> - **17+:** Slide 4; A < 4 7 damage

<!-- -->
> ❗️ **Reflexive Instinct (2 Malice)**
>
> | **Ranged**       |           **Triggered action** |
> | ---------------- | -----------------------------: |
> | **📏 Ranged 10** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the manticore.
>
> **Effect:** The manticore shifts up to 5 squares into the air, then can use Tail Spike against the target.

<!-- -->
> ☠️ **Trumpeting Howl (Villain Action 1)**
>
> | **Area, Magic** |                            **-** |
> | --------------- | -------------------------------: |
> | **📏 5 burst**  | **🎯 Each creature in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** Frightened (EoT); if the target has I < 2 they are instead frightened (save ends)
> - **12-16:** Frightened (EoT); if the target has I < 3 they are instead frightened (save ends)
> - **17+:** Frightened (EoT); if the target has I < 4 they are instead dazed (save ends)

<!-- -->
> ☠️ **Cornered Predator (Villain Action 2)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The manticore shifts up to their speed, then can use Tail Spike against each enemy within distance of that ability.

<!-- -->
> ☠️ **Debilitating Poison (Villain Action 3)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The manticore sours their poison with enmity. Until the end of the encounter, the manticore has a double edge on power rolls against weakened creatures. Additionally, any creature weakened by the manticore's Tail Spike ability has their speed halved and takes an extra 3 poison damage at the start of each of their turns.

###### Manticore Treasures

<!-- -->
> **Manticore Treasures**
>
> Although manticores have no earthly use for treasure, they tend to collect a lot of it—it comes attached to the humanoids they prey on. Since manticores drag their victims back to their cave lairs to feed, a manticore's cave is typically strewn with bones, broken weapons, coins, and other relics of unfortunate travelers. After a while, a manticore abandons its cluttered lair in favor of a fresh one, leaving unguarded treasure for anyone willing to explore manticore-infested wastes.
>
> The following are sample treasures from a manticore's cave, of which a manticore might have one or two. These items can be found in Draw Steel: Heroes.
>
> - **Treasures:** Blade of the Luxurious Fop, Bull Shot, Stop-'n-Go Coin
> - **Components:** Adamatine spearheads, a mirror blessed by a priest, pixie wings
> - **Project Sources:** Notes in Zaliac for the Warding II armor enhancement, notes in Khelt for the Celerity implement enhancement, notes in Variac for an Onerous Bow
> - **Wealth:** If the heroes follow blood trails back to a nearby abandoned caravan, each hero earns 1 wealth

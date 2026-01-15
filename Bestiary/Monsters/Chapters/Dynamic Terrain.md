---
chapter_num: 3
file_basename: Dynamic Terrain
file_dpath: Chapters
item_id: dynamic-terrain
item_index: '03'
item_name: Dynamic Terrain
scc:
  - mcdm.monsters.v1:chapter:dynamic-terrain
scdc:
  - 1.1.1:1:03
source: mcdm.monsters.v1
type: chapter
---

# Dynamic Terrain

A terrain object is an element placed in an encounter that alters tactics on the battlefield, allowing the Director to better theme an encounter. Terrain objects range from hazards that provide tempting targets for forced movement, to fieldworks and siege engines that provide a locational advantage, to supernatural objects that an entire encounter can be built around.

### Terrain Object Stat Blocks

Each terrain object is set up in a stat block, but this stat block format is different than for monsters. The following sections explain what you'll find in a terrain object stat block.

#### EV

Each dynamic terrain object has an encounter value cost, just like monsters in an encounter. Some objects, particularly environmental hazards, have a cost representing an area, such as a 10 x 10-square section of terrain. A hazard can always be smaller than that indicated size.

#### Stamina

Terrain objects have either a fixed amount of Stamina or an amount of Stamina per square, depending on their nature and size. If an object has an amount of Stamina per square, it can be partially destroyed square by square.

#### Size

Terrain objects either have a standard size (for example, 1M) or a size noted as squares of terrain or material. If a terrain object's size is noted as squares, a creature can move through that terrain object but might trigger the object's effects. Many terrain objects sized in squares are difficult terrain, as noted in the object's size entry.

#### Direction

Some terrain objects have a defined direction indicating how they are placed, such as archer's stakes having a front side.

#### Deactivate

Most terrain objects can be deactivated under certain circumstances. The Sabotage skill is generally applicable for tests made to deactivate mechanisms and siege engines, while traps might allow different skills to be used depending on their setup—Alchemy to deactivate a pool of flammable oil, Nature to deactivate a spiked pit trap in a forest, Magic or Psionics to deactivate a supernatural object, and so forth. Disabling a supernatural object requires a more intricate process detailed in each object's stat block.

Once a terrain object is deactivated, the Director determines what must be done to reset it and how long it takes to do so.

#### Activate

Terrain objects typically activate when a creature enters their space or when the object is interacted with in a specific way. Unless otherwise noted, there is no limit to how often a terrain object can activate.

Some terrain objects, particularly traps and other objects that are set up by creatures, are set to activate only in response to creatures or objects of a particular size. For example, smaller creatures such as goblins and kobolds typically calibrate their traps for size 1M and larger creatures, making those traps safe for smaller creatures to pass through.

Many area terrain objects activate when a creature enters their area without shifting. If such a terrain object is difficult terrain, remember that creatures can't usually shift through difficult terrain without having a trait or feature that allows them to do so.

#### Effect

Each terrain object's effect entry defines what happens when the object is triggered.

#### Upgrades

Some terrain objects can be upgraded to create additional effects. If a terrain object has a size in squares, the upgrade cost is paid on a square-by-square basis unless otherwise noted.

### Hidden Terrain Objects

Some terrain objects are inherently hidden or can be hidden with an upgrade. Hidden objects can be found as part of the Search for Hidden Creatures maneuver (see *Draw Steel: Heroes*). When you make an **Intuition test** to search for hidden creatures and objects, use the following outcomes for dealing with objects:

- **≤11:** You find all hidden terrain objects adjacent to you.
- **12-16:** You find all hidden terrain objects within 5 squares of you.
- **17+:** You find all hidden terrain objects within 10 squares of you.

#### Allied Awareness

Some terrain objects have an Allied Awareness trait noting benefits and options available to creatures who have familiarity and training with the object. If a creature is aware of a terrain object and has sufficient time to study it, they gain the object's Allied Awareness benefits at the Director's determination.

### Environmental Hazards

Environmental hazards represent natural elements that creatures (typically creatures defending a location) have channeled, cultivated, or otherwise placed to give them an edge in an encounter.

###### Angry Beehive (Level 2 Hazard Hexer)

This beehive is full of angry bees who swarm and attack with little provocation.

- **EV:** 2
- **Stamina:** 3
- **Size:** 1S

<!-- -->
> 🌀 **Deactivate**
>
> The beehive can't be deactivated. If it takes damage or is destroyed, the hive unleashes a swarm of bees.

<!-- -->
> ❕ **Activate**
>
> A creature enters the hive's space or an adjacent space without shifting.
>
> **Effect:** The hive is removed from the encounter map and a swarm of bees is placed in one square of the space of the triggering creature. Any creature who starts their turn in the swarm's space takes 3 poison damage. At the start of each round, the swarm moves 1 square and its size increases by 1 square (to 2 squares by 2 squares, 3 squares by 3 squares, and so forth), preferring squares in a creature's space. After 3 rounds, the swarm dissipates.

<!-- -->
> ⭐️ **Upgrades**
>
> **Concealed Hive (+1 EV)** The hive is hidden until the swarm is unleashed.
>
> **Killer Bees (+2 EV)** The bees are a particularly aggressive and dangerous species. The hive triggers even if a creature shifts into or while adjacent to it, and the swarm deals 1d6 + 3 poison damage.

###### Brambles (Level 1 Hazard Defender)

This thicket features close-growing vines tipped with sharp thorns.

- **EV:** 1 per 10 x 10 thicket
- **Stamina:** 3 per square
- **Size:** One or more squares of difficult terrain

<!-- -->
> 🌀 **Deactivate**
>
> Each square of brambles must be individually destroyed.

<!-- -->
> ❕ **Activate**
>
> A creature enters a square of brambles without shifting.
>
> **Effect:** A creature takes 1 damage per square of brambles they enter.

<!-- -->
> ⭐️ **Upgrade**
>
> **Poisonous Thorns (+1 EV)** The brambles are poisonous. Any creature who takes damage from brambles is also bleeding (save ends).

###### Corrosive Pool (Level 2 Hazard Hexer)

This shallow pool bubbles with acid or some other corrosive liquid.

- **EV:** 3 per 10 x 10 pool
- **Stamina:** 12 per square
- **Size:** One or more squares of difficult terrain
- **Immunity:** 20 to all damage except cold or fire damage

<!-- -->
> 🌀 **Deactivate**
>
> The pool must be completely destroyed.

<!-- -->
> ❕ **Activate**
>
> A creature or object enters the corrosive pool or starts their turn there. The liquid in the pool is also highly volatile (see **Explosive Reaction** below).
>
> **Effect:** A creature or object takes 3 acid damage if they start their turn in the pool, and takes 3 acid damage for each square of the pool they enter.

<!-- -->
> ❗️ **Explosive Reaction**
>
> | **Area**       |                   **Free triggered action** |
> | -------------- | ------------------------------------------: |
> | **📏 3 burst** | **🎯 Each creature and object in the area** |
>
> **Trigger:** The pool takes fire damage.
>
> **Power Roll + 2:**
>
> - **≤11:** 3 fire damage; M < 1 the target is burning (save ends)
> - **12-16:** 6 fire damage; M < 2 the target is burning (save ends)
> - **17+:** 9 fire damage; M < 3 the target is burning (save ends)
>
> **Effect:** The liquid in the pool is consumed. This ability has a double edge against any target in the pool. A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round. Any target with acid weakness takes extra damage from this ability and while burning as if the fire damage were acid damage.

<!-- -->
> ⭐️ **Allied Awareness**
>
> Allies who have weapons are equipped with torches. Any ally can use a maneuver to throw a torch up to 5 squares and deal 1 fire damage to the pool, triggering Explosive Reaction.

###### Frozen Pond (Level 1 Hazard Hexer)

A shallow, frozen patch of water features ice thick enough that it won't break, but its surface is slick and treacherous to navigate.

- **EV:** 1 per 10 x 10 pond
- **Stamina:** 3 per square
- **Size:** One or more squares of difficult terrain
- **Immunity:** 5 to all damage except fire damage

<!-- -->
> 🌀 **Deactivate**
>
> Destroying a square of the frozen pond turns the square into shallow icy water.

<!-- -->
> ❕ **Activate**
>
> A creature or object enters a square of the frozen pond without shifting.
>
> **Effect:** The **Slippery Surface** ability.

<!-- -->
> ❗️ **Slippery Surface**
>
> | **Melee, Strike** |                **Free triggered action** |
> | ----------------- | ---------------------------------------: |
> | **📏 Melee 0**    | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object enters a square of the frozen pond without shifting.
>
> **Power Roll + 2:**
>
> - **≤11:** Push 1 in the direction the target was moving
> - **12-16:** Push 2 in the direction the target was moving; A < 1 slowed (save ends)
> - **17+:** Push 3 in the direction the target was moving; A < 2 prone and can't stand (save ends)
>
> **Effect:** The triggering creature's movement ends, then they are force moved. If the target triggered this ability by being force moved, this ability gains an edge and any remaining forced movement distance is added to the ability's forced movement. The ability's forced movement doesn't trigger the ability again.

<!-- -->
> ⭐️ **Upgrade**
>
> **Thin Ice (+1 EV)** The ice covering the pond is thin and the water is deeper. Whenever a creature or object enters or falls prone in a square of the frozen pond, that square is destroyed and replaced with icy water. The **Icy Water** ability replaces **Slippery Surface**.
>
> Any creature who starts their turn in the icy water takes 1 cold damage. If the water is deep enough, a creature can swim beneath the surface of the frozen pond, but takes this cold damage while doing so.

❗️ **Icy Water**

<!-- -->
> **Power Roll + 2:**
>
> | **Melee, Strike** |                **Free triggered action** |
> | ----------------- | ---------------------------------------: |
> | **📏 Melee 0**    | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object enters or falls prone in a square of the frozen pond.
>
> - **≤11:** Slide 1
> - **12-16:** 1 cold damage; M < 1 slowed (save ends)
> - **17+:** 3 cold damage; M < 2 restrained (save ends)
>
> **Effect:** The triggering creature's movement ends, then they are force moved if applicable.

###### Lava (Level 3 Hazard Hexer)

A patch of blisteringly hot molten rock wells up from the ground, threatening anyone who gets close to it.

- **EV:** 4 per 10 x 10 patch
- **Stamina:** 12 per square
- **Size:** One or more squares of difficult terrain
- **Immunity:** 20 to all damage except cold damage

<!-- -->
> 🌀 **Deactivate**
>
> Each square of lava must be individually destroyed.

<!-- -->
> ❕ **Activate**
>
> A creature or object enters the lava or starts their turn there, or starts their turn adjacent to the lava.
>
> **Effect:** The **Liquid Hot Magma** ability.

<!-- -->
> ❗️ **Liquid Hot Magma**
>
> | **Melee, Strike** |                **Free triggered action** |
> | ----------------- | ---------------------------------------: |
> | **📏 Melee 1**    | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object enters the lava or starts their turn there, or starts their turn adjacent to the lava.
>
> **Power Roll + 2:**
>
> - **≤11:** 5 fire damage; M < 1 the target is burning (save ends)
> - **12-16:** 9 fire damage; M < 2 the target is burning (save ends)
> - **17+:** 12 fire damage; M < 3 the target is burning (save ends)
>
> **Effect:** If the target is adjacent to lava but not in it, this ability takes a bane. A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.

<!-- -->
> ⭐️ **Upgrade**
>
> **Magma Flow (+4 EV)** The lava is flowing! At the start of each round, add one square of lava adjacent to an existing square of lava.

###### Quicksand (Level 3 Hazard Hexer)

When this patch of sand is stepped on, it is revealed to be a slurry saturated by water—and ready to draw creatures down to their doom.

- **EV:** 3 per 10 x 10 patch
- **Stamina:** -
- **Size:** One or more squares

<!-- -->
> 🌀 **Deactivate**

<!-- -->
> ❕ **Activate**
>
> A creature or object enters the quicksand or starts their turn there.
>
> **Effect:** The **Grasping Depths** ability.

<!-- -->
> ❗️ **Grasping Depths**
>
> | **Melee, Strike** |                **Free triggered action** |
> | ----------------- | ---------------------------------------: |
> | **📏 Melee 0**    | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object enters the quicksand or starts their turn there.
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 slowed (save ends)
> - **12-16:** M < 1 restrained (save ends)
> - **17+:** M < 2 restrained (save ends)
>
> **Effect:** This ability takes a bane if a triggering creature shifted into the quicksand. A character who starts their turn restrained this way is suffocating.

<!-- -->
> ⭐️ **Hidden**
>
> The quicksand is hidden until triggered or detected.

###### Toxic Plants (Level 2 Hazard Hexer)

Colorful mushrooms or lovely flowering plants release a cloud of spores or pollen when disturbed, causing creatures to fall into a magical slumber.

- **EV:** 2 per 10 x 10 field
- **Stamina:** 3 per square
- **Size:** One or more squares

<!-- -->
> 🌀 **Deactivate**
>
> Each square of plants must be individually destroyed.

<!-- -->
> ❕ **Activate**
>
> A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without shifting.
>
> **Effect:** The **Sleep Spores** ability.

<!-- -->
> ❗️ **Sleep Spores**
>
> | **Magic, Melee, Strike** |      **Free triggered action** |
> | ------------------------ | -----------------------------: |
> | **📏 Melee 0**           | **🎯 The triggering creature** |
>
> **Trigger:** A creature starts their turn in the area of the toxic plants, or enters a square of toxic plants without shifting.
>
> **Power Roll + 2:**
>
> - **≤11:** M < 0 dazed (save ends)
> - **12-16:** M < 1 dazed (save ends)
> - **17+:** M < 2 dazed (save ends)
>
> **Effect:** While dazed this way, a target who starts their turn in the area of the toxic plants falls prone and can't stand.

<!-- -->
> ⭐️ **Upgrades**
>
> **Poisonous Spores (+2 EV)** Any creature dazed by this hazard takes 1d6 poison damage at the start of each of their turns.
>
> **Carnivorous Plants (+2 EV)** The plants are carnivorous and attempt to slowly digest any creature who falls among them. Any creature who starts their turn prone in the area takes 4 acid damage.

### Fieldworks

Fieldworks represent temporary military fortifications meant to give defenders an edge in an encounter.

###### Archer's Stakes (Level 1 Fortification Defender)

A series of sharp stakes have been placed point-out to protect defenders against charges and other direct attacks.

- **EV:** 2
- **Stamina:** 3 per square
- **Size:** One or more squares of difficult terrain
- **Typical Space:** 4 x 1-square area
- **Direction:** One side of the stakes is defined as the front.

<!-- -->
> 🌀 **Deactivate**
>
> Each square of stakes must be individually destroyed.

<!-- -->
> ❕ **Activate**
>
> A creature enters an area of stakes from the front.
>
> **Effect:** The triggering creature takes 2 damage per square of stakes they enter. If they are force moved into an area of stakes, they take an additional 3 damage.

<!-- -->
> ⭐️ **Upgrades**
>
> **Poison (+2 EV)** The tips of the stakes have poison applied to them. Any creature who takes damage from the stakes also takes 1d6 poison damage at the start of each of their turns (save ends).
>
> **Sticky (+3 EV)** A sticky slime or webbing has been applied to the stakes and the ground between them. Any creature who enters an area of stakes triggers the **Sticky Stakes** ability in addition to suffering the stakes' other effects.

<!-- -->
> ❗️ **Sticky Stakes**
>
> | **Melee, Strike, Weapon** |                **Free triggered action** |
> | ------------------------- | ---------------------------------------: |
> | **📏 Melee 0**            | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object enters an area of sticky stakes.
>
> **Power Roll + 2:**
>
> - **≤11:** No effect.
> - **12-16:** A < 1 slowed (save ends)
> - **17+:** A < 2 restrained (save ends)

<!-- -->
> ⭐️ **Allied Awareness**
>
> Allies of this object ignore the difficult terrain created by the stakes, take no damage from moving through the stakes unless they are force moved, and have cover while in an area of archer's stakes.

###### Bear Trap (Level 1 Trap Ambusher)

A set of spring-loaded steel jaws stands ready to snap shut when stepped on.

- **EV:** 2
- **Stamina:** 6
- **Size:** 1S

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a bear trap can make an **Agility test**.
>
> - **≤11:** The creature triggers the trap and is affected as if in its space.
> - **12-16:** The trap is deactivated but the creature is slowed (EoT).
> - **17+:** The trap is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> The bear trap is calibrated to be triggered by creatures or objects of a particular size or larger. The trap triggers when a creature or object of the appropriate size enters its space.
>
> **Effect:** A triggering creature or object ends their movement and is targeted by the **Bear Trap** ability.

<!-- -->
> ❗️ **Bear Trap**
>
> | **Melee, Strike, Weapon** |                **Free triggered action** |
> | ------------------------- | ---------------------------------------: |
> | **📏 Melee 0**            | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object of the appropriate size enters the trap's space.
>
> **Power Roll + 2:**
>
> - **≤11:** 1 The target shifts 1 square away from the trap.
> - **12-16:** 3 damage; A < 1 slowed (save ends)
> - **17+:** 5 damage; A < 2 slowed (save ends)
>
> **Effect:** The bear trap must be manually reset.

<!-- -->
> ⭐️ **Upgrade**
>
> **Chain (+1 EV)** The bear trap is attached to the ground by a steel chain. A target who would be made slowed by the trap is restrained instead.

<!-- -->
> ⭐️ **Hidden**
>
> The bear trap is hidden until triggered or detected.

###### Flammable Oil (Level 1 Trap Ambusher)

A patch of flammable oil or pitch on the ground is ready to be ignited.

- **EV:** 2 per 10 x 10 patch
- **Stamina:** -
- **Size:** One or more squares

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a patch of flammable oil can make an **Agility test**.
>
> - **≤11:** The creature ignites the oil and is affected as if in its area.
> - **12-16:** The oil temporarily ignites before safely burning out, and the creature takes 3 fire damage and is burning (save ends).
> - **17+:** The oil is rendered safe and can't be ignited.

<!-- -->
> ❕ **Activate**
>
> A creature or object in a square of oil takes fire damage, or a creature or object enters a square of burning oil or starts their turn there.
>
> **Effect:** The triggering creature or object takes 3 fire damage and is burning (save ends). A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.

<!-- -->
> ⭐️ **Upgrade**
>
> **Concealed Oil (+1 EV)** The oil is hidden until it ignites.

<!-- -->
> ⭐️ **Allied Awareness**
>
> Allies who have weapons are equipped with torches. Any ally can use a maneuver to throw a torch up to 5 squares and ignite the flammable oil.

###### Hidey-Hole (Level 1 Fortification Ambusher)

A cavity in a floor, wall, or ceiling might hold hidden threats.

- **EV:** 1
- **Stamina:** -
- **Size:** One or more squares

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a hidey-hole can make a **Might test**.
>
> - **≤11:** The creature is restrained (save ends).
> - **12-16:** The hidey-hole collapses but the creature is slowed (save ends).
> - **17+:** The hidey-hole collapses and can no longer be used until repaired.

<!-- -->
> ❕ **Activate**
>
> A creature starts the encounter in the hidey-hole or ends their turn there.
>
> **Effect:** The triggering creature can attempt to hide as a free triggered action.

<!-- -->
> ⭐️ **Upgrade**
>
> **Network (+1 EV per hidey-hole)** The hidey-hole is connected to a tunnel network. A creature familiar with the network can move from one hidey-hole to any space adjacent to a connected hidey-hole if they have movement available equal to the straight-line distance to that space. A creature unfamiliar with the network can use a maneuver to make a **hard Intuition test** to discover a connected hidey-hole.

###### Pavise Shield (Level 1 Fortification Defender)

A reinforced metal shield embedded in the ground acts as cover for the creature controlling it.

- **EV:** 1
- **Stamina:** 9
- **Size:** 1M

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a pavise shield controlled by another creature can make a **Might test**.
>
> - **≤11:** The creature controlling the shield retains control of it and can make an opportunity attack against the creature making the test.
> - **12-16:** The creature controlling the shield retains control of it.
> - **17+:** The creature making the test grabs the shield and takes control of it.

<!-- -->
> ⭐️ **Controlling the Shield**
>
> While a creature has the pavise shield grabbed, they have cover and take half damage from abilities whose line of effect extends through the shield. The pavise shield takes the other half of the damage.
>
> While a creature has a pavise shield grabbed, their speed is halved and they move the shield like a grabbed creature.

###### Snare Trap (Level 1 Trap Ambusher)

A rope snare is set to grab a target, leaving them hanging upside down.

- **EV:** 1
- **Stamina:** 1
- **Size:** 1S

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a snare trap can make an **Agility test**.
>
> - **≤11:** The creature triggers the trap and is affected as if in its space.
> - **12-16:** The trap is deactivated but the creature is slowed (EoT).
> - **17+:** The trap is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> The snare trap is calibrated to be triggered by creatures or objects of a particular size or larger. The trap triggers when a creature or object of the appropriate size enters its space.
>
> **Effect:** A triggering creature or object ends their movement and is targeted by the **Snare** ability.

<!-- -->
> ❗️ **Snare**
>
> | **Melee, Strike, Weapon** |                **Free triggered action** |
> | ------------------------- | ---------------------------------------: |
> | **📏 Melee 0**            | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object of the appropriate size enters the trap's space.
>
> **Power Roll + 2:**
>
> - **≤11:** The target shifts 1 square away from the snare.
> - **12-16:** 1 damage; A < 1 restrained (save ends)
> - **17+:** 3 damage; A < 2 restrained (save ends)
>
> **Effect:** A creature restrained this way is vertical pulled 2 squares and suspended in the air by the snare line. On a successful save, the snare is cut or breaks and the creature falls to the ground. The snare must be manually reset.

<!-- -->
> ⭐️ **Upgrade**
>
> **Net Trap (+1 EV)** The snare becomes a net that can wrap up multiple targets. The net has 3 Stamina and fills an area of 3 squares by 3 squares. The Snare ability loses its existing keywords, gains the Area keyword, and targets each creature or object in the area. The trap can be triggered by a target moving through one specific square, or by requiring multiple squares to be moved through. Any creature who makes their save to end the restrained effect ends that effect for all targets, who all fall to the ground.

<!-- -->
> ⭐️ **Hidden**
>
> The snare trap is hidden until triggered or detected.

###### Spike Trap (Level 2 Trap Ambusher)

A pit dug into the ground is filled with spikes, and camouflaged to avoid detection.

- **EV:** 3
- **Stamina:** 6
- **Size:** One or more squares
- **Typical Space:** 2 x 2-square area

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a spike trap can make an **Agility test**.
>
> - **≤11:** The creature triggers the trap and is affected as if in its area.
> - **12-16:** The trap is deactivated but the creature is slowed (EoT).
> - **17+:** The trap is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> The spike trap is calibrated to be triggered by creatures or objects of a particular size or larger. The trap triggers when a creature or object of the appropriate size enters its area.
>
> **Effect:** The **Spike Trap** ability.

<!-- -->
> ❗️ **Spike Trap**
>
> | **Area, Weapon** |                **Free triggered action** |
> | ---------------- | ---------------------------------------: |
> | **📏 Melee 0**   | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object of the appropriate size enters the trap's area.
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; the target shifts 1 square away from the trap
> - **12-16:** 4 damage; the target falls into the pit; A < 0 prone
> - **17+:** 6 damage; the target falls into the pit; A < 1 prone; restrained (save ends)
>
> **Effect:** The target ends their movement when they enter the trap's area. The pit is typically 2 squares deep. The trap must be manually reset.

<!-- -->
> ⭐️ **Hidden**
>
> The spike trap is hidden until triggered or detected.

### Mechanisms

Mechanisms represent any number of intricate devices that can complicate a battle. Unlike more straightforward traps, a mechanism is often linked to another triggering mechanism that activates it.

###### Column of Blades (Level 3 Fortification Defender)

A spinning wooden column is affixed with sharp blades to slash the unwary.

- **EV:** 3
- **Stamina:** 5
- **Size:** 1L

<!-- -->
> 🌀 **Deactivate**
>
> The column of blades must be completely destroyed.

<!-- -->
> ❕ **Activate**
>
> A creature or object moves adjacent to the column of blades.
>
> **Effect:** The **Spinning Blades** ability.

<!-- -->
> ❗️ **Spinning Blades**
>
> | **Melee, Strike, Weapon** |                **Free triggered action** |
> | ------------------------- | ---------------------------------------: |
> | **📏 Melee 1**            | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object moves within distance of the column.
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage; M < 2 bleeding (save ends)
> - **17+:** 9 damage; M < 3 bleeding (save ends)

<!-- -->
> ⭐️ **Upgrades**
>
> **Stone Column (+1 EV)** The column is made of stone and has 8 Stamina.
>
> **Metal Column (+1 EV)** The column is made of metal and has 11 Stamina.
>
> **Concealed (+1 EV)** The blades are concealed inside the column, which remains motionless until triggered.
>
> **Spiked Flails (+4 EV)** Instead of blades, the column is affixed with heavy spiked balls attached by long chains. The **Whirling Flails** ability replaces **Spinning Blades**.

<!-- -->
> ❗️ **Whirling Flails**
>
> | **Melee, Strike, Weapon** |                **Free triggered action** |
> | ------------------------- | ---------------------------------------: |
> | **📏 Melee 2**            | **🎯 The triggering creature or object** |
>
> **Trigger:** A creature or object moves within distance of the column.
>
> - **≤11:** 5 damage
> - **12-16:** 8 damage; M < 2 dazed (save ends)
> - **17+:** 11 damage; M < 3 dazed (save ends)

<!-- -->
> ⭐️ **Allied Awareness**
>
> Allies who shift don't trigger the column. A creature observing an ally shift this way can make an **Intuition test** to shift in imitation of their movements.
>
> **Power Roll + 2:**
>
> - **≤11:** The creature triggers the column and the column's ability gains an edge.
> - **12-16:** The creature triggers the column.
> - **17+:** The creature doesn't trigger the column.

###### Dart Trap (Level 1 Trap Ambusher)

A concealed dart thrower hurls missiles at short range.

- **EV:** 1
- **Stamina:** 3
- **Size:** 1S
- **Direction:** The dart trap fires in a fixed direction.

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a dart trap can make an **Agility test**.
>
> - **≤11:** The creature triggers the trap and is targeted by it.
> - **12-16:** The trap is deactivated but the creature is slowed (EoT).
> - **17+:** The trap is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> A pressure plate, switch, or other linked trigger is activated.
>
> **Effect:** The **Dart** ability.

<!-- -->
> ❗️ **Dart**
>
> | **Ranged, Strike, Weapon** |     **Free triggered action** |
> | -------------------------- | ----------------------------: |
> | **📏 Ranged 5**            | **🎯 One creature or object** |
>
> **Trigger:** A pressure plate, switch, or other linked trigger is activated.
>
> **Power Roll + 2:**
>
> - **≤11:** 2 damage
> - **12-16:** 4 damage
> - **17+:** 5 damage

<!-- -->
> ⭐️ **Upgrades**
>
> **Poison Darts (+2 EV)** The darts are tipped with poison. Any creature who takes damage from a dart also takes 1d6 poison damage at the start of each of their turns (save ends).
>
> **Large Darts (+1 EV)** Larger, heavier darts impart kinetic force to the trap's attack. A target of the **Dart** ability is pushed 1 square on a tier 1 outcome, 2 squares on a tier 2 outcome, or 3 squares on a tier 3 outcome.
>
> **Gatling Darts (+4 EV)** The dart trap is equipped with multiple barrels to launch darts at a high rate of fire. The **Dart** ability loses the Ranged and Strike and takes the Area keyword, its area becomes a 5 x 1 line within 1, and it deals an extra 1d6 damage.

<!-- -->
> ⭐️ **Hidden**
>
> The dart trap is hidden until triggered or detected.

###### Pillar (Level 2 Hazard Hexer)

This stone pillar can be toppled onto unsuspecting foes with the right amount of damage or a well-engineered trigger mechanism.

- **EV:** 3
- **Stamina:** 6
- **Size:** One square that can't be moved through
- **Direction:** The pillar topples in a preset direction.

<!-- -->
> 🌀 **Deactivate**
>
> The pillar's linked trigger must be deactivated.

<!-- -->
> ❕ **Activate**
>
> The pillar is destroyed, or a pressure plate, switch, or other linked trigger is activated.
>
> **Effect:** The **Toppling Pillar** ability.

<!-- -->
> ❗️ **Toppling Pillar**
>
> | **Area**                   |                   **Free triggered action** |
> | -------------------------- | ------------------------------------------: |
> | **📏 4 x 1 line within 1** | **🎯 Each creature and object in the area** |
>
> **Trigger:** The pillar is destroyed, or a pressure plate, switch, or other linked trigger is activated.
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage; M < 1 restrained (save ends)
> - **17+:** 9 damage; M < 2 restrained (save ends)
>
> **Effect:** The area is difficult terrain.

<!-- -->
> ⭐️ **Upgrades**
>
> **Metal Pillar (+1 EV)** The pillar is made of metal, has 9 Stamina, and deals 1d6 extra damage.
>
> **Multiple Pillars (+3 EV per additional pillar)** Multiple pillars can be used to represent a larger toppling object such as a wall. If triggered by destruction, all individual pillars need to be destroyed before the object falls.

###### Portcullis (Level 3 Trap Ambusher)

A portcullis is hidden in the ceiling of a passage or choke point, waiting to drop when activated.

- **EV:** 4
- **Stamina:** 9 per square
- **Size:** The area of the corridor to be blocked
- **Typical Space:** 2 x 1-square area, up to a 4 x 2-square area

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a portcullis can make an **Agility test**.
>
> - **≤11:** The creature triggers the portcullis and is affected as if in its area.
> - **12-16:** The portcullis is deactivated but the creature is slowed (EoT).
> - **17+:** The portcullis is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> A pressure plate, switch, or other linked trigger is activated.
>
> **Effect:** The **Heavy Gate** ability.

<!-- -->
> ❗️ **Heavy Gate**
>
> | **Area, Weapon** |                   **Free triggered action** |
> | ---------------- | ------------------------------------------: |
> | **📏 Special**   | **🎯 Each creature and object in the area** |
>
> **Trigger:** A pressure plate, switch, or other linked trigger is activated.
>
> **Special:** The area of this ability is the area directly beneath the portcullis when it falls.
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; slide 1, ignoring stability
> - **12-16:** 7 damage; A < 2 restrained (save ends)
> - **17+:** 10 damage; A < 3 restrained (save ends)
>
> **Effect:** The portcullis blocks movement from one side of it to the other. A target slid by the portcullis ends up on one side of it or the other (choose randomly). The portcullis must be manually reset.

<!-- -->
> ⭐️ **Hidden**
>
> The portcullis is hidden until triggered or detected.

###### Pressure Plate (Level 1 Trigger Support)

This mechanism acts as a trigger for another linked mechanism, and is skillfully hidden from view in the floor.

- **EV:** 2
- **Stamina:** -
- **Size:** Any area
- **Typical Space:** One square, up to a 4 x 4-square area
- **Link:** A pressure plate is linked to another mechanism that it activates when triggered.

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a pressure plate can make an **Agility test**.
>
> - **≤11:** The creature triggers the pressure plate.
> - **12-16:** The pressure plate is deactivated but the creature is slowed (EoT).
> - **17+:** The pressure plate is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> The pressure plate is calibrated to be triggered by creatures or objects of a particular size. The pressure plate triggers when a creature or object of the appropriate size enters its area.
>
> **Effect:** The linked mechanism is activated. A pressure plate automatically resets and can be triggered repeatedly.

<!-- -->
> ⭐️ **Upgrade**
>
> **Tripwire (−1 EV)** The pressure plate is a tripwire, which can trigger once and must be manually reset. A concealed tripwire can be discovered with an **easy Intuition test**.

<!-- -->
> ⭐️ **Hidden**
>
> The pressure plate is hidden until triggered or detected.

###### Pulley (Level 1 Trigger Support)

A counterweighted pulley system can be used to quickly ascend to the top of a wall, scaffold, tower, or other structure.

- **EV:** 1
- **Stamina:** 1
- **Size:** 1S

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a pulley can make an **Agility test**.
>
> - **≤11:** The creature triggers the pulley.
> - **12-16:** The pulley is deactivated but the creature is slowed (EoT).
> - **17+:** The pulley is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> A creature adjacent to the pulley uses a maneuver to release the pulley.
>
> **Effect:** The triggering creature is lifted to the top of the structure the pulley is attached to. The pulley must be manually reset.

<!-- -->
> ⭐️ **Climbable**
>
> A creature adjacent to the pulley can climb its ropes with an **easy Agility test** to ascend to the top of the structure it's attached to.

<!-- -->
> ⭐️ **Upgrade**
>
> **Looped Chain (+1 EV)** Instead of a rope and pulley, the system uses a counterweighted looped chain. A looped chain automatically resets and can be triggered repeatedly.

###### Ram (Level 2 Trap Ambusher)

A heavy wooden ram drops down or swings into the fray, crushing all in its path.

- **EV:** 3
- **Stamina:** 3 per square
- **Size:** Any area; the area can't be moved through
- **Typical Space:** 1 x 3-square area or a 2 x 2-square area
- **Direction:** One side of the ram is defined as the front.

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a ram can make an **Agility test**.
>
> - **≤11:** The creature triggers the ram and is affected as if in its space.
> - **12-16:** The ram is deactivated but the creature is slowed (EoT).
> - **17+:** The ram is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> A pressure plate, switch, or other linked trigger is activated.
>
> **Effect:** The **Ram** ability.

<!-- -->
> ❗️ **Ram**
>
> | **Area, Weapon** |                   **Free triggered action** |
> | ---------------- | ------------------------------------------: |
> | **📏 Special**   | **🎯 Each creature and object in the area** |
>
> **Trigger:** A pressure plate, switch, or other linked trigger is activated.
>
> **Special:** The area of this ability is the path the ram moves through from its starting position.
>
> **Power Roll + 2:**
>
> - **≤11:** 3 damage; slide 1, ignoring stability
> - **12-16:** 6 damage; push 3
> - **17+:** 9 damage; push 5
>
> **Effect:** A target slid by the ram ends up on one side of it or the other (choose randomly). The ram must be manually reset.

<!-- -->
> ⭐️ **Upgrades**
>
> **Stone (+1 EV)** The ram is made of stone, has 6 Stamina per square, and deals an extra 1d3 damage.
>
> **Metal (+2 EV)** The ram is made of metal, has 9 Stamina per square, and deals an extra 1d6 damage.
>
> **Repeating (+1 EV)** The ram automatically resets at the start of each round.
>
> **Rapid Repeating (+3 EV)** The ram automatically resets at the start of each turn.
>
> **Multiple Rams (+3 EV per additional ram)** Multiple rams can be used to represent a larger mechanism, such as a stack of tumbling logs.

<!-- -->
> ⭐️ **Hidden**
>
> The ram is hidden until triggered or detected.

###### Switch (Level 1 Trigger Support)

Set into any surface, this mechanism acts as a trigger for another linked mechanism.

- **EV:** 1
- **Stamina:** 3
- **Size:** 1T
- **Link:** A switch is linked to another mechanism that it activates when triggered.

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a switch can make an **Agility test**.
>
> - **≤11:** The creature triggers the switch.
> - **12-16:** The switch is deactivated but the creature is slowed (EoT).
> - **17+:** The switch is deactivated and doesn't trigger.

<!-- -->
> ❕ **Activate**
>
> A creature adjacent to the switch uses a maneuver to trigger it.
>
> **Effect:** The linked mechanism is activated. A switch automatically resets and can be triggered repeatedly.

<!-- -->
> ⭐️ **Upgrade**
>
> **Concealed (+1 EV)** The switch is hidden.

### Power Fixtures

Power fixtures are especially potent fortifications for solo creatures and smaller strike forces. The more of these terrain objects that occupy the field of battle, the worse things get for the attacking side.

###### Holy Idol (Level 5 Relic Support)

An empowering monument to a higher power enables a villain's machinations.

- **EV:** 7
- **Stamina:** 35
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> The holy idol must be completely destroyed.

<!-- -->
> ⭐️ **Empowered Will**
>
> At the start of each round while the holy idol is intact, the Director gains a d6 that lasts until the end of the round. When a Director-controlled creature deals or takes damage, the Director can roll the d6 to increase the damage the creature deals or reduce the damage the creature takes by an amount equal to the roll (to a minimum of 2 damage). If multiple idols are in play, only one d6 can be applied to a single instance of damage.

###### Psionic Shard (Level 5 Fortification Defender)

A massive humming crystal makes the air around it feel thick.

- **EV:** 7
- **Stamina:** 40
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> The psionic shard must be completely destroyed.

<!-- -->
> ⭐️ **Psionic Barrier**
>
> A psionic shard is attuned to one side in an encounter. While a psionic shard is intact, any damage dealt to each ally of the shard in the encounter is halved.

<!-- -->
> ❗️ **Psionic Pulse**
>
> | **-**          | **Free triggered action** |
> | -------------- | ------------------------: |
> | **📏 Special** |            **🎯 Special** |
>
> **Trigger:** The shard is destroyed.
>
> **Effect:** The shard releases a shockwave channeled through each creature affected by Psionic Barrier. Each ally in the encounter is dazed until the end of their next turn.

###### Tree of Might (Level 5 Hazard Hexer)

A gnarled tree has unearthed roots that writhe and curl.

- **EV:** 14
- **Stamina:** 60
- **Size:** 3
- **Immunity:** 5 to all damage except corruption or fire damage

<!-- -->
> 🌀 **Deactivate**
>
> The tree of might must be completely destroyed.

<!-- -->
> ⭐️ **Tree's Nourishment**
>
> At the start of each round while the tree of might is intact, each enemy touching the ground in the encounter area who has M < 0 takes 10 corruption damage, and the tree of might grows a fruit. The potency increases by 1 each subsequent round.

<!-- -->
> ⭐️ **Mighty Fruit**
>
> Once per round, any creature adjacent to the tree of might can take a fruit from the tree and eat it (no action required). The creature gains 10 temporary Stamina and has their Might score increased by 1 (to a maximum of 6) until the end of the encounter.

### Siege Engines

Siege engines are powerful weapons that require a team of creatures to operate and move. These weapons can scale in size from smaller field artillery to massive mechanisms that can destroy buildings.

#### Adjacent Creature Main Actions

Rather than siege engines taking actions on their own, a creature adjacent to the siege engine can use a main action to activate a siege engine ability noted as "Main action (Adjacent creature)." In addition to their primary attack, some siege engines require an adjacent creature main action to reload them once they are used, while others have adjacent creature main actions allowing them to be moved or allowing a creature to improve the engine's distance and accuracy.

Multiple minions in a squad can activate different aspects of a siege engine using adjacent creature main actions.

###### Arrow Launcher (Level 2 Siege Engine Artillery)

A small wooden cart uses alchemical rockets to launch up to a hundred arrows at a time across a wide area.

- **EV:** 8
- **Stamina:** 30
- **Size:** 1L

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to an arrow launcher can make an **Agility test**.
>
> - **≤11:** The creature accidentally activates the **Arrow Storm** ability.
> - **12-16:** The arrow launcher is deactivated but the creature is slowed (EoT).
> - **17+:** The arrow launcher is deactivated and can't be used.

<!-- -->
> 🔳 **Arrow Storm**
>
> | **- Area, Ranged, Weapon** |         **Main action (Adjacent creature)** |
> | -------------------------- | ------------------------------------------: |
> | **📏 5 cube within 20**    | **🎯 Each creature and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 8 damage
> - **17+:** 11 damage
>
> **Effect:** This ability can't be used again until the arrow launcher is reloaded.

<!-- -->
> ⭐️ **Reload**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The arrow launcher is reloaded, allowing **Arrow Storm** to be used again. This action can be used only once per round.

<!-- -->
> ⭐️ **Spot**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The next use of **Arrow Storm** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.

<!-- -->
> ⭐️ **Move**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The arrow launcher and the creature using this action move together up to 3 squares.

<!-- -->
> ⭐️ **Upgrades**
>
> **Flaming Arrows (+1 EV) Arrow Storm** deals fire damage, and can ignite flammable objects in its area.
>
> **Screamers (+3 EV)** The arrows make a high-pitched screaming noise as they are fired and descend onto their targets. The **Screamers** ability replaces **Arrow Storm**.

<!-- -->
> 🔳 **Screamers**
>
> | **Area, Ranged, Weapon** |         **Main action (Adjacent creature)** |
> | ------------------------ | ------------------------------------------: |
> | **📏 5 cube within 20**  | **🎯 Each creature and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; R < 0 dazed (save ends)
> - **12-16:** 8 damage; R < 1 dazed (save ends)
> - **17+:** 11 damage; R < 2 frightened (save ends)
>
> **Effect:** This ability can't be used again until the arrow launcher is reloaded.

###### Boiling Oil Cauldron (Level 3 Fortification Defender)

A large cauldron of boiling oil stands ready to be poured onto enemies.

- **EV:** 10
- **Stamina:** 50
- **Size:** 1L

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a boiling oil cauldron can make an **Agility test**.
>
> - **≤11:** The creature accidentally activates the **Boiling Oil** ability.
> - **12-16:** The boiling oil cauldron is deactivated but the creature is slowed (EoT).
> - **17+:** The boiling oil cauldron is deactivated and can't be used.

<!-- -->
> 🔳 **Boiling Oil**
>
> | **Area, Weapon**       |         **Main action (Adjacent creature)** |
> | ---------------------- | ------------------------------------------: |
> | **📏 3 cube within 1** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 fire damage; M < 1 burning (save ends)
> - **12-16:** 9 fire damage; M < 2 burning (save ends)
> - **17+:** 12 fire damage; M < 3 burning (save ends)
>
> **Effect:** If the boiling oil is poured down on targets from above, it has high ground and gains an edge on the power roll. A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round. This ability can't be used again until the boiling oil cauldron is reloaded.

<!-- -->
> ⭐️ **Reload**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The boiling oil cauldron is reloaded, allowing **Boiling Oil** to be used again. This action can be used only once per round.

###### Catapult (Level 3 Siege Engine Artillery)

This massive counterweighted engine hurls a heavy projectile for a devastating assault.

- **EV:** 10
- **Stamina:** 50
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a catapult can make an **Agility test**.
>
> - **≤11:** The creature accidentally activates the **Arcing Shot** ability.
> - **12-16:** The catapult is deactivated but the creature is slowed (EoT).
> - **17+:** The catapult is deactivated and can't be used.

<!-- -->
> 🔳 **Arcing Shot**
>
> | **- Area, Ranged, Weapon** |         **Main action (Adjacent creature)** |
> | -------------------------- | ------------------------------------------: |
> | **📏 3 cube within 20**    | **🎯 Each creature and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 9 damage; A < 0 push 1
> - **17+:** 12 damage; A < 1 push 2
>
> **Effect:** Line of effect for this ability is an arc that can be traced over obstacles between the catapult and the target area. This ability can't be used again until the catapult is reloaded.

<!-- -->
> ⭐️ **Reload**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The catapult is reloaded, allowing **Arcing Shot** to be used again. This action can be used only once per round.

<!-- -->
> ⭐️ **Spot**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The next use of **Arcing Shot** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.

<!-- -->
> ⭐️ **Move**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The catapult and the creature using this action move together up to 2 squares.

<!-- -->
> ⭐️ **Upgrades**
>
> **Air Assault (+2 EV)** The side fielding the catapult has trained their forces to safely use the siege engine to launch them across the battlefield. As an adjacent creature main action, the catapult can be used to vertical push 10 any ally of size 1L or less. If the ally lands in an unoccupied space, they take no damage.
>
> **Flammable (+2 EV) Arcing Shot** deals fire damage, and the area of that ability is on fire until the end of the encounter. Any creature who enters the area for the first time in a round or starts their turn there takes 2 fire damage.

###### Exploding Mill Wheel (Level 3 Siege Engine Artillery)

A massive wooden wheel is loaded with explosives and rolled toward enemy forces or fortifications, ready to explode.

- **EV:** 10
- **Stamina:** 25
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to an exploding mill wheel that isn't rolling can make an **Agility test**.
>
> - **≤11:** The creature accidentally activates the **Roll the Wheel** ability.
> - **12-16:** The exploding mill wheel is deactivated but the creature is slowed (EoT).
> - **17+:** The exploding mill wheel is deactivated and can't be used.
>
> Once the wheel is rolling, it can't be deactivated. However, it can be exploded early by destroying it or blocking its movement with a suitably large creature or object.

<!-- -->
> 🌀 **Roll the Wheel**
>
> | **Area**       |         **Main action (Adjacent creature)** |
> | -------------- | ------------------------------------------: |
> | **📏 Special** | **🎯 Each creature and object in the area** |
>
> **Effect:** When this ability is used and at the start of every turn thereafter, the exploding mill wheel rolls, moving 2 squares in a straight line. Each creature and object of size 2 or smaller in the area defined by the wheel's movement is targeted by the following power roll. A target force moved this way is moved to either side of the wheel, as the Director determines.
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; push 1
> - **12-16:** 9 damage; push 2
> - **17+:** 12 damage; push 3
>
> If the wheel enters the space of any creature or object of size 3 or larger, or if it is reduced to 0 Stamina, its movement stops and it explodes. Each creature and object in a 5 burst centered on the wheel is targeted by the following power roll.
>
> - **≤11:** 5 damage; push 1; M < 0 burning (save ends)
> - **12-16:** 9 damage; push 2; M < 1 burning (save ends)
> - **17+:** 12 damage; push 3; M < 2 burning (save ends)
>
> A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round.

<!-- -->
> ⭐️ **Upgrade**
>
> **Piloted (+4 EV)** The wheel has been fitted with a control mechanism and a pilot's seat for a creature of size 1M or smaller. As a move action, the pilot can turn the wheel in any direction while it is moving. As a main action, the pilot can leap out of the pilot's seat, landing in an adjacent space while the wheel continues moving in a straight line.
>
> Without proper training, determining how to pilot the wheel requires a **Reason test**.
>
> - **≤11:** The wheel immediately explodes as if striking a size 3 or larger creature or object.
> - **12-16:** The creature fails to pilot the wheel.
> - **17+:** The creature can pilot the wheel.
>
> On a natural 19 or 20, a creature can both pilot the wheel and can disarm its explosives as a maneuver.

###### Field Ballista (Level 2 Siege Engine Artillery)

A massive crossbow fires thick metal bolts with devastating effect.

- **EV:** 8
- **Stamina:** 40
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to a field ballista can make an **Agility test**.
>
> - **≤11:** The creature accidentally activates the **Release Bolt** ability.
> - **12-16:** The field ballista is deactivated but the creature is slowed (EoT).
> - **17+:** The field ballista is deactivated and can't be used.

<!-- -->
> 🏹 **Release Bolt**
>
> | **Ranged, Strike, Weapon** | **Main action (Adjacent creature)** |
> | -------------------------- | ----------------------------------: |
> | **📏 Ranged 20**           |       **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage
> - **12-16:** 8 damage; M < 1 push 1
> - **17+:** 11 damage; M < 2 push 2
>
> **Effect:** This ability can't be used again until the field ballista is reloaded.

<!-- -->
> ⭐️ **Reload**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The field ballista is reloaded, allowing **Release Bolt** to be used again. This action can be used only once per round.

<!-- -->
> ⭐️ **Spot**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |

**Effect:** The next use of **Release Bolt** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.

<!-- -->
> ⭐️ **Move**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The field ballista and the creature using this action move together up to 3 squares.

<!-- -->
> ⭐️ **Upgrades**
>
> **Penetrating Bolt (+2 EV)** The field ballista targets the nearest two additional creatures or objects in a straight line beyond the initial target.
>
> **Chain Bolt (+2 EV)** The field ballista's bolts are set with heavy chains that wrap around targets. The **Chain Bolt** ability replaces **Release Bolt**, and the field ballista gains the **Crank the Chain** ability.
>
> 🏹 **Chain Bolt**
>
> | **- - Ranged, Strike, Weapon** | **Main action (Adjacent creature)** |
> | ------------------------------ | ----------------------------------: |
> | **📏 Ranged 20**               |       **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 7 damage; M < 1 slowed (save ends)
> - **17+:** 10 damage; M < 2 slowed (save ends)
>
> **Effect:** This ability can't be used again until the field ballista is reloaded.
>
> 🏹 **Crank the Chain**
>
> | **Ranged, Strike, Weapon** | **Main action (Adjacent creature)** |
> | -------------------------- | ----------------------------------: |
> | **📏 Ranged 20**           |                 **🎯 One creature** |
>
> **Special:** The target must be slowed by the field ballista.
>
> **Power Roll + 2:**
>
> - **≤11:** Pull 1
> - **12-16:** Pull
> - **17+:** 3 Pull 5
>
> **Effect:** This forced movement triggers opportunity attacks.

###### Iron Dragon (Level 4 Siege Engine Artillery)

A massive metal device uses a bellows system and liquid fuel to shoot out gouts of flame.

- **EV:** 12
- **Stamina:** 60
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to an iron dragon can make an **Agility test**.
>
> - **≤11:** The creature accidentally activates the **Gout of Flame** ability.
> - **12-16:** The iron dragon is deactivated but the creature is slowed (EoT).
> - **17+:** The iron dragon is deactivated and can't be used.

<!-- -->
> 🔳 **Gout of Flame**
>
> | **Area, Weapon**           |         **Main action (Adjacent creature)** |
> | -------------------------- | ------------------------------------------: |
> | **📏 8 x 2 line within 1** | **🎯 Each creature and object in the area** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 fire damage; A < 0 the target is burning (save ends)
> - **12-16:** 10 fire damage; A < 1 the target is burning (save ends)
> - **17+:** 13 fire damage; A < 2 the target is burning (save ends)
>
> **Effect:** A burning creature takes 1d6 fire damage at the start of each of their turns. A burning object takes 1d6 fire damage at the end of each round. This ability can't be used again until the iron dragon is reloaded.

<!-- -->
> ⭐️ **Reload**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The iron dragon is reloaded, allowing **Gout of Flame** to be used again. This action can be used only once per round.

<!-- -->
> ⭐️ **Spot**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The next use of **Gout of Flame** gains an edge and has a +10 bonus to ranged distance. This action can be used only once per round.

<!-- -->
> ⭐️ **Move**
>
> | **-**    | **Main action (Adjacent creature)** |
> | -------- | ----------------------------------: |
> | **📏 -** |                            **🎯 -** |
>
> **Effect:** The iron dragon and the creature using this action move together up to 2 squares.

###### Watchtower (Level 2 Fortification Defender)

A sturdy wooden tower accessed by interior ladders or stairs provides cover and high ground for attackers.

- **EV:** 8
- **Stamina:** 50
- **Size:** 3

<!-- -->
> 🌀 **Deactivate**
>
> The watchtower must be completely destroyed.

<!-- -->
> ⭐️ **High Ground and Cover**
>
> Creatures who have access to the watchtower's interior ladders or stairs have high ground and cover against creatures outside the watchtower.

<!-- -->
> 🌀 **Getting Inside**
>
> A creature outside and adjacent to the watchtower can gain access to the interior by climbing it as an **Agility test** or breaking into it with a **Might test**.
>
> - **≤11:** 1d6 damage; the creature remains outside the watchtower
> - **12-16:** The creature remains outside the watchtower.
> - **17+:** The creature gains access to the watchtower.

<!-- -->
> ⭐️ **Upgrades**
>
> **Ballista Emplacement (+12 EV)** The watchtower is equipped with a field ballista that can be used by creatures in the watchtower. The ballista can't be moved.
>
> **Boiling Oil Cauldron (+17 EV)** The watchtower is equipped with a boiling oil cauldron that can be used by creatures in the watchtower.
>
> **Spyglass (+2 EV)** Any creature in the watchtower can use the spyglass to search for hidden creatures around the tower, gaining an edge on the Intuition test and increasing the distance at which creatures can be spotted to 15 squares.
>
> **Stone Tower (+2 EV)** The watchtower is reinforced with stone and has 75 Stamina.
>
> **Iron Tower (+4 EV)** The watchtower is reinforced with stone and iron and has 100 Stamina.

### Supernatural Objects

Infused with magic or psionics, these powerful and esoteric terrain objects can provide a strong environmental threat, or even be the centerpiece of an encounter.

<!-- -->
> **Objects With Enemies?**
>
> Supernatural objects are unique in having effects that target or affect enemies and allies. Although supernatural objects don't (necessarily) have awareness or sapience, their presence in an encounter aligns them clearly with or against the heroes. Unless the Director determines otherwise, the heroes are usually the enemies of a supernatural object.

###### The Black Obelisk (Level 3 Relic Controller)

A foreboding obelisk shaped of dark stone harrows the minds and spirits of those around it.

- **EV:** 20
- **Stamina:** 100
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> As a maneuver, a creature adjacent to the black obelisk can make a **Reason test**.
>
> - **≤11:** The creature accidentally activates the **Your Fears Become Manifest** ability, which gains an edge.
> - **12-16:** The creature must make another test to deactivate the obelisk. If they obtain this outcome a second time, they accidentally activate **Your Fears Become Manifest**.
> - **17+:** The obelisk is deactivated until the end of the encounter.

<!-- -->
> ❕ **Activate**
>
> A new round starts.
>
> **Effect:** The **Your Fears Become Manifest** ability.

<!-- -->
> ❗️ **Your Fears Become Manifest**
>
> | **Area, Magic** |     **Free triggered action** |
> | --------------- | ----------------------------: |
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Trigger:** A new round starts.
>
> **Power Roll + 2:**
>
> - **≤11:** P < 1 slowed (EoT)
> - **12-16:** P < 2 slowed and weakened (EoT)
> - **17+:** P < 3 frightened, slowed, and weakened (EoT)
>
> **Effect:** The target is pushed 2 squares.

###### The Chronal Hypercube (Level 3 Relic Controller)

This unnatural object twists space around it in a reflection of its own unnatural form.

- **EV:** 20
- **Stamina:** 80
- **Size:** 1M

<!-- -->
> 🌀 **Deactivate**
>
> A creature who has the Psionics skill can deactivate and take control of the chronal hypercube by making a **Reason test** while within 10 squares of the hypercube.
>
> - **≤11:** The creature takes 1d6 psychic damage.
> - **12-16:** The creature fails to deactivate the hypercube.
> - **17+:** The hypercube teleports adjacent to the creature at the start of the next round and becomes an ally to the creature and their allies.

<!-- -->
> ⭐️ **Dimensional Flicker**
>
> At the start of each round while the hypercube is present, roll a d10. On a 7 or higher, the hypercube teleports to a square of one ally's choice within 10 squares and is hidden. While the hypercube is hidden, Psionics is the only skill that can be applied to a test made to find it.

<!-- -->
> ⭐️ **Chronal Superhighway**
>
> Any ally within 10 squares of the hypercube can teleport when they move. An ally who teleports gains an edge on the next power roll they make.

###### The Throne of A'An (Level 4 Relic Controller)

The throne of A'An, sun god of the Antical Protectorate in what is now Vanigar, retains some of her power from the age before she was slain to end the Age of Suns—and plunge the region into eternal winter.

- **EV:** 24
- **Stamina:** 140
- **Size:** 2

<!-- -->
> 🌀 **Deactivate**
>
> The throne of A'An can be deactivated only by the current hierophant of A'An (see **Sitting on the Throne**), who must succeed on a **Presence test** that takes a bane to do so.
>
> - **≤11:** The hierophant triggers the **Nova** ability.
> - **12-16:** The hierophant fails to deactivate the throne.
> - **17+:** The throne is deactivated until the end of the encounter.

<!-- -->
> ⭐️ **Light of the Northern Sun**
>
> In the Age of Suns, there was no darkness and no night. Even among the many suns of that time, the light of A'An was the brightest. The throne of A'An manifests the sun powers of that god, even when no one is seated in it. The following effects always occur within 10 squares of the throne:
>
> - The throne sheds bright light that negates all darkness and concealment, and which prevents creatures from being hidden.
> - Any creature with cold immunity has fire weakness 10.
> - Any creature who uses an ability that deals cold damage takes 11 fire damage.

<!-- -->
> ⭐️ **Sitting on the Throne**
>
> Only a creature attuned to the throne can sit on it. A creature adjacent to the throne can use a main action to attune to it by succeeding on a **Presence test**.
>
> - **≤11:** The creature takes 11 fire damage.
> - **12-16:** The creature fails to attune to the throne.
> - **17+:** The creature attunes to the throne and can sit on it.
>
> A creature seated on the throne becomes the hierophant of A'An and gains the following benefits:
>
> - The hierophant and each of their allies within 10 squares of the throne have fire immunity 10.
> - The hierophant and each of their allies within 10 squares of the throne can choose to have their abilities deal fire damage instead of their usual damage.
> - The hierophant has a +5 bonus to stability, and any strike made against them takes a bane unless the attacker is also attuned to the throne.
> - The hierophant can use the **Primordial Flare** and **Solar Accretion** abilities.

<!-- -->
> 🏹 **Primordial Flare**
>
> | **Magic, Ranged, Strike** |                  **Maneuver** |
> | ------------------------- | ----------------------------: |
> | **📏 Ranged 20**          | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 fire damage
> - **12-16:** 11 fire damage
> - **17+:** 14 fire damage
>
> **Effect:** The target has fire weakness 10 until the start of the hierophant's next turn.

<!-- -->
> ❗️ **Solar Accretion**
>
> | **Magic, Ranged** | **Free triggered action** |
> | ----------------- | ------------------------: |
> | **📏 Ranged 10**  |       **🎯 One creature** |
>
> **Trigger:** A target within distance is made winded or is reduced to 0 Stamina by fire damage.
>
> **Effect:** If the hierophant is a hero, they gain 3 of their Heroic Resource. If the hierophant is a Director-controlled creature, the Director gains 3 Malice.

<!-- -->
> ❗️ **Nova**
>
> | **Area, Magic** |                   **Free triggered action** |
> | --------------- | ------------------------------------------: |
> | **📏 10 burst** | **🎯 Each creature and object in the area** |
>
> **Trigger:** The throne is destroyed or the hierophant obtains a tier 1 outcome on the test to deactivate it.
>
> **Effect:** Each target takes 14 fire damage and the Hierophant gains the Incubator of A'An complication (see the sidebar). If there is no hierophant, one creature within 10 squares of the throne chosen by the Director gains this complication.

###### Incubator of A'An

<!-- -->
> **Incubator of A'An**
>
> A shard of the formerly dead sun god A'An incubates within your body, guiding you so that A'An can be restored to her true glory by earning one hundred disciples.
>
> (This complication should be introduced to a campaign only with caution, and with the understanding that all the players are happy to have the party's agency affected by one of the characters roleplaying a forgotten god.)
>
> **Benefit:** You have all the abilities of the Sun domain as if you were a conduit of your level. Additionally, you gain fire immunity 5. If you succeed in resurrecting A'An, you will become a saint of A'An.
>
> **Drawback:** You have cold weakness 5. Whenever you finish a respite and you have not recruited a new disciple of A'An since your last respite, make a **Presence test**.
>
> - **≤11:** A'An possesses your body until your next respite. You now must roleplay A'An trapped in your form, prioritizing earning new disciples.
> - **12-16:** You lose a Recovery.
> - **17+:** You suffer no effect

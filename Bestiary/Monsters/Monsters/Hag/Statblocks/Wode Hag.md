---
agility: 1
ancestry:
  - Fey
  - Hag
ev: '60'
file_basename: Wode Hag
file_dpath: Monsters/Hag/Statblocks
free_strike: 6
intuition: 3
item_id: wode-hag
item_index: '01'
item_name: Wode Hag
level: 3
might: 2
presence: 3
reason: 1
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.hag.statblock:wode-hag
scdc:
  - 1.1.1:2.36.1:01
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: '300'
type: monster/hag/statblock
---

###### Wode Hag

|      Fey, Hag       |              -               |       Level 3        |          Solo           |         EV 60          |
| :-----------------: | :--------------------------: | :------------------: | :---------------------: | :--------------------: |
|  **1L**<br/> Size   |       **5**<br/> Speed       | **300**<br/> Stamina |  **1**<br/> Stability   | **6**<br/> Free Strike |
| **-**<br/> Immunity | **Fly, hover**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|  **+2**<br/> Might  |     **+1**<br/> Agility      |  **+1**<br/> Reason  |  **+3**<br/> Intuition  |  **+3**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the hag can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The hag can take two turns each round. They can't take turns consecutively.

<!-- -->
> ⭐️ **Supernatural Resistance**
>
> Magic and psionic abilities used against the hag take a bane.

<!-- -->
> 🗡 **Corrosive Claws (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> | ------------------------- | ------------------------------: |
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 corruption damage; A < 1 weakened (save ends)
> - **12-16:** 13 corruption damage; A < 2 weakened (save ends)
> - **17+:** 16 corruption damage; A < 3 weakened (save ends)

<!-- -->
> 🔳 **Soul Steal**
>
> | **Area, Magic**        |               **Main action** |
> | ---------------------- | ----------------------------: |
> | **📏 4 cube within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 corruption damage; P < 1 4 corruption damage
> - **12-16:** 8 corruption damage; P < 2 5 corruption damage
> - **17+:** 10 corruption damage; P < 3 6 corruption damage
>
> **Effect:** This ability gains an edge against a target who has a soul.
>
> **3 Malice:** The hag regains Stamina equal to half the damage dealt.

<!-- -->
> 👤 **Shapeshifter**
>
> | **Magic**   | **Maneuver** |
> | ----------- | -----------: |
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The hag alters their body to become any size 1 creature, from a house cat to a humanoid. If the hag uses this ability while outside of any enemy's line of effect, they can choose to be automatically hidden. The hag can return to their original form as a free maneuver.
>
> **5 Malice:** The hag becomes a size 2 creature instead, from a bear to an ogre. While in this form, the hag's melee abilities gain a +1 bonus to distance and deal an extra 4 damage.

<!-- -->
> ❗️ **Turned Upside Down (2 Malice)**
>
> | **Area, Magic** |          **Triggered action** |
> | --------------- | ----------------------------: |
> | **📏 1 burst**  | **🎯 Each enemy in the area** |
>
> **Trigger:** A creature targets the hag with a melee strike.
>
> **Power Roll + 3:**
>
> - **≤11:** Slide 2; R < 1 the slide is vertical
> - **12-16:** Slide 3; R < 2 the slide is vertical, and the target is restrained (EoT)
> - **17+:** Vertical slide 5; R < 3 restrained (EoT)
>
> **Effect:** While restrained this way, a creature who is vertical force moved is suspended in midair. The creature falls when the condition ends.

<!-- -->
> ☠️ **Snackies for Sweeties (Villain Action 1)**
>
> | **Area, Magic** |                            **-** |
> | --------------- | -------------------------------: |
> | **📏 5 burst**  | **🎯 Each creature in the area** |
>
> **Effect:** The hag attaches an ornate explosive pastry to each target who has A < 2. At the end of the round, the hag makes one power roll against each creature with a pastry attached to them.
>
> **Power Roll + 3:**
>
> - **≤11:** 6 poison damage
> - **12-16:** 10 poison damage
> - **17+:** 13 poison damage
>
> **Special:** A creature wearing a pastry or adjacent to a creature wearing a pastry can attempt an **Agility test** to remove the pastry as a maneuver.
>
> - **≤11:** The hag makes the power roll for all pastries.
> - **12-16:** The pastry is not removed.
> - **17+:** The pastry is removed and can no longer explode.

<!-- -->
> ☠️ **Predator's Alacrity (Villain Action 2)**
>
> | **Area, Weapon** |                         **-** |
> | ---------------- | ----------------------------: |
> | **📏 1 burst**   | **🎯 Each enemy in the area** |
>
> **Effect:** Before using this villain action, the hag shifts up to their speed. They then use Corrosive Claws against each target, push each target up to 2 squares, and shift up to their speed again.

<!-- -->
> ☠️ **Open the Oven (Villain Action 3)**
>
> | **Area, Weapon**       |                            **-** |
> | ---------------------- | -------------------------------: |
> | **📏 5 cube within 1** | **🎯 Each creature in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 fire damage; A < 1 weakened (save ends)
> - **12-16:** 10 fire damage; A < 2 weakened (save ends)
> - **17+:** 13 fire damage; A < 3 weakened (save ends)
>
> **Effect:** The hag turns the area into a roiling oven until the end of the encounter. Any creature in area takes an extra 5 damage from the hag's damage-dealing abilities.

---
agility: 2
ancestry:
  - Goblin
  - Hobgoblin
  - Humanoid
  - Infernal
ev: '32'
file_basename: Hobgoblin Bloodlord
file_dpath: Monsters/Hobgoblins/Statblocks
free_strike: 7
intuition: 3
item_id: hobgoblin-bloodlord
item_index: '10'
item_name: Hobgoblin Bloodlord
level: 6
might: 4
presence: 3
reason: 2
roles:
  - Leader
scc:
  - mcdm.monsters.v1:monster.hobgoblins.statblock:hobgoblin-bloodlord
scdc:
  - 1.1.1:2.21.1:10
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: '180'
type: monster/hobgoblins/statblock
---

###### Hobgoblin Bloodlord

| Goblin, Hobgoblin, Humanoid, Infernal |             -              |       Level 6        |         Leader          |         EV 32          |
| :-----------------------------------: | :------------------------: | :------------------: | :---------------------: | :--------------------: |
|           **1M**<br/> Size            |      **6**<br/> Speed      | **180**<br/> Stamina |  **2**<br/> Stability   | **7**<br/> Free Strike |
|       **Fire 6**<br/> Immunity        | **Teleport**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|           **+4**<br/> Might           |    **+2**<br/> Agility     |  **+2**<br/> Reason  |  **+3**<br/> Intuition  |  **+3**<br/> Presence  |

<!-- -->
> 🗡 **Soul Sword (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |                 **Main action** |
> | -------------------------------- | ------------------------------: |
> | **📏 Melee 1**                   | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 corruption damage; P < 2 bleeding (save ends)
> - **12-16:** 16 corruption damage; P < 3 bleeding (save ends)
> - **17+:** 19 corruption damage; P < 4 bleeding (save ends)
>
> **2 Malice:** Each target is marked until the end of the encounter or until they die. The bloodlord's allies gain an edge on strikes against any target marked this way. The bloodlord can have up to three targets marked this way. If they mark a new target who would exceed the limit, the oldest mark ends.

<!-- -->
> 🏹 **Take Point!**
>
> | **Ranged**       |    **Maneuver** |
> | ---------------- | --------------: |
> | **📏 Ranged 10** | **🎯 One ally** |
>
> **Effect:** The target moves up to their speed and can use a signature ability.

<!-- -->
> ❗️ **An Army From Blood (3 Malice)**
>
> | **Ranged**       |           **Triggered action** |
> | ---------------- | -----------------------------: |
> | **📏 Ranged 10** | **🎯 The triggering creature** |
>
> **Trigger:** A non-minion hobgoblin within distance takes damage.
>
> **Effect:** Three hobgoblin recruits manifest from the target's blood into unoccupied spaces adjacent to the target.

<!-- -->
> ⭐️ **Infernal Ichor**
>
> When the bloodlord is reduced to 0 Stamina, they spray burning blood. Each creature adjacent to the bloodlord takes 3 fire damage.

<!-- -->
> ⭐️ **End Effect**
>
> At the end of each of their turns, the bloodlord can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

<!-- -->
> ☠️ **Advance! (Villain Action 1)**
>
> | **Area**        |                                 **-** |
> | --------------- | ------------------------------------: |
> | **📏 10 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target gains 10 temporary Stamina and can move up to their speed. Then each non-minion target can make a free strike.

<!-- -->
> ☠️ **Skulls Abound (Villain Action 2)**
>
> | **Area, Magic** |       **-** |
> | --------------- | ----------: |
> | **📏 3 aura**   | **🎯 Self** |
>
> **Effect:** Until the end of the encounter, the bloodlord surrounds themself with a storm of flying skulls. Any enemy who enters the area for the first time in a round or starts their turn there takes 8 corruption damage and takes a bane on their next power roll until the start of their next turn.

<!-- -->
> ☠️ **I Am Fire! I Am Death! (Villain Action 3)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 5 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 5 fire damage; P < 2 2 fire damage, push 2, prone
> - **12-16:** 5 fire damage; P < 3 7 fire damage, push 3, prone
> - **17+:** 5 fire damage; P < 4 10 fire damage, push 5, prone
>
> **Effect:** Until the end of the encounter, the bloodlord is wreathed in black flames. Whenever any adjacent enemy grabs the bloodlord or uses a melee ability against them, that enemy takes 5 corruption damage.

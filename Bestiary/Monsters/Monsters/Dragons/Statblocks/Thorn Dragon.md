---
agility: 3
ancestry:
  - Dragon
  - Elemental
ev: '48'
file_basename: Thorn Dragon
file_dpath: Monsters/Dragons/Statblocks
free_strike: 5
intuition: 1
item_id: thorn-dragon
item_index: '05'
item_name: Thorn Dragon
level: 2
might: 2
presence: 2
reason: -1
roles:
  - Solo
scc:
  - mcdm.monsters.v1:monster.dragons.statblock:thorn-dragon
scdc:
  - 1.1.1:2.45.1:05
size: '3'
source: mcdm.monsters.v1
speed: 8
stability: 6
stamina: '250'
type: monster/dragons/statblock
---

###### Thorn Dragon

|     Dragon, Elemental      |           -           |       Level 2        |          Solo           |         EV 48          |
| :------------------------: | :-------------------: | :------------------: | :---------------------: | :--------------------: |
|      **3**<br/> Size       |   **8**<br/> Speed    | **250**<br/> Stamina |  **6**<br/> Stability   | **5**<br/> Free Strike |
| **Poison 5**<br/> Immunity | **Fly**<br/> Movement |          -           | **-**<br/> With Captain |  **-**<br/> Weakness   |
|     **+2**<br/> Might      |  **+3**<br/> Agility  |  **-1**<br/> Reason  |  **+1**<br/> Intuition  |  **+2**<br/> Presence  |

<!-- -->
> ☠️ **Solo Monster**
>
> **End Effect:** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

<!-- -->
> ❇️ **Withering Wyrmscale Aura**
>
> The dragon's scales create a 2 aura of withering green magic around them. Any creature other than the dragon who regains Stamina in the area regains only half the expected amount. Any winded creature who enters the area for the first time in a round or starts their turn there takes 1d3 corruption damage.

<!-- -->
> 🔳 **Virulent Breath (Signature Ability)**
>
> | **Area, Magic**             |                          **Main action** |
> | --------------------------- | ---------------------------------------: |
> | **📏 10 x 1 line within 1** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes a **Might test**.
>
> - **≤11:** 12 poison damage; the target is dragonsealed (save ends)
> - **12-16:** 9 poison damage; the target is dragonsealed (save ends)
> - **17+:** 5 poison damage
>
> A dragonsealed creature has their wounds bound by nettles and thorns, causing them to take an extra 1d3 damage whenever they take damage rolled as a d6 or a d3.

<!-- -->
> 🗡 **Spinous Tail Swing**
>
> | **Charge, Melee, Strike, Weapon** |               **Main action** |
> | --------------------------------- | ----------------------------: |
> | **📏 Melee 2**                    | **🎯 Two enemies or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; push 2
> - **12-16:** 12 damage; push 4
> - **17+:** 15 damage; push 8
>
> **2 Malice:** Each target takes an extra 1d3 damage, and if they have A < 2, they are bleeding (save ends).

<!-- -->
> ⭐️ **Provoking Nettles**
>
> Once per turn, the dragon shifts up to 5 squares and can move through enemies' spaces at their usual speed. The first time the dragon moves through an enemy's space during this movement, the enemy takes 3 damage.

<!-- -->
> ❇️ **Investiture of Verdure (5 Malice)**
>
> | **Area**        |                  **Maneuver** |
> | --------------- | ----------------------------: |
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. Each target is pulled up to 5 squares toward the dragon, who gains 5 temporary Stamina for each target pulled.

<!-- -->
> ❗️ **Prickly Situation**
>
> | **Magic, Ranged** |      **Free triggered action** |
> | ----------------- | -----------------------------: |
> | **📏 Ranged 10**  | **🎯 The triggering creature** |
>
> **Trigger:** A dragonsealed creature within distance ends the dragonsealed effect.
>
> **Effect:** The target is pulled up to 5 squares toward the dragon, and if they have A < 2, they are restrained until the end of their next turn.

<!-- -->
> ❗️ **Thorny Scales (1 Malice)**
>
> | **Melee**      |      **Free triggered action** |
> | -------------- | -----------------------------: |
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the dragon with a melee strike.
>
> **Effect:** The dragon makes a free strike against the target, and if the target has M < 2, they are bleeding until the end of their next turn.

<!-- -->
> ☠️ **Briar Bindings (Villain Action 1)**
>
> | **Area, Magic** |                         **-** |
> | --------------- | ----------------------------: |
> | **📏 4 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 damage; A < 1 restrained (save ends)
> - **12-16:** 9 damage; A < 2 restrained (save ends)
> - **17+:** 12 damage; A < 3 restrained (save ends)

<!-- -->
> ☠️ **Thorned Armor (Villain Action 2)**
>
> | **-**       |       **-** |
> | ----------- | ----------: |
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The thorns upon the dragon's scales grow longer and sharper. Until the end of the encounter, any adjacent creature who targets the dragon with a melee strike takes 3 damage. The dragon then uses their Provoking Nettles ability.

<!-- -->
> ☠️ **Malign Thicket (Villain Action 3)**
>
> | **-**          |          **-** |
> | -------------- | -------------: |
> | **📏 Special** | **🎯 Special** |
>
> **Effect:** Poisonous overgrowth and seeking vines cover all surfaces on the encounter map. The dragon uses their Bramble Barricade Malice feature twice at no cost. Until the end of the encounter, any creature force moved by the dragon takes 1d3 poison damage, and if they have M < 2, they are weakened (save ends).
>
> **Special:** If the Thorn Dragon's Domain trait is in effect, any creature other than the dragon who starts their turn on the encounter map takes 1d3 poison damage.

###### Thorn Dragon Malice (Malice Features)

At the start of a thorn dragon's turn, you can spend Malice to activate one of the following features.

<!-- -->
> ⭐️ **Cage of Thorns (3 Malice)**
>
> A cage of thorns grows around one dragonsealed enemy on the encounter map, making that enemy restrained until the end of their next turn.

<!-- -->
> 🔳 **Bramble Barricade (5 Malice)**
>
> The dragon grows a 10 wall of briars in unoccupied spaces on the encounter map. The wall blocks line of effect for all creatures except the dragon. Each square of the wall has 5 Stamina and fire weakness 5. The area can be moved through but is difficult terrain. Any creature who is force moved into or within the area takes 1 damage for each square of the area entered and is bleeding until the end of their next turn.

<!-- -->
> ☠️ **Solo Action (5 Malice)**
>
> The dragon takes an additional main action on their turn. They can use this feature even if they are dazed.

<!-- -->
> 🌀 **Afflictive Overgrowth (7 Malice)**
>
> The dragon summons poisonous, biting thorns around their foes. Each enemy on the encounter map makes an **Agility test**.
>
> - **≤11:** 12 poison damage; restrained (save ends)
> - **12-16:** 9 poison damage; bleeding (save ends)
> - **17+:** 5 poison damage; bleeding (EoT)

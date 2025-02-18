## Previous Class
- [[Pupil]]
## Important Abilities
- Constitution
- Intelligence
## Progression
| Level | Features                                         | Tome Attunements | Spells Known | 1st | 2nd | 3rd | 4th | 5th |
| :---: | ------------------------------------------------ | :--------------: | :----------: | :-: | :-: | :-: | :-: | :-: |
|  3rd  | Ancient Language, Spellcasting, Magic of Shadows |                  |      4       | +2  | +1  |     |     |     |
|  4th  |                                                  |                  |      5       |     | +1  |     |     |     |
|  5th  | Transference                                     |                  |      5       | +1  |     | +1  |     |     |
|  6th  | Enthralling Undead                               |                  |      6       |     | +1  | +1  |     |     |
|  7th  | Dark Magic Mastery                               |                  |      6       | +1  |     | +1  | +1  |     |
|  8th  |                                                  |        +1        |      7       |     |     |     | +1  |     |
|  9th  | Hexing Aura                                      |                  |      7       |     | +1  |     | +1  | +1  |
## Class Gains
- **Gear**: A [[Tomes#Dark Tomes#Miasma|Miasma]] tome
- **Weapon Proficiencies**: Dark Tomes
- **Tool Proficiencies**: Choose any one Artisan’s tools
- **Skill Proficiencies**:  Choose one from Stealth, Arcana, Investigation, History, Insight, Animal Handling, Deception, and Intimidation
## Promotions
- [[Warlock]]
- [[Malig Knight]]
## Ancient Language
You have deciphered ancient language of dragons. You can speak the language and use it to leave hidden messages for other capable dark magi such as yourself. You and others who know it automatically spot such a message. Others spot the message’s presence with a successful DC 15 Wisdom (Perception) check but can’t decipher it without magic.
## Spellcasting
As a student of arcane magic, you have discovered the knowledge of spellcasting, being able to learn spells on the Wizard Spell List. See Spells Rules for the general rules of spellcasting.
### Spell Slots
The Dark Mage table shows how many spell slots you gain at each level to cast your wizard spells of 1st level and higher. To cast one of these spells, you must expend a slot of the spell’s level or higher. You regain all expended spell slots when you finish a long rest.
For example, If you know the 1st-level spell magic missile, you can cast it using a 1st-level or a 2nd-level slot.
### Spells Known
You know five spells of your choice from the wizard spell list.
The Spells Known column of the Dark Mage table shows when you learn more wizard spells of your choice. Each of these spells must be of a level for which you have spell slots.
### Tomes
You continue with your proficiency in Tome magic from the [[Pupil]] class. Both Dark Tomes and Anima Tomes utilize the same attunement limits. See the Tome Attunements column of the Dark Mage table to know when you gain additional attunement slots.
## Hearth of Shadows
For a Dark Mage, home can be wherever you are. During a short or long rest, you can invoke the shadowy power of the dragon gods to help guard your respite. At the start of the rest, you touch a point in space, and an invisible, 30-foot-radius sphere of magic appears, centered on that point. Total cover blocks the sphere. While within the sphere, you and your allies gain a +10 bonus to Dexterity (Stealth) and Wisdom (Perception) checks, and any light from open flames in the sphere (a campfire, torches, or the like) isn’t visible outside it.
The sphere vanishes at the end of the rest or when you leave the sphere.
## Magic of Shadows
Your study of shadow magic has ingrained them deeply within your mind.
You learn the Darkness, Darkvision, Pass Without Trace, and Silence spells. These spells cannot be swapped out for a different spell when you gain levels and do not count against your spells known as a Dark Mage.
## Transference
The energy of a creature's soul as it leaves its body becomes visible to you as magical energy.
When a creature within 60 feet of you that you can see dies, you can use your reaction to convert it's soul into healing energy. Target yourself or a willing living creature you can see within 15 feet of the dying creature, they regain hit points equal to 1d4 x your Constitution modifier (minimum of
one).
## Enthralling Undead
Your study of dark magic has finally broken through the secrets of animating undead terrors. You learn the spell animate dead if you haven't already. This spell cannot be swapped out for a different spell when you gain levels and do not count against your spells known as a Dark Mage.
When you cast Animate Dead, you can create Bonewalkers using a humanoid skeleton and Revenants using a humanoid corpse instead of regular skeletons and zombies.
These terrors have abilities that scale with the level of the spell slot used to cast Animate Dead (minimum of 3).
You can only animate and maintain control over undead created with this feature equal to your Constitution modifier (minimum of one).
## Dark Magic Mastery
Your mastery of Dark magic allow you to treat the living and undead the same.
Whenever an ability asks you to target a living creature, you can instead target an undead creature.
## Hexing Aura
The dark magic coursing through you leaks out like a terrifying aura, freezing those too close to you. Attacks have advantage against creatures within 5 feet of you. A creature immune to being frightened is not affected by this feature. This aura does not differentiate between friend and foe.

```statblock
name: Bonewalker
type: Medium Undead, Neutral Evil
ac: 8 + (spell level)
hp: 6 x (spell level)
speed: 30 ft.
stats: [12,12,15,6,8,3]
damage_vulnerabilities: Bludgeoning, Radiant
damage_resistances: Slashing, Piercing
damage_immunities: Poison
condition_immunities: Poisoned, Frightened
senses: Darkvision 60 ft., Passive Perception 9
languages: Understands common but can't speak
dice: false
traits:
  - name: Enthralling Undead
    desc: The Bonewalker adds your proficiency bonus to its saving throw and weapon attack rolls.
actions:
  - name: Multiattack
    desc: "The Bonewalker makes 2 attacks if this creature was created with a spell level 5 or higher."
  - name: Rusted Sword
    desc: "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 1d8 + (spell level) slashing damage."
  - name: Shortbow
    desc: "Ranged Weapon Attack: +1 to hit, range 80/320 ft., one target. Hit: 1d6 + (spell level) piercing damage."
```
```statblock
name: Revenant
type: Medium Undead, Neutral Evil
ac: 5 + (spell level)
hp: 10 x (spell level)
speed: 20 ft.
stats: [14,6,16,3,6,3]
damage_vulnerabilities: Fire, Radiant
damage_immunities: Poison
condition_immunities: Poisoned, Frightened
senses: Darkvision 60 ft., Passive Perception 8
languages: Understands common but can't speak
dice: false
traits:
  - name: Enthralling Undead
    desc: The Revenant adds your proficiency bonus to its saving throw and weapon attack rolls.
actions:
  - name: Multiattack
    desc: "The Revenant makes 2 attacks if this creature was created with a spell level 5 or higher."
  - name: Putrid Claw
    desc: "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 1d4 + (spell level) slashing damage and the creature must succeed on a Constitution saving throw against your spell save DC or be poisoned until the end of its next turn."
```

![[dark_mage.png]]
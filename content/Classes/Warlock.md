## Previous Class
- [[Dark Mage]]
## Important Abilities
- Constitution
- Intelligence
## Progression
| Level | Features                              | Spells Known | 5th | 6th | 7th | 8th | 9th |
| :---: | ------------------------------------- | :----------: | :-: | :-: | :-: | :-: | :-: |
| 10th  | Death's Command, Phantom Familiar     |      8       | +1  |     |     |     |     |
| 11th  | Death's Beginning                     |      9       |     | +1  |     |     |     |
| 13th  |                                       |      11      |     |     | +1  |     |     |
| 15th  | Death's Abundance, Persistent Phantom |      13      |     |     |     | +1  |     |
| 17th  |                                       |      15      |     |     |     |     | +1  |
| 18th  | Death's Embrace, Durable Phantom      |      17      |     |     |     |     |     |
| 19th  |                                       |      19      |     | +1  |     |     |     |
| 20th  |                                       |      20      |     |     | +1  |     |     |
## Class Gains
- **Gear**: A 7th-level [[Tomes#Dark Tomes|Dark Tome]]
- **Skill Proficiencies**:  Choose one from Stealth, Arcana, Investigation, History, Insight, Animal Handling, Deception, and Intimidation
## Death's Command
You learn the spell Command if you haven't already. This spell cannot be swapped out for a different spell when you gain levels and do not count against your spells known as a Dark Mage. You can cast this spell at a 1st level without expending a spell slot and you are able to affect undead creatures with this spell.
## Phantom Familiar
You learn the Summon Phantom spell. This spell cannot be swapped out for a different spell when you gain levels and do not count against your spells known.

> [!NOTE] Summon Phantom
> *3rd Level Conjuration*
> **Casting Time**: 1 Action
> **Range**: 90 ft.
> **Components**: V, S, M
> **Duration**: 1 Hour (requires concentration)
> 
> You call forth a Phantom soldier. It manifests in an unoccupied space that you can see within range. The corporeal form uses the Phantom Familiar stat block. The creature disappears when it drops to 0 hit points or the spell ends.
> 
> The creature is an ally to you and your companions. In combat, the creature shares your initiative count, but it takes its turn immediately after yours. It obeys your verbal commands (no action required by you). If you don't issue any, it takes the Dodge action and uses its move to avoid danger.
> 
> This Phantom may be cast using higher spell slots for a stronger summon. Only one familiar can be summoned at a time.

```statblock
name: Phantom Familiar
type: Medium Construct, Lawful Neutral
ac: 10 + (spell level)
hp: 8 x (spell level)
speed: 30 ft.
stats: [16,10,16,4,8,3]
damage_immunities: Poison, Psychic
condition_immunities: Poisoned, Frightened, Charmed, Petrified
senses: Darkvision 60 ft., Passive Perception 9
languages: Understands common but can't speak
dice: false
traits:
  - name: Summoner's Familiar
    desc: "The Phantom Familiar adds your proficiency bonus to its saving throw and weapon attack rolls."
actions:
  - name: Multiattack
    desc: "The Phantom Familiar makes a number of attacks equal to half the spell level rounded down."
  - name: Phantom Axe
    desc: "*Melee Weapon Attack*: +3 to hit, reach 5 ft., one target. *Hit*: 2d8 + (spell level) slashing damage"
```

## Death's Beginning
Your study of death and it's reversal has revealed the secrets of resurrection magic typically only
granted to those who worship the goddess. Doing so will require you to compensate your lack of faith with physical skill, but success would allow you to impart your skills of animating the dead on those you resurrect.
You learn the spell Raise Dead if you haven't already. This spell cannot be swapped out for a different spell when you gain levels and do not count against your spells known as a Dark Mage.
When you cast this spell, you must make a Constitution saving throw (DC equal to 8 + half the target's level). If you fail, the target's soul will be tormented and the revived creature will be eternally hostile towards you without any regards for it's own safety.
If you succeed, then the resurrected creature must succeed on a Charisma saving throw or become unknowingly charmed by you, remaining friendly to you for the rest of their life and losing any problematic memories it may have from before it's death that would prevent it from being friendly towards you.
## Death's Abundance
You begin to recognize and understand that the dead is all around you, even when others wouldn't normally consider it as such.
You no longer need to use a pile of bones or a corpse of a humanoid to cast Animate Dead. Instead you are able to locate the fragments of those long dead all around you to quickly piece together exactly what you need in place of a pile of bones or a corpse.
## Persistent Phantom
Your phantom cannot be easily dismissed. 
You gain +10 to your concentration saving throws while concentrating on the Summon Phantom spell.
## Death's Embrace
You have become so deeply steeped in the magic of death that you become immune to it.
You are immune to Necrotic damage. Additionally, creatures you summon or raise are resistant to Necrotic damage.
## Durable Phantom
You learn how to maximize the durability of your Phantom.
Your phantom has additional hit points equal to half of your own (rounded down). 
As an action, you can restore hit points to your phantoms equal to 1d10 x (spell level).

![[warlock.png]]
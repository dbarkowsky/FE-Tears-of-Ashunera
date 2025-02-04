## Previous Class
- [[Recruit]]
## Important Abilities
- Dexterity/Strength
- Charisma
## Progression
Characters of this class have the option to take either the Pegasus route or the Wyvern route.
They may only gain the Features relative to their choice of mount.
### Pegasus Rider

| Level | Features                              |
| :---: | ------------------------------------- |
|  3rd  | Young Pegasus, Skilled Flier, Harrier |
|  5th  | Terrors Slayer, Canto                 |
|  6th  | Extra Attack                          |
|  7th  | Triangle Attack                       |
|  9th  | Relief                                |
### Wyvern Rider

| Level | Features                             |
| :---: | ------------------------------------ |
|  3rd  | Young Wyvern, Skilled Flier, Harrier |
|  5th  | Terrorize, Canto                     |
|  6th  | Extra Attack                         |
|  7th  | Wyvern's Bond                        |
|  9th  | Air Raid                             |
## Class Gains
- **Gear**: A chain shirt, an [[Weapons#Lances|Iron Lance]], an [[Weapons#Shields|Iron Shield]], and either (a) a pegasus OR (b) a wyvern
- **Tool Proficiencies**: Any one Artisan's Tools or Musical Instrument
- **Skill Proficiencies**: Gain Animal Handling and choose one from Acrobatics, Stealth, Arcana, Investigation, Religion, Insight, Perception, Intimidation, and Performance
## Promotions
- [[Pegasus Knight]]
- [[Wyvern Knight]]
- [[Malig Knight]]

> [!NOTE] Controlling a Mount
> You can control a mount only if it has been trained to accept a rider. The initiative of a controlled mount changes to match yours when you mount it. It can act either before or after you.
> 
> It moves as you direct it, and it has only three action options: Dash, Disengage, and Dodge. A controlled mount can move and act even on the turn that you mount it, given that it has not already acted that turn.
> PHB, pg. 198

> [!NOTE] Mounting and Dismounting
> Once during your move, you can mount a creature that is within 5 feet of you or dismount. Doing so costs an amount of movement equal to half your speed.
> 
> If an effect moves your mount against its will while you're on it, you must succeed on a DC 10 Dexterity saving throw or fall off the mount, landing prone in a space within 5 feet of it. If you're knocked prone while mounted, you must make the same saving throw.
> 
> If your mount is knocked prone, you can use your reaction to dismount it as it falls and land on your feet. Otherwise, you are dismounted and fall prone in a space within 5 feet it.
> PHB, pg. 198

> [!NOTE] Flying Mounts
> Flying mounts behave the same as regular mounts, but the following rules should be remembered during play:
> 
> If you fall off your mount, or if your mount becomes incapacitated, you will fall towards the ground at a rate of 500 feet per round. If it is not your turn, you will fall 500 feet before the start of your turn.
>
> Alternatively, if you jump off of your mount on your turn, you will fall 500 feet by the end of your turn. This rapid descent can only be interrupted by a reaction (such as the Feather Fall spell.)
> XGE, pg. 77
>
>At the end of a fall, a creature takes 1d6 bludgeoning damage for every 10 feet it fell, to a maximum of 20d6. The creature lands prone, unless it avoids taking damage from the fall.
>PHB, pg. 183


```statblock
name: Young Pegasus
type: Large Celestial
ac: 15 (Barding)
hp: 10 + 4 per rider's level
speed: 50 ft., flying 90 ft.
stats: [13,16,12,6,14,12]
senses: Passive Perception 15
saves:
  - dexterity: 6
  - wisdom: 5
damage_vulnerabilities: Piercing, Force
traits:
  - name: Bred for War
    desc: This creature has advantage on death saving throws.
actions:
  - name: Hooves
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (2d6 + 1) bludgeoning damage."
dice: false
```

```statblock
name: Young Wyvern
type: Large Dragon
ac: 16 (Barding)
hp: 10 + 5 per rider's level
speed: 35 ft., flying 60 ft.
stats: [15,13,14,3,11,7]
senses: Passive Perception 15
saves:
  - strength: 6
  - constitution: 5
damage_vulnerabilities: Force, Lightning
traits:
  - name: Bred for War
    desc: This creature has advantage on death saving throws.
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (2d6 + 2) bludgeoning damage."
dice: false
```

## Young Pegasus
Having shown a natural affinity with mounted aerial combat, you have been given a Young Pegasus as your companion. Taking care of it is your responsibility and duty. Should your Young Pegasus die, you will need to spend 1500 gp to purchase and outfit a replacement.
## Young Wyvern
Having shown a natural affinity with mounted aerial combat, you have been given a Young Wyvern as your companion. Taking care of it is your responsibility and duty. Should your Young Wyvern die, you will need to spend 1500 gp to purchase and outfit a replacement.
## Skilled Flier
You have advantage on saving throws made to avoid falling off your mount. If you fall off your mount and descend no more than 10 feet, you can land on your feet if you’re not incapacitated.
Additionally, both you and your mount have advantage on Dexterity saving throws while flying at least 30 feet in the air.
## Harrier
Being in the sky allows you to enter combat quickly. You have advantage on initiative rolls while flying at least 30 feet in the air.
## Terrors Slayer (Pegasus)
You have been trained in the ways of fighting horrid monsters by channeling your prayers to the goddess. You gain an bonus to melee weapon attack and damage rolls equal to your Charisma modifier against fiend, monstrosity or undead creatures.
## Terrorize (Wyvern)
Your mount's intimidating nature strikes fear into the hearts of all those around it. As a bonus action on your turn, your mount can roar loudly affecting all enemies within a 30ft radius.
Enemies that can see and hear you must succeed on a Wisdom saving throw (DC equal to 8 + your proficiency bonus + your Charisma modifier) or be frightened of you. This effect ends if the creature ends its turn out of line of sight or more than 1 minute passes.
You can do this a number of times equal to your proficiency bonus following each long rest.
## Canto
Your command of your mount grants you the ability to easily reposition yourself on the battlefield.
After you've taken your action, you can use your reaction to grant your mount an additional 30 foot of movement. A creature that you or your mount have dealt damage to on your turn has disadvantage on opportunity attacks against you and your mount until the end of your turn.
## Extra Attack
You can attack twice, instead of once, whenever you take the Attack action on your turn.
## Triangle Attack (Pegasus)
You learn advanced flying maneuvers, allowing you lead your allies into attacking with a triangle formation.
When you make a melee attack against a creature, you can make the attack with advantage if:
- At least 2 friendly creatures are within 5 feet of it 
- They are not incapacitated
- They have an Intelligence of 7 or higher
If the attack hits, 2 friendly creatures that fulfilled the above conditions may each use their reaction to make an attack against your attack target.
You can use this feature a number of times equal to your Charisma modifier (minimum of once). You regain all expended uses of it when you finish a long rest.
## Wyvern's Bond (Wyvern)
Your connection with your wyvern has grown strong, and you have a keen sense of how they wish to move. As a result, it's easier to stay mounted and your wyvern may take the attack action on their turn without knocking you off.
## Relief (Pegasus)
Your prayers to the goddess can grant you temporary protection.
While there are no hostile creatures within 30 feet of you, you can use your bonus action to gain temporary hit points equal to 1d10 + twice your Charisma modifier.
## Air Raid (Wyvern)
Your mount has learned that heights can be just as deadly as a bite. While flying at least 30 feet in the air, you can use your action (or your mount's if unmounted) to swoop down and attempt to grapple an enemy of medium or smaller size. In the same turn, it may rise into the air 30 feet without taking attacks of opportunity from those below. Any lateral movement in this maneuver counts against your move speed, but the vertical movement does not.
A grappled opponent may be dropped immediately from that height, or you can continue to grapple the opponent for subsequent turns. While grappled, the opponent can attack the wyvern on its regular turn. The rider cannot attack the grappled opponent in this position.
For the initial grab, use an attack roll with your mount's Dexterity modifier to hit.
To maintain the grapple for subsequent turns, use your mount's Strength modifier in a role against the grappled opponent's. 
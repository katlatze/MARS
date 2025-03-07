# Table of Contents

* [The Basics](#the-basics)
* [Primary Stats](#primary-stats)
* [Secondary Stats](#secondary-stats)
* [Skills](#skills-1)
* [Basic Skills](#basic-skills)
* [Advanced Skills](#advanced-skills)
* [Combat Skills](#combat-skills)
* [Maneuvers](#maneuvers)
* [Languages](#languages)
* [Genre Specific Skills](#genre-specific-skills)
* [Playing the Game](#playing-the-game)
* [Encounters](#encounters)
* [Damage](#damage)
* [Effects](#effects)
* [Resting](#resting)
* [Creating a Character](#creating-a-character)
* [Equipment](#equipment)
* [Advancing a Character](#advancing-a-character)

# The Basics

MARS features many similarities to other role-playing game systems. You will control a character that has several numerical and abstract features. These features are called *stats*, *skills*, *talents*, and *traits*. Stats and skills are represented by dice or numbers, while talents and traits represent special abilities or actions that a character can perform. As players progress they will be awarded experience points that they can spend to improve the stats and skills of their character, or to acquire new talents.

If at any point during the game you are required to perform math that results in a decimal, that number is always rounded down unless otherwise specified.

### Roll Value

Most roleplaying games typically use [dice notation](https://en.wikipedia.org/wiki/Dice_notation) to describe what dice to roll, while MARS uses a modified version of dice notation called *roll value*. Some characteristics or numbers may be represented by this roll value. The main difference in this notation is that while common dice notation will specify exactly what dice to roll, the resulting equation may get long and complicated, such as: *2d10+1d6+1d4+1*. This is difficult to read, so roll value is designed to be shorter, easier to read, and represent a whole group of dice to roll.

Roll value will typically have one or two numbers like so: *r14+1*. Where the first number following the *r* represents the roll value, and therefore what dice to roll, and the second value represents a numerical modifier as a plus or minus. Basically, you count the number of tens in the roll value, then roll that many ten-sided-dice. Any remainder left over is rolled as a die of that size. The exception to this, is that if you get a remainder of 2, then you upgrade one of those ten-sided-dice to a twelve-sided-die. Whenever you add multiple roll values together they merge into a combined roll value: *r14 plus r8 equals r22*. Below is a table for visualization (with a more full table available in the [appendix](/Basic/Appendix.md#roll-values)):

| Roll Value | Dice to Roll |
|:-:|:-|
| r4 | 1d4 |
| r6 | 1d6 |
| r8 | 1d8 |
| r10 | 1d10 |
| r12 | 1d12 |
| r14 | 1d10+1d4 |
| r16 | 1d10+1d6 |
| r18 | 1d10+1d8 |
| r20 | 2d10 |
| r22 | 1d12+1d10 |
| r24 | 2d10+1d4 |
| r26 | 2d10+1d6 |
| r28 | 2d10+1d8 |
| r30 | 3d10 |

This has the added benefit of clearly indicating the maximum value you can roll (it is the same as the roll value), and makes calculating the average value quite fast as it is simply half of the roll value.

### Stats

Stats represent the innate capabilities of a character. The two types of stats are *primary stats* and *secondary stats*. Primary stats are represented by a roll value, and represent how well a character can perform universal tasks. Secondary stats are represented by either a roll value or flat numbers, and are the generic properties of a character. While primary stats are simply given to a character, secondary stats are derived from other sources (usually primary stats).

### Skills

Skills represent what your character is practiced in. Like primary stats, skills are represented a roll value. The two types of skills are *basic skills* and *advanced skills*. Basic skills are tasks that anyone can perform, while advanced skills can only be performed by characters that are at least trained in that skill. The types of advanced skills that a character can learn are mostly dependant on the type of genre you are playing. While someone who can cast spells might be more typical of a fantasy genre, it would not be as common in a modern genre.

### Talents

Talents are powerful abilities that characters can learn. They usually provide you the ability to perform unique actions that are not simple enough to be performed by skills, or are modifiers to how a character performs their normal abilities. Most talents that can be acquired are dependant on the type of genre you are playing (similar to advanced skills).

### Traits

Traits are unique abilities that usually only belong to a single character. Typically they are something that one can do or have, and provide opportunities to roleplay in a unique way. Traits help characters stand out from other characters that would otherwise be very similar to them.

# Primary Stats

Each character has four Primary Stats that are used to derive other stats and abilities. These stats are: *strength*, *dexterity*, *intelligence*, and *resolve*. All primary stats are represented by roll values ranging from r8 to r20.

##### Table: Primary Stat Steps
| Roll Value | Step Name |
|:-:|:-|
| r8 | Below Average |
| r10 | Average |
| r12 | Above Average |
| r14 | Great |
| r16 | Superb |
| r18 | Powerful |
| r20 | Epic |

### Strength (STR)

Strength measures physical power, and general fortitude. This stat is important for atheletes, labourers, and those who engage in physical combat.

### Dexterity (DEX)

Dexterity measures the reaction speed, balance, and precision of your character. It is an important stat for characters who want to use stealth, use sleight of hand, or tinker with devices. 

### Intelligence (INT)

Intelligence determines how well your character learns and reasons. It is important for those who want to understand how complex things work, speak many languages, or recall important information. In genres that have magic it also determines a character's capacity for magical energies.

### Resolve (RES)

Resolve is the determination, willpower, intuition, and spirituality of your character. It is primarily used for characters who want to persevere through pure force of will, practice the arts or business, or communicate with others and animals.

# Secondary Stats

Characters have several secondary stats: *health*, *endurance*, *stamina*, *mana*, *initiative*, *armour class*, *damage reduction*, *deflection*, *evasion*, *fortitude*, *willpower*, *speed*, and *size*. These stats are typically calculated based on on your primary stats. Armour class and damage reduction are determined by what your character is wearing, while *speed* and *size* are determined by your character's race.

The first four secondary stats (health, endurance, stamina, and mana) are also considered *resources*. Resources have current and maximum values, and they may be spent or damaged.

##### Table: Secondary Stats
| Secondary Stat | Formula |
|:-|:-:|
| Health (HP) | Max STR |
| Endurance (EP) | Max RES |
| Stamina (SP) | Max DEX |
| Mana (MP) | Max INT |
| Initiative (INIT) | DEX + RES |
| Deflection (DEF) | RES + AC |
| Evasion (EVA) | DEX + AC |
| Fortitude (FORT) | STR + RES |
| Willpower (WILL) | INT + RES |

For example: if you have a strength of r12, then you have a maximum strength of 12 and therefore 12 health.

### Health (HP)

Health is an abstraction representing how healthy a character is at the current moment. Any damage taken to your health represents a serious injury.

### Endurance (EP)

Endurance represents your ability to shrug off injuries before suffering serious damage, and is easy to restore with a little rest.

### Stamina (SP)

Stamina is used to perform tricks, maneuvers, and certain physical actions.

### Mana (MP)

Mana is used to cast spells and perform magical abilities.

### Initiative (INIT)

Initiative is your ability to react first in a moment of conflict.

### Armour Class (AC)

Armour class represents the effectiveness of defensive equipment to neutralize incoming attacks.

### Damage Reduction (DR)

Damage reduction represents the effectiveness of defensive equipment to reduce the force of incoming successful hits. Any damage you take is reduced by your total damage reduction.

### Deflection (DEF)

Deflection is the capacity to shrug off incoming attacks and abilities before they can even take effect.

### Evasion (EVA)

Evasion is your ability to quickly avoid danger, rather than relying on deflection to take hits.

### Fortitude (FORT)

Fortitude is your ability to resist poison and disease. In dire circumstances it is also used to avoid potential death.

### Willpower (WILL)

Willpower is your ability to resist temptation or supernatural influence, both mental and physical. This is not the same as preventing effects that harm the body, but instead those that control the body or mind. It is also used to determine whether or not someone seems believable or false.

### Speed (SPD)

Your speed is a measurement of your average walking distance over six seconds. You can run three times this distance in the same amount of time.

### Size (SZ)

Size is measured in size categories. Most characters will normally be considered medium-sized, however, certain genres and settings may provide you with additional racial options that exist in different size categories. Your size may provide you with modifiers to some of your other stats.

##### Table: Size & Size Modifiers
| Size | Avg. Height | Avg. Weight | Strength | Dexterity |
|:-|:-:|:-:|:-:|:-:|
| Tiny | ½~¾m | 5~15kg | –3 | +2 |
| Very Small | ¾~1m | 15~30kg | –2 | +1 |
| Small | 1~1½m | 30~60kg | –1 | +1 |
| Medium | 1½~2m | 40~90kg | – | – |
| Large | 2~2½m | 60~150kg | +1 | –1 |
| Very Large | 2½~3m | 90~250kg | +2 | –1 |
| Huge | 3~4m | 150~500kg | +3 | –2 |

# Skills

Like primary stats, skill values are represented by roll values. All skills have associated primary stats that are rolled with that skill whenever it is performed (listed next to that skill's name).

##### Table: Skill Steps
| Roll Value | Step Name |
|:-:|:-|
| - | Untrained |
| r4 | Trained |
| r6 | Adept |
| r8 | Practiced |
| r10 | Proficient |
| r12 | Exceptional |
| r14 | Disciplined |
| r16 | Accomplished |
| r18 | Expert |
| r20 | Master |

# Basic Skills

All characters can perform all basic skills, even if they are not trained in them. There are five basic skills: *acrobatics*, *athletics*, *charisma*, *perception*, and *stealth*.

### Acrobatics (DEX)

You can keep your balance while traversing narrow or treacherous surfaces. You can also performs dives and flips, among other nimble feats.

### Athletics (STR)

You use the strength of your body to manipulate the world around you and move within it. You are practiced in lifting, climbing, swimming, and jumping, among other activities.

### Charisma (RES)

The capacity to convince others to follow your lead, whether that means through intimidation, deception, or appealing to emotion.

### Perception (DEX)

Perception is used to track animals, monsters, or people, to detect stealthy individuals, or find hidden secrets and traps.

### Stealth (DEX)

You’re skilled in concealing yourself effectively in different environments. You know how to avoid standing out, pick good hiding spots, and move silently. It can also be used to disguise your identity.

# Advanced Skills

Unlike basic skills, a character must be at least trained in an advanced skill to use it. There are six core advanced skills: *contacts*, *knowledge*, *lore*, *medicine*, *sleight*, and *wild empathy*. All additional types of skills, such as combat skills, spellcasting skills, and languages are all considered advanced skills. Depending on the genre, setting, or specific adventure there could be any number of additional advanced skills available to players.

### Contacts (RES)

Somtimes you just know someone who can get what you need done, and if you don't, maybe you know how to find one. In a city or town there's always that somebody. This skill can be used to find people in urban areas where tracking them with perception can't get the job done. It is likely that this task may involve bribes or threats.

### Knowledge (INT)

Knowledge represents your ability to recall important events, the names and details of important people, or prominent world religions. Anything pertaining to widely available but potentially unknown information. It can also be used to recall any information that someone with your character's background and skills would know (that don't fall into categories determined by the lore or medicine skills).

### Lore (INT)

Although most worldy facts can be recalled using the knowledge skill, everything else can be recalled with the lore skill. This means obscure cults and religions, secret organizations and their leaders, the occult, monsters, or magical artifacts. This skill can also be used to perform research on a topic you are not knowledgeable in, assuming you have access to research materials.

### Medicine (INT)

This skill is important for anyone seeking to apply medicines and treat wounds, injuries, or illnesses. It can also be used to recognize materials, chemicals, and plants with medicinal properties, and recall knowledge on medicines and herbs.

### Sleight (DEX)

Whether its traps, locks, pockets, or just fancy tricks, all such things are within your grasp. While this skill is generally used for everything a thief would do, it can also be used to conceal objects and perform magic tricks.

### Wild Empathy (RES)

In the wild, many animals are unfriendly or fearful towards the majority of people. This skill allows you to speak to and calm down such animals. It can also be used to convince certain animals, like guard dogs, that you are friendly much in the same way you could use the charisma skill to persuade someone.

# Combat Skills

There are four core combat skills: *finesse*, *martial*, *ranged*, and *unarmed*. Although combat skills are considered advanced skills, characters can make attacks with weapons without training. If a character does so, they must roll the stat associated with the skill required to use that weapon (normally dexterity). Being trained in any combat skill allows you to use that skill to make attacks with weapons of a matching type, and all basic weapons. There are also cross-skill weapons which have multiple listed types. Any type listed can be used with those weapons.

### Finesse (DEX)

Combat with small or precise weapons. This skill is dedicated to utilizing fast attacks to constantly threaten opponents and find openings and weak spots.

### Martial (DEX)

Combat with heavy or broad weapons. Although it is not as likely to get as many good strikes on an opponent as someone trained in Finesse, it is more likely to deliever stronger blows even without striking the weak points as martial weapons are generally heavier.

### Ranged (DEX)

Ranged combat includes the use of all weapons that fire projectiles, such as bows and guns, and throwing projectile weapons.

### Unarmed (DEX)

Unarmed combat involves anything from complex martial arts to boxing. Unarmed combat is the least likely to deal lethal blows, but is important for anyone who might find themselves often fighting without a weapon.

# Maneuvers

Maneuvers are special abilities acquired by advancing combat skills. Each combat skill has access to different maneuvers.

Whenever you become trained in a new combat skill, you acquire a maneuver from that specialization. You gain additional maneuvers for every two rank advancements beyond that in the same skill. Maneuvers cost stamina and can only be used once each round. Any characters that start with combat skills also start with maneuvers based on their advancement in that skill. Maneuvers gained from advancing one combat skill can be used by your other combat skills, so long as they could normally also be learned by it.

For example: You advanced your Martial skill and learned Heavy Strike. Since you are also trained in Unarmed, you can also use Heavy Strike with the Unarmed skill.

When you perform a maneuver on a target it may have a chance for the target to resist the effects of that maneuver. They will roll the skill or stat listed to make an opposed check against your attack roll (or a skill check instead if the maneuver specifies one). If they succeed the resist, then they do not suffer the effects of that maneuver. If they graze, they suffer the effect at half the duration (if any), otherwise it counts as a success and they suffer no effects. Any attacks are still made on the target even if they resist the effects of the maneuver.

Although maneuvers must be learned in order to use normally, you can improvise maneuvers. To do so you must be trained in the skill required to learn it, but not have the maneuver itself learned. If you do improvise a maneuver, you make all skill checks and attacks specified in that maneuver with a –2 penalty, and it costs twice as much stamina. If that maneuver is a swift action, it becomes a standard action instead.

For example: You are trained in Finesse but aren't trained in the Feint maneuver. You attempt to improvise the maneuver, taking a –2 penalty on your charisma check to perform the maneuver.

Click [here](/Basic/Maneuvers.md) for the list of universal maneuvers.

Click [here](/Fantasy/Maneuvers.md) for the list of fantasy maneuvers.

# Languages

When characters are created they are considered native speakers of their starting languages. If any characters wish to learn new languages they will need to acquire them exactly the same way that one would acquire a new advanced skill. Therefore, non-native languages have values as roll values. Languages as skills are associated with your Intelligence.

Whenever your character tries to read, write, speak, or listen to a language that they aren't native in, they will usually need to make a Language check. Once you become a master of that language, it is functionally the same as if you were native in that Language, so you will no longer need to roll to determine success.

The availability of languages to your character are determined by the genre or setting that you are in. If you're not playing in a modern or historic genre, usually there is a "common" language that all races speak, and languages for every race. In the fantasy genre it is common for most monstrous creatures to also share an "undercommon" language between them.

# Genre Specific Skills

There may be additional skills available depending on the genre you are playing.

Click [here](/Fantasy/Skills.md) for the list of fantasy skills.

Click [here](/Fantasy/Spellcasting.md) for the rules and a table of spells for fantasy spellcasting.

# Playing the Game

Typically game sessions run as follows: the Game Master describes the scene, then the players describe their actions and the game progresses. Through the act of description and exposition, your characters and the world they inhabit become alive.

It is important to focus on describing what it is your character does, rather than declaring the exact game action your character takes. It is up to the Game Master to decide what actual game action you perform, or what skill is required to overcome a challenge. This provides more freedom to narrate your character's intentions, rather than strictly adhering to gamified actions like a traditional board game.

While describing what your character does, try not to detail the results of your character's actions, only the actions themselves. Your Game Master is responsible for deciding the results of your actions. It is also important to note that you should only need to roll dice to determine the success of your actions when the outcome of that action is uncertain, or failure carries potential consequence.

### Skill Checks

If you have taken an action and success is not guaranteed, you will need to make a *skill check*. To do so you will roll your skill and associated primary stat together and compare the result to a *difficulty value* determined secretly by the Game Master. The resulting roll of any skill check is determined by its relationship to the difficulty value. This can result in multiple degrees of success or failure.

For example: you attempt to leap over a large pit. This requires an athletics check, which is associated with your strength stat. If you have a strength of r12, and an athletics of r4, you will roll r16. If you were not trained in athletics you would still at least roll your strength.

Generally if you roll less than the difficulty, you fail, and succeed if you roll higher than the difficulty. If you tie with the difficulty, you partially succeed (also known as a *graze*). In circumstances like this you generally succeed at reduced effectiveness, or with some degree of consequence. Success and failure can be made better or worse if you roll exceptionally high or low. If you roll half of the difficulty or less, you *critically fail* (also known as a *fumble*). If you roll double the difficulty or more, you *critically succeed*. These success categories apply to any comparison of a dice roll to either a difficulty value, or against another dice roll. Comparing dice rolls from skill checks against one another is called an *opposed check*, where one is trying to succeed over the other.

### Challenge Difficulty

Various challenges will come at various difficulties. These difficulties are represented by a name and a value. Most challenges requiring you to roll dice will exist within the *easy* to *ambitious* difficulty range as described by the following table. Although more difficult challenges may present themselves, they are increasingly rare.

##### Table: Challenge Difficulties
| Difficulty Value | Difficulty Name |
|:-:|:-|
| 5 | Easy |
| 7 | Moderate |
| 10 | Hard |
| 14 | Challenging |
| 19 | Ambitious |
| 25 | Absurd |
| 32 | Improbable |
| 40 | Impossible |

### Skill Duration

While most basic skills and actions can be performed in a matter of a couple seconds, some advanced skill and actions cannot be performed so quickly. While it is expected that most advanced actions that a character can take (as a result of skill checks) may take at least a few minutes, the exact duration is up to the Game Master to decide based on the circumstances of the skill check. Some actions may even take several hours.

### Advantage & Disadvantage

Occasionally, circumstance, clever roleplaying, or one of your abilities will provide you with an advantage. If you have an advantage in any moment where you are required to roll dice, the advantage modifies how you roll. Instead of simply rolling and keeping the result, you roll an additional time (for every degree of advantage you have) and keep the best result. Disadvantage works similarly, but instead of keeping the better result, you must keep the worst. Paired instances of advantage and disadvantage cancel each other out.

### Group Actions

Sometimes multiple players will want to perform the same type of action. If the circumstances (and the Game Master) determine it to be reasonable for multiple players to work together, then they will all roll the same skill check for that action, but only the best result will be used. A player can only assist in a task only if they are at least trained in that skill.

### Talents & Special Abilities

Under normal circumstances you will dictate what you do rather than specifying the exact game action you take. In the case of talents or other special abilities, however, these aspects of your character are more under you control. In this circumstance it is appropriate to declare exactly what you are using, and then describe what your character does as it performs that action.

For example: You might say, *"I jump across the pit,"* and you would need to roll an athletics check to succeed. Alternatively, you could instead say, *"I cast Feather Fall then jump across the pit,"* and it might make it easy enough that you don't need to roll at all.

# Encounters

Encounters are time-sensitive scenarios where each action you take matters. Encounters typically begin in a few different ways:

* If two or more characters or creatures intend to perform actions that oppose each other (combat and non-combat).
* When a character is aware of a potential danger, and intends to be deliberate and calculating with their actions.
* When there is limited time to overcome a complex challenge.

Encounters from start to end follow this sequence:

1. All characters roll initiative.
2. If it is combat, determine which characters are aware of their opponents. If these characters are aware of their opponents, but not the other way around, they can act during a surprise round.
3. Characters who are not surprised take turns in initiative order during the surprise round.
4. After the surprise round (if any), all characters take turns in initiative order during regular rounds. This repeats until the encounter ends.

### Initiative

When it comes time to *roll for initiative* each player will simply roll their initiative stat, which is their dexterity plus their resolve. The results rolled from highest to lowest determine turn order. Break ties by rolling opposed initiative checks.

### Rounds

Each round represents about six seconds in the game world, meaning there are 10 rounds in a minute. Each round’s activity begins with the character with the highest initiative result and then proceeds in order from the next highest to the lowest. When a character's turn comes up in the initiative sequence, that character performs up to their entire round's worth of actions.

When the rules refer to a *full round* or a number of rounds, they usually mean a span of time from a particular initiative count in one round to the same initiative count in the next round. Effects that last a certain number of rounds end just before the same initiative count that they began on.

### Complex Challenges

Some encounters are considered complex challenges: there is a limited amount of time to complete them, or a series of skill checks are required to overcome them. In these encounters the exact duration of a player's turn is abstract and non-specific. Since players will usually be performing skill checks, the average duration of a turn is the average time it takes to perform all of the player's skill checks and minor actions (assuming they all take about the same amount of time).

Most basic combat scenarios can be considered complex challenges rather than tactical combat encounters. In these situations it is more common for simple enemies to go down in a single hit, while player characters must suffer damage before becoming unconscious or even killed.

### Actions

During an encounter with more concrete turn length (such as a tactical combat), any action that you take uses a specific portion of your turn. The amount of your turn each action requires is based on their action speed. These speeds—in order from slowest to fastest—are: *extended*, *full*, *standard*, *swift*, *reaction*, and *free*.

Since a turn is six seconds long, we can also measure each action in seconds. Full, standard, and swift actions are each six, four, and two seconds long respectively. Free actions don't take up any time the first time you use one, but each additional free action on your turn takes up one second of your turn.

Reactions are two seconds long (like a swift action), but you can only use them if you meet the conditions for that action. If you use a reaction when it is not your turn, it uses two seconds worth of time from your next turn and you cannot use a reaction again until your next turn begins.

Extended actions take time that is longer than a single turn (longer than six seconds). Once started they can be interrupted at any point in their duration, so long as it is your turn.

In addition to the following basic actions, characters may perform maneuvers or cast spells with an action speed specified by those actions.

#### Attack

**Action Speed:** Swift

Make an attack on a target with one of your wielded weapons or with your bare hands.

When making an attack, first roll your appropriate combat skill to hit your target versus their deflection. Then roll your weapon's damage. Grazes deal half damage, and criticals deal bonus damage as specified by that weapon.

Additional attacks made during the same turn get a –4 penalty to hit for each attack made before it in the same turn. This penalty applies to all forms of attack actions. This is known as the *multiple attack penalty*. Attacks made as a reaction are considered attacks made on your next turn (such as by a readied action).

Attacks made against enemies who cannot see you, or who are surrounded on two opposite sides, are made with advantage. These are known as *sneak attacks* and *flanking attacks* respectively. You do not need to be contributing to a flank to make a flanking attack.

#### Block

**Stamina Cost:** 1  
**Action Speed:** Reaction

Use a wielded item with the block feature to block all incoming attacks or spells coming from in front of you, adding its block value to your damage reduction. If this action is used to block projectiles, add its block value to your armour class instead. While blocking you cannot see in front of you.

#### Brandish

**Action Speed:** Free

Choose which of your items you are wielding in your hands. This can be items from your inventory, or items found in your immediate area.

#### Drop Prone

**Action Speed:** Free

You become prone. Ranged attacks against prone characters are made with disadvantage, but melee attacks are made with advantage.

#### Evade

**Stamina Cost:** 1  
**Action Speed:** Reaction

Roll your evasion to defend against an attack instead of using your deflection. While evading, attacks made against you that result in a graze are instead considered a failure. After you evade, you may move a distance up to half your speed.

#### Interact

**Action Speed:** Variable

This action covers most basic actions, like opening doors, activating wielded items, or using objects in the immediate area. Unless an object specifies, or a task requires an extended amount of time to perform, this action is usually considered a swift action.

#### Move

**Stamina Cost:** 0 or 1  
**Action Speed:** Swift or Free

Move a distance up to your speed. If you move more than 1m, this is considered a swift action, otherwise, it is considered a free action. Additionally, this action costs 1 stamina if it is not the first time you have used it during your turn.

If the terrain you are moving over is rough or difficult to navigate, then you can only move half as far over that terrain.

#### Parry

**Stamina Cost:** 1  
**Action Speed:** Reaction

Use a wielded item with the parry feature to block an attack, adding its parry value to your deflection. While parrying, attacks made against you that result in a graze are instead considered a success.

#### Ready

**Action Speed:** Standard

Declare any standard, swift, or free action to use as a reaction given a specified trigger of your choice. For example: while standing at the end of a hallway, you can ready an attack action against any targets that come into view (such as from a room attached to that hallway). Readied actions are performed immediately, even if that means they might happen in the middle of, or before, another action.

#### Seek Cover

**Action Speed:** Swift

If you are next to a barricade, or the edge of a wall, or some similar structure, you can seek cover behind that object. While being provided cover, you are considered to be partially concealed from ranged enemies until your next turn, giving disadvantage to ranged attacks and spells made against your deflection and evasion. You can also use this action as a free action if you have moved more than once during your turn. If you do, you do not need to hide behind an obstacle to get the benefits; it is as though you are using your speed and movement to avoid being targeted from a distance.

#### Use Skill

**Action Speed:** Variable

Skills can be performed as normal during any type of encounter. The exact duration that a skill takes to perform is the same as it would be during any complex challenges. As some skills may take more than a few minutes, this means that most characters who attempt to use advanced skills during a combat encounter may effectively find themselves removed from combat (unless they leave their attempt as incomplete).

# Damage

When a character is hit by an attack, trap, or any means, they will take damage. Any damage dealt to a character is taken first to their endurance, and then to their health if no endurance remains. If a character is ever reduced to zero or less health, that character is given the dying condition. Attacks made by weapons with the nonlethal feature cause a creature to be given the unconscious condition instead of the dying condition. If nonlethal attacks bring a character to negative health equal to their maximum health, then they get the dying condition.

Damaging items or objects is done by making the relevant skill checks against a difficulty value based on the perceived difficulty to break that item or object (as determined by the Game Master). For example: breaking a door with an axe would be an athletics or martial check against an arbitrary difficulty value (if the door was made of wood, it would likely be easy).

# Effects

The duration of the following effects are considered permanent unless specified by the circumstance which provides these effects to an object or character. Most effects are normally temporary.

#### Blind

Blinded characters suffer a disadvantage to all rolls that require that character to attack, interact with, brandish, or use special abilities at, a specified target. This does not count for interacting with or brandishing their own personal items. In addition to this, all terrain is difficult to move across.

#### Burning

Burning objects are dangerous and likely to cause nearby objects to continue to burn if not contained or extinguished. Burning characters suffer damage over time. When applied to a character, burning is an effect that has multiple degrees, as specified by a number. If a burning character has burning applied to them, add the burning values together. At the beginning of a burning character's turn, they take fire damage equal to r4 plus r2 for every degree of burning beyond the first, then the burning effect decreases by 1, until it goes away entirely. Burning 1 would be r4 damage, while burning 3 would be r8 damage. Fire damage bypasses damage reduction. Dousing a target in water will completely remove the burning.

#### Debilitation

A debilitation is an effect that applies to one of your stats. Debilitated stats when rolled are made with a disadvantage. Multiple debilitations to the same stat do not stack.

#### Dying

When a character is given the dying effect they are also given the unconscious effect. At the start of each turn that a character is dying, they must make a fortitude check versus a difficulty of r12 plus their negative health. If that character succeeds three times, they lose the dying condition, but remain unconscious. If they fail three times, they die. Criticals count as two successes, and fumbles count as two failures. Successes and failures do not need to be consecutive. Stabilized characters remain at negative health. At the end of every round that a character is dying they lose one more health.

#### Encumbered

Encumbered characters are carrying too much. They get a disadvantage to both strength and dexterity, and halved speed.

#### Enhancement

An enhancement is an effect that applies to one of your stats. Enhanced stats when rolled are made with an advantage. Multiple enhancements to the same stat do not stack.

#### Overencumbered

Overencumbered characters suffer the same effects as encumbered characters, but instead of moving at half speed, they cannot move.

#### Prone

Prone characters are either kneeling or laying down on the ground. Ranged attacks against prone characters are made with disadvantage, but melee attacks are made with advantage. You must spend a swift action to stand up from being prone.

#### Sickness

Sickness is an effect that has multiple degrees, as specified by a number. This number is a penalty that you take to *all* of your rolls. Additionally, every day that you are sick you lose health equal to half this sickness value.

#### Stunned

At the beginning of a stunned character's turn, they lose the stunned effect and a swift action.

#### Unconscious

Unconscious characters can perform no actions. Loud noises or other disrupting behaviour may awaken an unconscious individual.

# Resting

At some point during an adventure you may find yourself low on your resources (health, endurance, stamina, and mana). In order to restore these resources, you need to rest. There are three different types of rests: the short rest, moderate rest, and long rest. Depending on the type of rest performed, you will recover a different amount of your spent resources.

##### Table: Rest Recovery Rates
| Resource | Short Rest | Moderate Rest | Long Rest |
|:-|:-:|:-:|:-:|
| Health | None | None | 1 |
| Endurance | Quarter, round up | Half, round up | All |
| Stamina | Roll STR or DEX,<br/>quartered, round up | Roll STR or DEX,<br/>halved, round up | Roll STR or DEX |
| Mana | Roll INT or RES,<br/>quartered, round up | Roll INT or RES,<br/>halved, round up | Roll INT or RES |

### Short Rest

A short rest is basically like a break. Whenever you take a break to make preparations over a period of thirty minutes to an hour, that would be considered a short rest.

### Moderate Rest

Moderate resting involves relaxation for an extended period of about four hours. Sleep is not necessary to qualify as a short rest. A single activity can even be taken during this period, such as performing research or crafting an item.

### Long Rest

A long rest requires about eight hours of sleep. This sleep may be interrupted so long as it is resumed relatively quickly (within one hour). If such a rest is interrupted part way and not resumed, then it is considered to be a short rest instead. Abilties that can be used a number of times per rest can only be restored from a long rest unless otherwise specified.

Characters with substantial wounds will require substantial rest to recover. Other characters may treat the wounds of a character performing a long rest by using the medicine skill by perfoming a medicine check against a difficulty of 10. If successful, the amount of health that characters heals during their long rest is increased to 2.

# Creating a Character

The process of creating a character is a series of small steps. A character is made up of a few aspects: *race*, *background*, *archetype*, and *trait*. As a reminder, whenever you assign any stat or skill a roll value, it does not mean to roll those dice and assign it the resulting value. It means that you assign it the roll value itself. This represents what you roll when you use that stat or skill.

### Race

It is not guaranteed that a genre or setting has a multitude of racial options, but Humans are usually an available option. The race you pick will provide bonuses to your primary stats, a racial ability, and determine your size and movement speed.

Click [here](/Fantasy/Races.md) for a list of fantasy races.

### Background

Backgrounds are the profession or history of your character before they left that life behind them to become an adventurer or hero (or whatever the genre you are playing calls them). The background you choose will provide bonuses to some of your skills.

Click [here](/Fantasy/Backgrounds.md) for a list of fantasy backgrounds.

### Archetype

Archetypes get you on the path to building a character with a strong theme, but they do not limit any of your character advancement options. Essentially they are a title that provides you with some benefits, much like backgrounds. They determine what skills and abilities you start with.

Click [here](/Fantasy/Archetypes.md) for a list of fantasy archetypes.

### Trait

Traits are unique abilities that only you possess. This part of character creation is entirely up to you (and your Game Master). Generally traits are special things you can do or have. Typically they provide opportunities to roleplay in a unique way, or help make your character stand out from others with a similar background or archetype. They can be mundane or magical in nature, and are something you can describe in a couple sentences. Traits should provide some degree of actual mechanical benefit, but the exact benefit is to be determined by the context of your adventure and what your Game Master determines is fair.

The trait you decide upon can be something very similar to an existing talent or spell, but the obvious drawback is that you don't get some other type of unique ability.

Click [here](/Basic/Traits.md) for a list of example traits.

### Starting Stats

After choosing your race, background, archetype, and trait, you will need to decide what your starting primary stats are. Assign one of them to be *above average* (r12), one of them to be *below average* (r8), and the rest as *average* (r10).

### Motivation

One of the most important defining features of a character is their motivation. It can be described in a few sentences or less. Ultimately it will be a source of both conflict and cooperation, as characters will need to make decisions that fulfill their motivations. Characters that fulfill their motivations during a game session provide an experience bonus to all participating player's characters.

Example: To protect the weak from those who abuse their power.

Some motivations may represent more circumstantial character developmental ordeals. These types of motivations when completed are usually then replaced with another motivation, assuming that it doesn't end that character's heroic journey. Because these types of motivations are more difficult to complete, making progress towards completing that motivation is enough to provide the experience bonus.

Example: To find a lost family member; or to avenge a death.

# Equipment

Characters may start with some degree of currency or equipment. Most items that a character can acquire and use are normal worldly items. If you can imagine an object or device, it is an item a person can have and use. The only restriction is if it meets the setting you are playing in. For example: machine guns or flashlights are not a likely device to have in a fantasy setting, but a torch or a sword is.

Although you can use any type of item you can imagine approriate to your adventure, some items are explicitly made available, including their cost, weight, and specific features. Among these, armour and weapons are explicitly defined. For each of both armour and weapons, they are given tables detailing what to expect from such items. Additionally, armour and weapons may have additional features to help differentiate them.

Some items may seem better than others, but depending on the genre that uses them, some may be more or less expensive, or have various minor requirements or drawbacks.

Click [here](/Fantasy/Equipment.md) to see the rules and tables for fantasy equipment.

### Armour

Although a character can wear any amount of gear, such as boots, cloaks, clothes, gloves, helmets, rings, and so on, only some of these items are considered as *armour*. Armour exists in a few specific *equipment slots* when worn: *body*, *head*, *wrist*, and *feet*. Armour items will have some minor features, but usually they also have an armour class and a damage reduction. These values from all your slots are added together to provide a total armour class and damage reduction.

Some armours will have a strength value listed. This value is the recommended strength required to wear that armour. If your maximum strength does not meet the requirement, then you get a penalty to your dexterity equal to half of the difference (rounded up). For example: if you have a maximum strength of 11, and you are wearing a piece of armour with a strength requirement of 16, you will get –3 to your dexterity. This is known as the *armour penalty*.

### Weapons

Weapons are the means to inflict attacks upon opponents using the combat skills. Weapons exist in multiple categories named after the combat skill required to use them. There is also a category of basic weapons, which can be used by anyone trained in any of the combat skills. Weapons have a listed damage dice and type as some combatants and armours may be weaker to certain damage types. Additionally, although unarmed attacks are not actually made with weapons, they are usually listed as a weapon for clarity on their stats.

### Carrying Capacity

Many items will have a listed weight. Although it is optional to keep track of the weight of items, sometimes it might be necessary if a character is carrying an exceptional amount of them, especially heavy ones. In this case you would need to determine the carrying capacity of a character. This is determined as a product of their size and maximum strength. Although items do not have a listed size or bulk, use reason to determine how many items a character can carry.

##### Table: Carrying Capacity
| Modifier | Formula |
|:-|:-|
| Light Capacity (kg) | Max STR × 4 |
| Heavy Capacity (kg) | Max STR × 7 |
| Tiny | Capacity × ¼ |
| Very Small | Capacity × ½ |
| Small | Capacity × ¾ |
| Medium | Capacity × 1 |
| Large | Capacity × 1½ |
| Very Large | Capacity × 2 |
| Huge | Capacity × 3 |

If a character exceeds their light capacity they become encumbered (getting a disadvantage to all rolls with strength and dexterity, and halved speed). If they exceed their heavy capacity then they become overencumbered (and cannot move).

Casual carrying of items over extended periods of time is different than momentary displays of physical ability. Typically you can expect that someone can lift items near their heavy capacity over a very short distance, or drag something weighing twice that amount over a moderate distance (up to four times that amount if assisted by wheels).

# Advancing a Character

As you play the game your character will acquire experience points. As a baseline each character receives 3 experience points at the end of every game session. For each player that met their character's goals during that session, all players receive an additional 2 experience points. This bonus stacks for each player that met their goals. Additionally, if a major goal of the campaign is met then each player receives a bonus 3 experience points. These points can be spent to improve your character's stats and skills, and to acquire new abilities. The cost to improve your stats and skills depend on what your current dice step is. 

##### Table: Primary Stat Steps & Cost
| Step Cost | Total Cost | Roll Value | Step Name |
|:-:|:-:|:-:|:-|
| - | - | r8 | Below Average |
| 10 | 10 | r10 | Average |
| 12 | 22 | r12 | Above Average |
| 14 | 36 | r14 | Great |
| 16 | 52 | r16 | Superb |
| 18 | 70 | r18 | Powerful |
| 20 | 90 | r20 | Epic |

Although you do not spend experience points to obtain your starting primary stats, the costs for each step are still listed. This helps provide context for the value of your stats.

##### Table: Skill Steps & Cost
| Step Cost | Total Cost | Roll Value | Step Name |
|:-:|:-:|:-:|:-|
| 2 or 4<sup>1</sup> | 2 | r4 | Trained |
| 3 | 5 | r6 | Adept |
| 4 | 9 | r8 | Practiced |
| 5 | 14 | r10 | Proficient |
| 6 | 20 | r12 | Exceptional |
| 7 | 27 | r14 | Disciplined |
| 8 | 35 | r16 | Accomplished |
| 9 | 44 | r18 | Expert |
| 10 | 54 | r20 | Master |

<sup>1</sup>Becoming trained in any advanced skill costs 4 experience points rather than the usual 2.

Talents can also be acquired at varying costs dependent on the specific talent. These will provide more breadth of ability to your character rather than raw numerical improvement. You can even acquire talents that other archetypes start with.

Click [here](/Basic/Talents.md) for the list of universal talents.

Click [here](/Fantasy/Talents.md) for the list of fantasy talents.

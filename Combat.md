# Combat
Combat is a unfortunate reality among those who specialize in dealing with dangerous situations. Whether you have to fend off the cultists who are suspicious you know too much or accidentally got caught up slaying dragons, you will eventually find yourself trying to kill or incapacitate your opponents before they kill or incapacitate you. That is what this chapter is for.

## Overview
Combat is organized into [Rounds]. One [Round] is the time it takes everyone to take one turn in combat (in-game, it is between 2 and 10 seconds, usually 6). On your turn each [Round], you will lose any Action Points (AP) you previously had and receive 3 new AP that you can spend taking actions. When everyone's turn is over, a new [Round] begins.

### Initiative and Turn Order
When deciding who goes first in a [Round], have everyone roll 1d20 and add their initiative. By default, everyone takes actions in order from highest to lowest - break ties with a re-roll.

You can always choose to treat your initiative as lower than what you rolled.

You and an ally can swap positions in the initiative order at the beginning of combat. Whoever rolled higher takes the initiative score of the other. Whoever rolled lower takes the higher initiative score - 2, or their initiative score + 1, whichever is lower. _Example: Alice rolls a 17 and Bob rolls a 5. They swap, so Alice has a 5 and Bob has a 15. Example: Alice rolls a 12 and Bob rolls a 10. They swap. Alice has a 10 and Bob has an 11._

### On Your Turn
At the beginning of your turn, you lose any AP you did not use last [Round] and gain 3 new AP. You can then begin taking actions, spending AP as appropriate. The following table lists action types and their AP cost. The next section lists some common combat actions.

|Action Type|AP Cost|
|---|---|
|[Instant Action]|0 AP|
|[Fast Action]|1 AP|
|[Standard Action]|2 AP|
|[Slow Action]|3 AP|
|[Immediate Action]|0 AP*|
|[Reaction]|0 AP*|

__[Immediate Actions] and [Reactions]:__ These special kinds of actions can be taken when it is not your turn. Anything that is an [Immediate Action] or [Reaction] will list the precise conditions under which it can be taken. While you can take any number of [Immediate Actions], many GMs will limit this to a reasonable number (say, 3). However, you can only ever take a single [Reaction] per [Round]. 

## Common Actions

### Standard Attack
Also known as "attack." This is a [Standard Action]. Select one of your weapons you are currently wielding and an opponent you can target with that weapon. Make an attack roll. If you are using a martial weapon, you have to equal or exceed their AC to hit. If you are using a magical weapon, you have to equal or exceed their SR to hit (and use a spell attack roll).

_Attack roll = 1d20 + Strength + weapon bonuses + misc. bonuses_  
_Spell Attack Roll = 1d20 + Intelligence + weapon bonuses + misc. bonuses_

If the natural result of the d20 - the number that lands facing up - is equal to or greater than your weapons critical threshold, you scored a critical hit. If the attack roll still was not high enough to hit your opponent, you still hit but it is only a regular hit.

If your opponent currently has any [Miss Chances], check those now. Roll d%. If you roll less than or equal to their [Miss Chance], you hit. Otherwise, you miss. If you have a critical hit but would miss, you still hit but it is only a regular hit.

Then, you roll damage, based on the weapon. If a critical hit, multiply this by your weapon's critical multiplier. Then apply any [Weakness] or [Resistance] the target has. Then they subtract the damage from their health.

All told, the process looks like this:
1. Choose weapon and target
1. Attack roll
1. Miss Chance
1. Roll base damage
1. Apply critical multiplier, [Weakness], and [Resistance]
1. Target takes damage

### Standard Defense
A favorite of pacifists and defensive fighters. This involves using your weapon to interrupt enemy attacks, getting your shield in the way, or otherwise focusing on defense. This is a [Standard Action]. If you have a melee weapon, you may make an attack roll. Otherwise, roll 1d20 + initiative + one-half your level. Your AC and SR receive a +4 bonus until your next turn, but cannot exceed the results of this roll. This can only be used once per [Round].

### Move
This is a [Standard Action], allowing you to move up to your movement speed. When moving on a square grid, the first diagonal step as part of this movement counts as 5 feet, and every diagonal step after counts as 10 feet.

### 5-Foot Step
This is a [Fast Action]. You move 5 feet in any direction. You may only take one 5-foot step per turn.

### Cast a Spell
This is a [Fast Action] that advances a spell's casting by 1 AP. When you reduce the time needed to cast the spell to 0 AP, you may cast the spell as an [Instant Action] (some spells instead let you release the spell later, and you can always choose to let a spell fizzle). To finish casting the spell, you must immediately pay the spell's casting cost.

## Combat Maneuvers

### Charge
This is a [Slow Action]. Move up to your movement speed in a straight line, at least 10 feet, ending your movement adjacent to an enemy. Then make a single melee attack. You receive a +2 bonus on the attack roll and add your level to the damage. If you have special abilities that affect Power Attacks, you can choose to activate them on this attack.

### Quick Attack
This is a [Fast Action]. Make an attack. If the attack roll hits, the attack automatically does minimum damage.

### Quick Defense
This is a [Fast Action]. It works the same as Standard Defense, except your AC and SR can only go up by +2. This stacks with Standard Defense, but not with itself.

### Power Attack
This is a [Slow Action]. Make an attack. If the attack roll hits, you deal normal damage but roll the weapon's damage dice twice.

Example: The damage dice for a Longsword are 2d8, with Strength and one-half the wielder's level added to damage. On a Power Attack, the wielder rolls 4d8, adding their Strength and one-half their level.

## Optional Rules
These rules add more realism to combat, but they also add more bookkeeping, and are not needed to have a good time. As such, they are __strictly optional.__

### Reach
These rules make it easier to strike an opponent when your weapon is longer than theirs. It applies only to melee weapons.

Keep track of your weapon's reach, based on its length: 0 for short weapons, 1 for medium, 2 for large, 3 for huge. When attacked in melee, add your weapon's reach + your Strength to your AC. When you attack an opponent in melee, add your initiative + your weapon's reach to your attack roll.

### Wounds
These rules make combatants fight less effectively as they take more injuries. It makes small, quick attacks significantly more effective.

Keep track of how many wounds you currently have. You can have up to 15 wounds. If you suffer a wound while you have 15, you die. Each day, you heal 1 wound. A day of total rest instead heals 2 wounds.

You take a -1 penalty to AC, SR, and all attack rolls for each wound you have. When you take damage, if you take at least your base hp (4 + Constitution + Charisma) in damage, you gain 1 wound. This wound threshold can never be larger than one-tenth your maximum hp. Even if an attack deals significantly more damage, it still only counts as 1 wound.

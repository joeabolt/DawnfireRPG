# Combat
Combat is an unfortunate reality among those who specialize in dealing with dangerous situations. Whether you have to fend off the cultists who are suspicious you know too much or accidentally got caught up slaying dragons, you will eventually find yourself trying to kill or incapacitate your opponents before they kill or incapacitate you. That is what this chapter is for.

## Overview
Combat is organized into [Rounds]. One [Round] is the time it takes everyone to take one turn in combat (in-game, about 6 seconds). On your turn each [Round], you will lose any Action Points (AP) you previously had and receive 3 new AP you can then spend taking actions. When everyone's turn is over, a new [Round] begins.

### Initiative and Turn Order
When deciding who goes first in a [Round], have everyone roll 1d20 and add their initiative. By default, everyone takes actions in order from highest to lowest - break ties with a re-roll. You can always choose to treat your initiative as lower than what you rolled. After determining initiative order, it stays the same for the entire [Encounter].

You and an ally can swap positions in the initiative order at the beginning of combat. Whoever rolled higher takes the initiative score of the other. Whoever rolled lower takes the higher initiative score - 2, or their initiative score + 1, whichever is lower. _Example: Alice rolls a 17 and Bob rolls a 5. They swap, so Alice has a 5 and Bob has a 15. Example: Alice rolls a 12 and Bob rolls a 10. They swap. Alice has a 10 and Bob has an 11._

At the beginning of your turn, before you take any actions, you can choose to voluntarily lower your initiative score (delay). This is not an action in-game. You do not take your turn, instead taking it later that [Round] at the lower initiative score.

#### Optional: Team Initiative
If you and your teammates want to interact more, you can opt for team initiative. Only the the team member with the lowest initiative bonus rolls, and you all act on that initiative count. You can take actions in any order, even alternating between people. When everyone is done, turns advance as normal.

This requires more attention from players and GMs, so it is an optional rule. GMs, you can introduce this just for enemies as well.

### On Your Turn
At the beginning of your turn, you lose any AP you did not use last [Round] and gain 3 new AP. You can then begin taking actions, spending AP as appropriate. The following table lists action types, their AP cost, and their typical intensity. The next section lists some common combat actions. If you take an uncommon combat action, use the intensity on the following table to figure out how many AP it should be.

|Action Type|AP Cost|Intensity|
|---|---|---|
|[Instant Action]  |0 AP |Not an action, shouting, thinking, looking around|
|[Fast Action]     |1 AP |Can be done quickly, often with your eyes closed, sheathing or unsheathing a weapon, catching/throwing something, lunging; physically simple but requires mental effort|
|[Standard Action] |2 AP |Requires attention physically and mentally to execute, most attacks and blocks, most skill checks; moderately time-consuming activites like running
|[Slow Action]     |3 AP |Slow, intensive activities, lockpicking or special attacks. 
|[Immediate Action]|0 AP*|Non-action, talking, thinking
|[Reaction]        |0 AP*|Varies by the ability; usually instinctual and physically quick

__[Immediate Actions] and [Reactions]:__ These special kinds of actions can be taken when it is not your turn. Anything that is an [Immediate Action] or [Reaction] will list the precise conditions under which it can be taken. You can only ever take a single [Reaction] per [Round]. Though you can take any number of [Immediate Actions] per [Round], many GMs will limit this to a reasonable number (say, 3).

## Common Actions

### Standard Attack
Also known as "attack." This is a [Standard Action]. Select one of your weapons you are currently wielding and an opponent you can target with that weapon. Make an attack roll. With a martial weapon, you must equal or exceed their AC to hit. With a magical weapon, you must equal or exceed their SR, and use a spell attack roll.

_Attack roll = 1d20 + Strength + weapon bonuses + misc. bonuses_  
_Spell Attack Roll = 1d20 + Intelligence + weapon bonuses + misc. bonuses_

If the natural result of the d20 - the number that lands facing up - is equal to or greater than your weapon's critical threshold, you scored a critical hit. If the attack roll was not high enough to hit your opponent, you miss. If your attack roll was not high enough but was in your critical range, you land a regular hit - not a critical hit.

If your opponent currently has any [Miss Chances], check those now. Roll d%. If you roll less than or equal to their [Miss Chance], you hit. Otherwise, you miss. If you have a critical hit that would miss from [Miss Chances], it becomes a regular hit instead of a miss.

Then, roll damage as per your weapon. If a critical hit, multiply this total by your weapon's critical multiplier. Then apply any [Weakness] or [Resistance] the target has. Finally, the target subtracts the damage from their health.

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

### Run
This is a [Slow Action] that lets you move up to double your movement speed. As with Move, diagonal steps cost 10 feet, except for the first which costs 5 feet.

### 5-Foot Step
This is a [Fast Action]. You move 5 feet in any direction. You may only take one 5-foot step per turn.

### Cast a Spell
This is a [Fast Action] that advances a spell's casting by 1 AP. When you reduce the time needed to cast the spell to 0 AP, you may activate the spell as an [Instant Action] (some spells instead let you release the spell later, and you can always choose to let a spell fizzle). As part of activating a spell, you must immediately pay the spell's casting cost.

#### Partially-Cast Spells
You do not have to finish casting a spell on one turn. If you have a partially-cast spell and do not spend any AP progressing the casting by the end of your turn, you must make an Intelligence check or the spell immediately fizzles. The DC is 10 + twice the spell's tier. If you are casting multiple spells, the DC is 10 + twice the spell's tier + the highest tier of the other spells you are casting.

#### Casting Multiple Spells
You can cast multiple spells at the same time. When starting to cast another spell, you must make an Intelligence check to begin casting. The DC is 10 + twice new spell's tier + the highest tier of the spells you were already casting. If you fail, the action is wasted and the spell immediately fizzles.

## Death, Dying, and Healing
If your hit points ever fall below 0, you fall [Unconscious] and begin [Dying]. While [Dying], you must make a Constitution check each [Round] (DC 15 + number of negative hit points) or take 1 point of damage. As a [Slow Action], another creature can stabilize you, removing the [Dying] condition.

If your hit points reach -10, you become [Dead]. Stone dead. Deceased. Demised. Passed on. No more. Expired. Stiff. A proverbial ex-parrot.

Each day, you heal your Constitution hit points. If you spend the day resting, you heal twice your Constitution + your level. Medical attention can increase this, as per the Heal skill.

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
These rules make it easier to strike an opponent in melee when your weapon is longer than theirs. It applies only to melee weapons.

Keep track of your weapon's reach, based on its length: 0 for short weapons, 1 for medium, 2 for large, 3 for huge. When attacked in melee, add your weapon's reach + your Strength to your AC. When you attack an opponent in melee, add your initiative + your weapon's reach to your attack roll.

### Wounds
These rules make combatants fight less effectively as they take more injuries. It makes small, quick attacks significantly more effective.

Keep track of how many wounds you currently have. You can have up to 15 wounds. If you suffer a wound while you have 15, you die. Each day, you heal 1 wound. A day of total rest instead heals 2 wounds.

You take a -1 penalty to AC, SR, and all attack rolls for each wound you have. When you take damage, if you take at least your base hp (4 + Constitution + Charisma) in damage, you gain 1 wound. This wound threshold can never be larger than one-tenth your maximum hp. Even if an attack deals significantly more damage, it still only counts as 1 wound.

# Spells
A spell is a unit of magic that can be created relatively at will. Casting a spell generally requires both gesticulating wildly and speaking in a firm, stern voice - if a spell is an exception, it will be noted in its description.

Every spell has several details associated with it:
* __Tier__: A rough measure of power, between 1 and 10. Your level must be at least double the spell's tier to cast it, except for 1st-Tier spells, which anyone can cast. Many spell can be cast at multiple tiers to augment their power.
* __Element__: A spell's element has no mechanical effect, but it sorts them into groups. Some feats, magic items, or story events will use this value. There are five elements: Fire, Earth, Metal, Water, and Wood.
* __Casting Time__: The amount of AP required to cast the spell.
* __Casting Cost__: The amount of [HP Reduction] required to be paid to activate the spell.
* __Description__: The description of the spell's effects; the rules governing what happens when the spell is cast.
* __Range__: How far you can cast the spell. Generally comes in one of the following options:
    * _Personal_: The spell can only target you or your space.
    * _X Feet_: The spell can target any valid target within X feet.
    * _Touch_: The spell can target any valid target that you can touch.
    * _Eye_: The spell can target any valid target that you make eye contact with. In social situations, most people will make eye contact. In combat, no one will. Animals will after 1 [Round] if not in combat. A suspecting and unwilling target can avoid this spell (though an unsuspecting target cannot).
    * _Voice_: The spell can affect a valid target where your voice reaches (usually 60 feet, further if you shout, shorter if you whisper, self only if you say nothing).
    * _Sight_: The spell can affect a valid target that you can see. While [Blinded], you can only target yourself.
    * _Connection_: The spell can affect any valid target you have a connection to. The spell will define what "connection" means - sometimes as little as knowing their name, sometimes having one of their possessions or a part of their body.
* __Duration__: How long the spell lasts. Generally comes in one of the following options:
    * _Instantaneous_: The spell effect occurs as soon as you finish casting the spell and does not continue afterward.
    * _Concentration_: The spell begins immediately and lasts as long as you spend a [Fast Action] each [Round] concentrating on it.
    * _Encounter_: The spell lasts until the end of the [Encounter].
    * _Sun_: The spell lasts until the sun next rises or sets.
    * _Moon_: The spell lasts until both the full and new moon have set.
    * _X time periods_: The spell lasts until X time periods have gone by. This could be 3 [Rounds], 2 weeks, 6 days, or 1 year, for example.
* __Target__: What the spell can target. Generally comes in one of the following options:
    * _X Creatures_: The spell can target up to X creatures.
    * _X-ft Burst_: The spell targets a single 5-foot square, and all squares within X feet of it. You only need line of effect to the target square. A burst cannot go around obstacles.
    * _X-ft Aura_: This functions as an X-ft Burst, except that it can bleed around obstacles (though not further than X feet).
    * _X-ft Line_: The spell targets a single 5-foot square, and all squares up to X feet away in a straight line.
    * _X-ft Cone_: The spell targets a single 5-foot square, and all squares within X feet of it along a 90-degree arc (quarter-circle).
    * _Room_: The spell affects a clearly enclosed space and all targets within it. For example: a broom cupboard, the nave of a cathedral, or a forest clearing, but not an alpine valley or a room-sized volume of empty space.
    * _Boundary_: The spell affects everything within a boundary, such as the edge of a forest, the shores of a lake, the edge of a farm plot, or the walls of a city. There must be a clear boundary - this cannot affect abritrary space.

## Spell Attack Rolls
These come up reasonably frequently.

_Spell Attack Roll = 1d20 + Intelligence + spell Tier + misc. bonuses_

## Fireball
__Tier:__ 1; __Element:__ Fire;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ 30 feet; __Duration:__ Instantaneous; __Target:__ 5-ft burst;  
__Description:__ Your point your finger and a small white bead of flame streaks forward, detonating in the target square in a burst of flame. Make a spell attack roll, and compare it to all targets' SR. This spell deals 1d6 + your Charisma [Fire] damage to all targets, +2d6 [Fire] to targets that did not resist.

You can cast Fireball at a higher tier. Each time you increase the tier, do the following:
* Increase the range by 10 feet.
* Increase the damage by 1d6 + your Charisma when you beat an opponent's SR.
* If now an even tier, increase the burst radius by 5 feet.
* Either:
    * Increase the casting time by 1 AP, or
    * Increase the casting cost by 5 [HP Reduction].

The following table summarizes these changes for your ease:

|Tier|Max Casting Time|Max Casting Cost|Range|Radius|Damage Dice|Charisma|
|---|---|---|---|---|---|---|
|1 |2 AP |5 |30 |5 |3d6 |x1
|2 |3 AP |10|40 |10|4d6 |x2
|3 |4 AP |15|50 |10|5d6 |x3
|4 |5 AP |20|60 |15|6d6 |x4
|5 |6 AP |25|70 |15|7d6 |x5
|6 |7 AP |30|80 |20|8d6 |x6
|7 |8 AP |35|90 |20|9d6 |x7
|8 |9 AP |40|100|25|10d6|x8
|9 |10 AP|45|110|25|11d6|x9
|10|11 AP|50|120|30|12d6|x10

## Heroism
__Tier:__ 1; __Element:__ Fire;  
__Casting Time:__ 1 AP; __Casting Cost:__ 3 [HP Reduction];  
__Range:__ Voice; __Duration:__ 3 [Rounds]; __Target:__ 1 creature;  
__Description:__ You point out one ally and speak a short, bold, inspiring incantation, bolstering the target's courage and capability. They receive a +2 bonus to any two of the following that you choose:

* Weapon attack rolls
* Weapon damage rolls
* Spell attack rolls
* Spell damage rolls
* Armor Class
* Spell Resistance
* Skill checks on one skill you choose
* Ability checks with one ability score you choose

If you cast this spell on the same target while a previous casting is active, the bonuses do not stack. You may grant more types of bonuses through multiple castings. Each time you cast this spell on the same target, the duration resets for all bonuses affecting them.

## Word of Calm
__Tier:__ 1; __Element:__ Fire;  
__Casting Time:__ 1 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Voice; __Duration:__ 10 minutes, see text; __Target:__ 1 creature;  
__Description:__ With a soothing word, you instill calm into a creature your voice reaches - you need not gesture to cast this spell. Make a spell attack roll against the target's SR. If they resist, they take a -2 penalty to attack and damage rolls for 1 [Round]. If you succeed, they are magically calmed for up to 10 minutes. They can still defend themselves, and if they are harmed the spell is broken. Otherwise, they avoid conflict, either dodging the confrontation or refusing to fight. Keep in mind that a calmed creature is not necessarily a compliant one, just not hostile.

After the 10 minutes pass, they may remain calm if there are no stressors present. Regardless, they are aware that you enchanted them and may not take kindly to you in the future.

## Control Object
__Tier:__ 1; __Element:__ Earth;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Voice; __Duration:__ 3 [Rounds]; __Target:__ 1 inanimate object;
__Description:__ You shout a command at an object, and it immediately moves to obey. This allows you to control the object, but it can only move in ways it is designed to - a door can swing on its hinges, a rope can move in almost any direction, and a lock can turn, but a sword cannot swing itself, a potion cannot uncork itself, and a rock cannot roll. If you cast this spell again while it is currently active, the first instance of the spell immediately ends.

If you target an object in another creature's possession, you must make a spell attack roll against the possessor's SR. If you succeed, this spell works normally. If you fail, you may only issue a single swift command to the object - a book can slam shut or an unlocked chest can pop open, but a necklace cannot strangle its wearer, nor can a lock undo itself.

If the Strength of this spell comes into question (say, a door trying to hold itself shut), treat its Strength as your Charisma.

You may cast this spell above 1st tier. Each time you increase the tier:
* Increase the duration by 1 [Round].
* Increase either the casting cost by 3 [HP Reduction] or the casting time by 1 AP.

## Lightning Bolt
__Tier:__ 1; __Element:__ Earth;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Personal; __Duration:__ Instantaneous; __Target:__ 30-ft line;  
__Description:__ Your point your finger and a bolt of lightning thunders forth, electrifying everything in its path. Make a spell attack roll, and compare it to all targets' SR. This spell deals 1d6 + your Charisma [Electricity] damage to all targets, +2d6 [Electricity] to targets that did not resist.

You can cast Lightning Bolt at a higher tier. Each time you increase the tier, do the following:
* Increase the line length by 20 feet.
* Increase the damage by 1d6 + your Charisma when you beat an opponent's SR.
* Either:
    * Increase the casting time by 1 AP, or
    * Increase the casting cost by 5 [HP Reduction].

The following table summarizes these changes for your ease:

|Tier|Max Casting Time|Max Casting Cost|Range|Damage Dice|Charisma|
|---|---|---|---|---|---|---|
|1 |2 AP |5 |30 |3d6 |x1
|2 |3 AP |10|50 |4d6 |x2
|3 |4 AP |15|70 |5d6 |x3
|4 |5 AP |20|90 |6d6 |x4
|5 |6 AP |25|110|7d6 |x5
|6 |7 AP |30|130|8d6 |x6
|7 |8 AP |35|150|9d6 |x7
|8 |9 AP |40|170|10d6|x8
|9 |10 AP|45|190|11d6|x9
|10|11 AP|50|210|12d6|x10

## Mage Armor
__Tier:__ 1; __Element:__ Earth;  
__Casting Time:__ 3 AP; __Casting Cost:__ 3 [HP Reduction];  
__Range:__ Touch; __Duration:__ [Sun], or until dismissed; __Target:__ 1 creature;  
__Description:__ A number of magical planes of [Force] slowly swirl around the target creature, blocking incoming attacks. They increase the target's AC by +4, or by +2 if the target is wearing armor. As an [Immediate Action], when the target receives a critical hit, they may dismiss this spell to make the attack miss.

This spell can be cast above 1st Tier. Each time you increase the tier, do the following:
* Increase the AC bonus by +1. The armored bonus is always one-half this value
* Increase the casting cost by 3 [HP Reduction]

## Shield
__Tier:__ 1; __Element:__ Earth;  
__Casting Time:__ 1 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Touch; __Duration:__ [Encounter], or until depleted; __Target:__ 1 creature;  
__Description:__ You summon a shield-sized plane of [Force] that automatically moves around a creature you designate, protecting them against harm. It provides a +2 bonus to AC while active, or +4 against ranged attacks. If you are targeted by the Magic Missile spell, the shield automatically negates it - the shield can do this 5 times, after which it is destroyed.

You can cast this spell above 1st Tier. Each time you increase the tier, do the following:
* Increase the number of Magic Missiles the shield can negate by 1

## Blade Barrier
__Tier:__ 3; __Element:__ Metal;  
__Casting Time:__ 2 AP; __Casting Cost:__ 12 [HP Reduction];  
__Range:__ 60 feet; __Duration:__ 6 [Rounds]; __Target:__ 60-ft line;  
__Description:__ Your voice and elaborate gesticulation call forth a wall of whirling blades made entirely of pure [Force] - these frequently glow based on the caster, with pink, blue, white, and violet being common. The wall is up to 60 feet long, up to 15 feet high, and 5 feet deep. Any creature moving through the wall takes 3d6 damage + 3 times your Charisma [Force] damage. Creatures ending their turn in the wall take 6d6 + 6 times your Charisma [Force] damage. Creatures in the wall when it is created may use an [Immediate Action] to step 5 feet to either side.

While the wall is active, you can summon one of its swords into your hand as an [Instant Action]. These are one-handed weapons, deal 2d8 + Charisma + Strength [Force] damage on a hit, and can be thrown up to 30 feet. The swords use martial attack rolls against SR. Only you can wield the swords.

You can cast this spell above 3rd Tier. Each time you increase the tier, do the following:
* Increase the wall's damage dice by 1d6, up to 12d6
* Increase the sword's damage by +2
* Increase the casting cost by 4 [HP Reduction]

## Counterspell
__Tier:__ 1; __Element:__ Metal;  
__Casting Time:__ 2 AP, see text; __Casting Cost:__ 0 [HP Reduction], see text;  
__Range:__ Voice; __Duration:__ Concentration/Instantaneous; __Target:__ 1 spell;  
__Description:__ You murmur and wring your hands, preparing a small bundle of antimagic that can be used to counter an enemy spell. When you finish casting the spell, it does not automatically fire, and you may begin concentrating as a [Fast Action] each [Round] to save it for later. You fire the counterspell as a [Reaction] or as an [Instant Action] when an enemy within range of your voice finishes casting a spell. Roll 1d6 per point of [HP Reduction] accepted when you cast this spell. If you exceed their spell attack roll (they make one now if they did not have to for the spell), their spell is countered and has no effect.

When casting Counterspell at the same time as another spell, 

You can use Counterspell on itself; indeed, this is a rather common feature of wizard duels. Wands and staves with Counterspell can be designed with a flat cost of 5 [HP Reduction] (plus any [HP Reduction] to grant the counterspell strength) to allow them to charge and cast it as a [Fast Action].

## Gust of Wind
__Tier:__ 1; __Element:__ Metal;  
__Casting Time:__ 1 AP; __Casting Cost:__ 3 [HP Reduction];  
__Range:__ Personal; __Duration:__ 3 [Rounds]; __Target:__ 30-ft line;  
__Description:__ You call to the wind and it gathers in your open palm. Casting this spell requires a free hand for the duration - picking up an object in that hand ends the spell. While this spell is active, you may fire a 30-ft line of intense wind as a [Standard Action]. Any creature or object in the line is thrown backwards. Make a spell attack roll, using 12 + their Strength + 2 for each size category above Medium as their defense. If you succeed, they are [Knocked back] 15 feet. If they resist, they are still pushed 5 feet away from you.

If you are trying to push an object, treat the gust's Strength as 1d6 + your Charisma.

The gust automatically extinguishes nonmagical fires and disperses fog in its path. For protected or magical flames, roll 1d6 and add your Charisma. If you equal or exceed 7, flames that are either magical or protected are extinguished. If you equal or exceed 12, flames that are magical and protected are also extinguished.

No matter what you think, or what physics textbooks you use to "prove" it, this spell cannot move you. The laws of magic laugh at your paltry laws of physics. Any attempt to use this spell that relies on physics automatically fails (you still lose the action and take the [HP Reduction]). The spell resumes functioning normally when you cease being too creative for your own good.

## Magic Missile
__Tier:__ 1; __Element:__ Metal;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ 30 feet; __Duration:__ Instantaneous; __Target:__ 3 magical darts;  
__Description:__ You sweep your hand outward, throwing out 3 darts of pure force that speed unerringly to their targets. This spell deals 1d6 [Force] damage with each dart. You can send multiple darts to the same target if you so choose.

You can cast Lightning Bolt at a higher tier. Each time you increase the tier, do the following:
* Increase the range by 5 feet.
* Increase the number of darts by 1.
* Either:
    * Increase the casting time by 1 AP, or
    * Increase the casting cost by 5 [HP Reduction].

The following table summarizes these changes for your ease:

|Tier|Max Casting Time|Max Casting Cost|Range|Darts|
|---|---|---|---|---|---|---|
|1 |2 AP |5 |30 |3 
|2 |3 AP |10|35 |4 
|3 |4 AP |15|40 |5 
|4 |5 AP |20|45 |6 
|5 |6 AP |25|50 |7 
|6 |7 AP |30|55 |8 
|7 |8 AP |35|60 |9 
|8 |9 AP |40|65 |10
|9 |10 AP|45|70 |11
|10|11 AP|50|75 |12

## Cone of Cold
__Tier:__ 1; __Element:__ Water;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Personal; __Duration:__ Instantaneous; __Target:__ 15-ft cone;  
__Description:__ You wave your hand and a wave of hoarfrost pours forth. Make a spell attack roll, and compare it to all targets' SR. This spell deals 1d6 + your Charisma [Cold] damage to all targets, +2d6 [Cold] to targets that did not resist.

You can cast Cone of Cold at a higher tier. Each time you increase the tier, do the following:
* Increase the cone radius by 5 feet.
* Increase the damage by 1d6 + your Charisma when you beat an opponent's SR.
* Either:
    * Increase the casting time by 1 AP, or
    * Increase the casting cost by 5 [HP Reduction].

The following table summarizes these changes for your ease:

|Tier|Max Casting Time|Max Casting Cost|Range|Damage Dice|Charisma|
|---|---|---|---|---|---|---|
|1 |2 AP |5 |15 |3d6 |x1
|2 |3 AP |10|20 |4d6 |x2
|3 |4 AP |15|25 |5d6 |x3
|4 |5 AP |20|30 |6d6 |x4
|5 |6 AP |25|35 |7d6 |x5
|6 |7 AP |30|40 |8d6 |x6
|7 |8 AP |35|45 |9d6 |x7
|8 |9 AP |40|50 |10d6|x8
|9 |10 AP|45|55 |11d6|x9
|10|11 AP|50|60 |12d6|x10

## Dowse
__Tier:__ 1; __Element:__ Water;  
__Casting Time:__ 3 AP; __Casting Cost:__ 1 [HP Reduction];  
__Range:__ 720 ft; __Duration:__ Instantaneous; __Target:__ Self;  
__Description:__ You hold up your arms in front of you, feeling magical auras through them, and detecting the nearby presence of a number of objects. You can detect any of the objects listed at the end of the description, but only one per casting. 

You detect the direction toward the most prominent example in range. If you are next to a stream and a large lake is in range, this spell detects the lake. If this spell finds a target, you may then make a spell attack roll to gain the extra information listed in parentheses. If you beat DC 20, you get 1 piece of information of your choice, +1 for every 5 by which you beat the DC.

You can dowse for:
 * Magical auras (the element; if the caster is within 4 levels of you, higher level, or lower level)
 * Water (whether it is fresh- or saltwater; whether it is flowing or stagnant)
 * Living plant matter, such as a tree or shrubbery (approximate size; approximate age; and health)
 * Stone (whether it is natural or carved; whether it is disconnected from other stone or not)

## Harm
__Tier:__ 1; __Element:__ Water;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Touch; __Duration:__ Instantaneous; __Target:__ 1 creature;  
__Description:__ Your hands burn with dark fire as you lay them on the subject. If the target resists, make a spell attack roll against the target's SR. This spell deals 1d6 + your Charisma [Negative] damage, +1d6 [Negative] if the target did not or failed to resist.

You can cast Harm at a higher tier. Each time you increase the tier, do the following:
* Increase the damage by 1d6 when you beat an opponent's SR or they do not resist.
* Either:
    * Increase the casting time by 1 AP, or
    * Increase the casting cost by 5 [HP Reduction].

## Heal
__Tier:__ 1; __Element:__ Water;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Touch; __Duration:__ Instantaneous; __Target:__ 1 creature;  
__Description:__ Your hands glow with warm light as you lay them on the subject. If the target resists, make a spell attack roll against the target's SR. This spell deals 1d6 + your Charisma [Positive] damage, +1d6 [Positive] if the target did not or failed to resist.

You can cast Heal at a higher tier. Each time you increase the tier, do the following:
* Increase the damage by 1d6 when you beat an opponent's SR or they do not resist.
* Either:
    * Increase the casting time by 1 AP, or
    * Increase the casting cost by 5 [HP Reduction].

## Message
__Tier:__ 1; __Element:__ Water;  
__Casting Time:__ 2 AP; __Casting Cost:__ 2 [HP Reduction];  
__Range:__ Eye; __Duration:__ 5 minutes; __Target:__ Up to 3 creatures;  
__Description:__ With quick, pointed glances you form a telepathic link between up to 3 creatures, possibly including yourself as one of the targets. This spell is silent to cast. Creatures linked telepathically can communicate at any distance. If you cast this spell multiple times, one entire link can be used as a target - this allows you to add 1 or 2 other creatures to it. When used this way, this spell also resets the duration on that link.

## Regeneration
__Tier:__ 3; __Element:__ Water;  
__Casting Time:__ 6 AP; __Casting Cost:__ 12 [HP Reduction];  
__Range:__ Touch; __Duration:__ Sun; __Target:__ 1 creature;  
__Description:__ You run your hands over the target's wounds and whisper secret chants, commanding the flesh to knit itself together again. The target heals half their current damage over time until the sun next rises or sets, at least 3 hours. This is a slow process, so if they get in combat early, they may not have fully healed.

This spell also regenerates any damaged organs. If a severed limb is present and secured against the body, the limb reattaches to the body. Reattaching limbs is an excellent way to get nasty diseases, so thorough cleaning or a remove disease spell is recommended.

This spell can heal living creatures, undead creatures, and creatures that heal through other means (such as constructs), as long as they have a physical form.

## Translation
__Tier:__ 2; __Element:__ Water;  
__Casting Time:__ 3 AP; __Casting Cost:__ 10 [HP Reduction];  
__Range:__ Personal; __Duration:__ Sun; __Target:__ Self;  
__Description:__ A quick word and passing a hand over your face allows you to understand any language you read or hear until the sun next sets or rises. This does not let you speak or write these languages. Particularly arcane languages may still elude this spell - notably, Faerie and Celestial tongues.

## Acid Cloak
__Tier:__ 1; __Element:__ Wood;  
__Casting Time:__ 2 AP; __Casting Cost:__ 5 [HP Reduction];  
__Range:__ Personal; __Duration:__ 3 [Rounds]; __Target:__ 5-ft aura;  
__Description:__ With a word and quick gesture, vitriolic mist gathers around you. This spell deals 1d6 + your Charisma [Acid] damage to all targets. At the beginning of your turn each [Round] the spell is active, deal this damage again to all targets in range. This spell does not stack, but casting it while it is active resets the duration.

You can cast Acid CLoak at a higher tier. Each time you increase the tier, do the following:
* Increase the damage by your Charisma when you beat an opponent's SR.
* If now an even tier, increase the burst radius by 5 feet.
* Either:
    * Increase the casting time by 1 AP, or
    * Increase the casting cost by 5 [HP Reduction].

The following table summarizes these changes for your ease:

|Tier|Max Casting Time|Max Casting Cost|Range|Charisma|
|---|---|---|---|---|---|---|
|1 |2 AP |5 |5 |x1
|2 |3 AP |10|10|x2
|3 |4 AP |15|10|x3
|4 |5 AP |20|15|x4
|5 |6 AP |25|15|x5
|6 |7 AP |30|20|x6
|7 |8 AP |35|20|x7
|8 |9 AP |40|25|x8
|9 |10 AP|45|25|x9
|10|11 AP|50|30|x10

## Fog Cloud
__Tier:__ 1; __Element:__ Wood;  
__Casting Time:__ 1 AP; __Casting Cost:__ 3 [HP Reduction];  
__Range:__ 20 ft.; __Duration:__ 3 [Rounds]; __Target:__ 15-ft aura;  
__Description:__ With a hissing sound and a snap of your fingers you call a thick fog bank up from the ground. Adjacent creatures are [Concealed] from one another if either is in the fog, and creatures with 5 feet of fog or more between them are [Fully Concealed]. You have a vague sense of the fog - creatures only ever get [Concealment] against you. The fog can be burned away, and a stout gust of wind disperses it immediately.

You may cast this spell above 1st Tier. Each time you increase the tier, make the following changes:
* Increase the range by 10 feet
* Increase the radius by 5 feet
* Increase the casting cost by 2 [HP Reduction]

If cast in a particularly fitting situation, such as in a graveyard under a new moon or in the heart of a swamp at dusk, your GM may give you one free Tier increase (even if you could not normally cast at that Tier). This increases the range and radius, but not the cost.

## Haste
__Tier:__ 2; __Element:__ Wood;  
__Casting Time:__ 3 AP; __Casting Cost:__ 7 [HP Reduction];  
__Range:__ Eye; __Duration:__ Encounter; __Target:__ 1 creature;  
__Description:__ You lock eyes with the target and magically enhance their metabolism (and give them resistance to friction, et cetera), allowing them to move at increased speeds. Their movement speed increases by 15 feet. When they make 5-foot steps, they may move 5 feet farther. They receive a +1 bonus to AC, SR, and all attack rolls. Lastly, the increased movement speed grants a +4 bonus to Acrobatics checks to jump.

You may cast this spell above 2nd Tier. Each time you increase the tier, make the following changes:
* Increase the number of creatures you can target by 1
* Increase the casting time by 1 AP
* Increase the casting cost by 12 [HP Reduction]

## Portal
__Tier:__ 1; __Element:__ Wood;  
__Casting Time:__ 0 AP, see text; __Casting Cost:__ 3 [HP Reduction];  
__Range:__ 60 feet; __Duration:__ 3 [Rounds]; __Target:__ see text;  
__Description:__ You instantly wrap a bit of warped space around one of your arms where you can easily fire it at nearby surfaces. Firing is a [Fast Action], and may require a spell attack roll to fire precisely. Surfaces must be at least 5 square feet to be targeted. You do not need to keep a free hand for the spell duration, but you must have a free hand to fire.

The two most recent surfaces you have fired upon are linked by portals, allowing one to treat them as adjacent to each other. Firing a third time removes an existing portal of your choice, places a new one, and links the new portal to the remaining portal.

Physics works peculiarly, but predictably.

You can cast this spell above 1st Tier. Each time you increase the tier, make the following changes:
* Increase the duration by 1 [Round]
* Increase the range by 60 feet. At 10th tier, the range is Sight
  * GMs are within their right to arbitrarily limit range at 10th level. Not everyone enjoys suddenly interplanatary high fantasy.
* Increase the casting cost by 5 [HP Reduction]

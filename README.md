# BG3-Eldridtch_Bardadin
a markdown guide for a particularly powerful build in BG3 that I created myself

**__Keywords__:**
  **Classes/Subclasses:** [Paladin](https://bg3.wiki/wiki/Paladin), [Oath of Vengance](https://bg3.wiki/wiki/Oath_of_Vengeance), [Oathbreaker](https://bg3.wiki/wiki/Oathbreaker); [Bard](https://bg3.wiki/wiki/College_of_Swords), [College of Swords](https://bg3.wiki/wiki/College_of_Swords); [Fighter](https://bg3.wiki/wiki/Fighter), [Eldritch Knight](https://bg3.wiki/wiki/Eldritch_Knight)
  **Feats:** [Ability Improvement](https://bg3.wiki/wiki/Feats), [Alert](https://bg3.wiki/wiki/Alert), [Savage Attacker](https://bg3.wiki/wiki/Savage_Attacker)
  **Weapons:** [Bloodthirst](https://bg3.wiki/wiki/Bloodthirst), [Duellist's Perogative](https://bg3.wiki/wiki/Duellist%27s_Prerogative), [Knife of the Undermountain King](https://bg3.wiki/wiki/Knife_of_the_Undermountain_King), [The Dead Shot](https://bg3.wiki/wiki/The_Dead_Shot)
  **Armour:** [Armour of Agility](https://bg3.wiki/wiki/Armour_of_Agility), [Adamantine Splint Armour](https://bg3.wiki/wiki/Adamantine_Splint_Armour), [Helldusk Armour](https://bg3.wiki/wiki/Helldusk_Armour)
  **Gear:** [Sarevok's Horned Helmet](https://bg3.wiki/wiki/Sarevok%27s_Horned_Helmet)
  **Consumables:** [Elixir of Bloodlust](https://bg3.wiki/wiki/Elixir_of_Bloodlust), [Elixir of Cloud Giant Strength](https://bg3.wiki/wiki/Elixir_of_Cloud_Giant_Strength), [Elixir of Visciousness](https://bg3.wiki/wiki/Elixir_of_Viciousness), [Supreme Elixir of Arcane Cultivation](https://bg3.wiki/wiki/Supreme_Elixir_of_Arcane_Cultivation)
  **Abilities:** [Divine Smite](https://bg3.wiki/wiki/Divine_Smite), [Blade Flourish](https://bg3.wiki/wiki/Blade_Flourish), [Song of Rest](https://bg3.wiki/wiki/Song_of_Rest), [Action Surge](https://bg3.wiki/wiki/Action_Surge)
  
## Introduction
Bardadin is a tank and single-target melee build that uses Bard's full spell slot progression for extra daily uses of `Divine Smite`.

A typical Bardadin build involves 2 levels into Paladin to pick up `Divine Smite`, then Fighter for `Action Surge`, then College of Swords Bard for 20 `Flourishes` a day and all the spell slots your `Divine Smite` could ever want. This variation trades out levels 7 and 8 in Bard for two levels in Eldritch Knight, which provides access to `Shield` and `Expeditious Retreat` for extreme survivability and mobility, even maintaining the second feat. Furthermore, this build focuses on critical hit damage out put for `Divine Smite` rather than 2-Handed melee damage, allowing another party member to use `Balduran's Giantslayer`.

## Build Theory
### Divine Smite
Paladin's `Divine Smite` is a class feature which consumes a spell slot to deal extra damage to the target of your melee attack. It has the unique feature to be applied after a melee hit as well as not using a spell slot on a miss from manual activation, so you'll always get damage out of it unlike something like `Sleep` or `Command` which can be resisted. `Divine Smite` can also be upcast, allowing you to deal extra damage with higher level spell slots. `Divine Smite` deal 2d8 Radiant damage at level 1 and 1d8 per level of upcast, as follows:
 - Level 1: 2d8 (2 - 12; mean 9)
 - Level 2: 3d8 (3 - 24; mean 13.5)
 - Level 3: 4d8 (4 - 32; mean 18)
 - Level 4: 5d8 (5 - 40; mean 22.5)
 - Level 5: 5d8 (5 - 40; mean 22.5)
 - Level 6: 5d8 (5 - 40; mean 22.5)
 
Critical Hits double the damage of `Divine Smite` as well as the rest of the attack, so disciplined usage of level 4, 5 and 6 spell slots have a mean of 45 extra radiant damage in a range of 10 to 80 per spell slot--up to 8 times per day (mean of 360 damage). There are of course methods of restoring spell slots or gaining extras, so this can be improved even further.

So all of these things sound pretty good right? What if I told you `Divine Smite` is also broken and you can just apply a ton of ridiculous effects to it to further optimize its damage? You can do that!

#### Savage Attacker (Feat) & Divine Smite
Lastly, `Divine Smite` is affected by `Savage Attacker`, meaning that damage from `Divine Smite` is rolled twice and the higher result taken--effectively `Advantage` but for damage. That feat skews mean damage per `Divine Smite` by 1.86 for 2d8, then 2.28, 2.64, and finally 2.89 for 5d8. The mode and median both also increase by 2 or 3 depending on the exact roll, and the trimming of low rolls shows up as a standard deviation decrease by -0.57 to -0.91 from 2d8 to 5d8. All the quartiles on damage increase by 2 except Q1 for 3d8, 4d8, and 5d8, which all increase by 3. `Savage Attacker` makes the damage from `Divine Smite` higher overall and more reliable per swing. This feat also applies to critical hits, and since that's the focus of this build

#### Savage Attacks (Racial Feature) & Divine Smite
This [half-orc](https://bg3.wiki/wiki/Half-Orc) passive feature adds 1d8 to all `Divine Smite` critical hits. This extra d8 is affected by `Savage Attacker` if you have both.

### Notes on Multiclass Spellcasting in 5e
When a character has two classes that each feature `Spellcasting` (not Warlock, which has `Pact Magic`), their levels opperate independently for `Spells Known` for each class, and collectively for `Spell Slots` which are shared among all a character's classes.
 - For example:
   - A Paladin 2 has two 1st level `Spell Slots`, and learns five 1st level Paladin spells.
   - When taking her next level in Bard (Paladin 2/Bard 1), she gains four 1st level Bard spells, and one 1st level spell slot for having two levels of `Spellcasting`.
   - When taking her next level in Bard (Paladin 2/Bard 2), she gains one 1st level Bard spell, and one 2nd level spell slot for having three levels of `Spellcasting`. If she chooses to swap a spell this level, she only has access to 1st level Bard spells because she is a second level Bard. She can notably upcast `Divine Smite`, `Healing Word`, and `Command`.
This means the more a character multiclasses with spell casting, the broader but shallower their pool of spells is, and the more reliant they are on upcasting.
 - In the `Jack of All Trades` achievement run, a character never gains spells above 1st level, but gains `Spell Slots` up to 3rd level.
 - This advantages spells like `Magic Missile`, which benefit from upcasting significantly.

There are a few different ways `Spellcasting` is distributed for different classes.
 - Bards, Clerics, Druids, Sorcerers, and Wizards have "Full Progression", or they gain spells and `Spell Slots` every level.
 - Paladins and Rangers are considered "Half Progression" because they only advance their `Spellcasting` on even levels.
   - They do gain half a level every level, so when you have a Paladin 1/Ranger 1, they gain `Spellcasting`.
 - Arcane Trickster Rogues and Eldritch Knight Fighters are "Third Progression" because they gain a level of `Spellcasting` every three levels, though they get their first two as levels 3 and 4.

## Build Details
### Background
 - Wood Elf and Half Wood Elf are both great for the extra mobility, but play whatever you like.
 - While this build especially shines in melee, it still has consistent output at range with 4 attacks per round.
 - I picked BACKGROUND for my background, but play whatever works best for you. Just keep in mind it's hard to sneak in heavy armor.

### Attributes
`STR 10 | DEX 16 | CON 9* | INT 10 | WIS 12 | CHA 17`
 - n.b. CON is minimized because I am at end game and have an item that sets it.
 - For earlier game, you may want `10|16|14|8|8|17` (swap STR and WIS as you wish).
 - +1 to CHA from an event
 
### Levels

#### 1 - Paladin 1 (+1)
The initial level should be Paladin for its extra Weapons and Armours. The proficiency bonus to `WIS` and `CHA` mean you stay in control of your character more often than not when fighting casters.
 - Take `Oath of Vengeance`. It's fine if you break your `Oath`; just become an `Oathbreaker`.
 - I picked `Athletics` and `Religion` for my skills. `Athletics` helps in melee with pushing and resisting various maneauvers, but the second one is up to you. Make sure you have at least one conversational skill (`Deception`, `Intimidation`, `Persuasion`).

#### 2 - Paladin 2 (+1)
This is where the magic happens (because you get `Spellcasting`, but also because you also get `Divine Smite`).
 - You gain `Divine Smite`, which is the class feature that outputs the most single-target damage in BG3. It turns your sword into a damage hose.
   - Only use it on Crits or to finish off a target. Do not use it to just add more damage, especially in the early game.
 - Take `Defence` for your `Fighting Style` to add `+1 AC`. You'll get `Dueling` later, and you won't use the other two.
 - You probably will never use any of these spells, but I took:
   - `Command`, `Compelled Duel`, `Bless`, `Healing Touch`, and `Thunderous Smite`
 
#### 3 - Paladin 2 / Bard 1 (+1)

 

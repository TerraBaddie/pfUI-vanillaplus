# pfUI Vanilla Plus

An extension for [pfUI](https://github.com/shagu/pfUI) which adds support for the [Vanilla+ Server](https://vanillaplus.org/).
The latest version of pfUI is required and only enUS-Gameclients are supported at the time.
The modifications are based on the research of [@Heroclastus09](https://github.com/Heroclastus09/) and [@hawaiisa](https://github.com/hawaiisa/) and [@cgoodwin117](https://github.com/cgoodwin117).
Many thanks go to Shagu for enabling this practical module and for his support and advice :)

## Important Note
The non-modular version of pfUI V+ will no longer be supported as this version offers much better integrity and flexibility, please only download this mod extension for Vanilla Plus !

## Installation

1. Download **[Latest Version](https://github.com/shagu/pfUI)** of pfUI and follow install instructions on that site
2. Download pfUI-vanillaplus-master.zip via the green code button on this page 
2. Unpack the Zip file
3. Rename the folder "pfUI-vanillaplus-master" to "pfUI-vanillaplus"
4. Copy "pfUI-vanillaplus" into Wow-Directory\Interface\AddOns
5. Cut the file libtotem.lua out of the pfui-vanillaplus folder and copy it into Wow-Directory/Interface/Addons/pfUI/libs and overwrite
6. Restart Wow

## Features

Vanilla+ is providing a custom client with spells, debuffs and other features that differ from the original game.
This pfUI module updates the pfUI core components to make them aware of those changes. 
In general, those vanilla+ custom changes are:

- Updated debuff durations
- Updated cast durations
- Updated talent based calculations (for debuffs and cast times)
- Updated duration of totems and custom totems

## Changelog (Summary)

**Hunter:**
- Aimed and Multi Shot show the correct cast times and are affected by the Snap Shot and Melee Specialization Talent
- Hunters Mark shows correct debuff time and is correctly affected by Improved Hunters Mark talent
- Concussive and Scatter Shot show correct (new) duration
- Scorpid Sting and improved Scorpid Sting show correct duration
- Wyvern Sting now partially shows the correct duration (10 seconds on both the sleep and wake-up-slow, differentiating the times wasn't possible for me yet)
- corrected Intimidation duration, corrected some pet's abilites durations 

**Rogue:**
- Duration altering talents affecting debuffs should work correctly (Total Control, Improved Gouge, Exhaustion, Serrated Blades)

**Warrior:**
- Hamstring duration corrected, talent interaction with Improved Hamstring added
- Booming Voice should correctly affect debuff times for Shouts

**Warlock:**
- Prolonged Misery and Jinx should correctly increase the associated Curses duration, base Curse duration corrected
- added debuff timer for Shock and Awe Skill

**Priest:**
- Mindflay debuff time corrected
- Shadow Word Pain should display correct in relation to Improved Shadow Word Pain talent
- Shadow Word: Numb debuff duration is shown
- Improved Psychic Scream talent acutally increases shown debuff time

**Paladin:**
- Improved Hammer of Justice should affect Hammers shown debuff time
- added debuff timer for Inner Light

**Druid:**
- Mighty Roots and Power of Nature should affect the associated spells shown debuff timers
- Moonfire base debuff durations corrected

**Mage:**
- Permafrost should correctly increase Frostbolts debuff duration, Frostbolt baseline debuff times corrected

**Shaman:**
- corrected a few totem durations
- Earth Shock debuff time should be displayed and affected by Earth Graps Talent
- added debuff timer for Sand Blast

## Changelog v 0.65
- added new debuff durations
- adjusted seal of fury duration

## Changelog v 0.64
- updated immolation trap and explosive trap dot duration
- correctly scale freezing trap with talents

## Changelog v 0.63
- corrected pally judgment and vindication debuffs
- added thunderstomp debuff
- formatted files(i.e. changed tabs into spaces, alphabetize lists, etc.)

## Changelog v 0.62
- corrected expose armor duration calculation
- added garrote silence duration

## Changelog v 0.61

- changed Shadow Weaving and Winter's Chill Debuff timers to reflect the patch changes

## Changelog v 0.60

- changed durations according to 04.03.21 changelog
--> Flame Shock duration 15 sec, Shock and Awe 3 sec, Improved Hamstring Talent duration bonus per talent pt reduced to 1 second


## Changelog v 0.59

- corrected Warlock's Talent Prolonged Misery Talent affecting the correspronding abilities shown debuff durations
- cleaned up some code due to Total Control not affecting Blind and Sap any longer

## Changelog v 0.58

- corrected Tranquil Air Totem duration (thanks@Molnezar)
- corrected Rake duration

## Changelog v 0.57

- now really corrected all Totem timers, unfortunately they have to be added manually for the time being--> see Install Instructions
- added and corrected debuff timers for Stormstrike and Aftershock (since both debuffs have the same name I took 4 seconds for the Frost stun debuff)

## Changelog v 0.56

- corrected Healing Stream and Mana Spring Totem timers

## Changelog v 0.55

- corrected Hunter talents Intimidation and Wyvern Sting debuff times (Wyvern sting shows 10 seconds on both Wyvern Sting parts)
- corrected Hunter Pet Ability Screech debuff duration


## Changelog v 0.54

- made Psychic Scream correlate with Improved Psychic Scream talent correctly (thx@ Hawaiisa)

## Changelog v 0.53

- Multi and Aimed Shot cast time should be also influenced by Melee Specialization Talent
- Added Shaman Sand Blast and Paladin Inner Light debuff durations
- Moonfire debuff durations corrected
- added debuff timer for Earth shock and included dependancy with Earths Grasp Talent

## Changelog v 0.52

- added a few v+ skill debuff durations, corrected some non-working code

## Changelog v 0.51

- cleaned up the code, got the module version of pfUI Vanilla Plus
- corrected some errors
- added correct totem durations

## Changelog v 0.5

- initial release



[h1] Worthy Conquerors [/h1]
Mod that alters a character's eligibility and percentage chance for the conqueror pulse event. 
The goal of the mod is to make conquerors much more impressive characters skill and trait wise.

[h2] Details [/h2]

[h3] Eligibility [/h3]
To be eligible for the conqueror event a character needs to:

* be a healthy, landed, independent adult of age 50 or less (down from 60)
* have a highest title of duchy or kingdom (see game rules section)
* have an education of 3 star or higher (see game rules section)
* a conqueror's personality (see below)
* not to be involved in any struggle (see game rules section)
* not be at war

[u][b]Conqueror's Personality[/b][/u]
A new personality check has been added that examines hidden values. To pass the following is required:
* 0 or higher value for [i]boldness[/i] and [i]energy[/i]
* 30 or higher value for either [i]boldness[/i], [i]honor[/i], [i]greed[/i] or [i]zeal[/i]
* does not have either [i]craven[/i], [i]content[/i] or [i]lazy[/i] personality traits
* does not follow a religion or culture that favours pacifism

This aim of the check is to allow for a variety of different style conquerors but at the same time filter out nonsensical ones.

See the [url=https://ck3.paradoxwikis.com/Traits#Personality_traits]personality traits[/url] section on the wiki for more information on what hidden values traits give.

[h3] Random Chance Percentage [/h3]
The percentage chance to trigger the conqueror pulse event has been reworked.
Non character specific increases (such as having a clan government) have been removed.
Instead the percentage is now influenced by the following character specific items:
* education, with those martial educated getting a bigger bonus
* martial skill
* prowess skill
* traits across all categories, not just personality. (e.g getting certain lifestyle traits will improve chances)
* prestige level, with higher levels contributing more
* certain rare modifiers, such as tool of fate

[h2] Game Rules [/h2]
Existing game rules related to conquerors still work as normal.
The following new game rules are added by the mod.

[h3] Empire Title Conquerors [/h3]
Determines whether characters who hold empire titles are eligible to be conquerors.

[i]Prevent[/i] - stops them from becoming conquerors (default)
[i]Allow[/i] - allows them to be conquerors

[h3] Struggle Participant Conquerors [/h3]
Determines whether characters who are involved in a struggle are eligible to be conquerors.

[i]Prevent[/i] - stops them from becoming conquerors (default)
[i]Allow[/i] - allows them to be conquerors

[h2] Compatibility [/h2]
This mod overwrites the [b]story_cycle_conqueror_events[/b] file and will not be compatible with any other mod that also changes this file.

[h2] Other Notes [/h2]
* Conquerors who exist on game start do not need to pass the eligibility check
* This mod does not change how inheritance works for the conqueror trait

[h2] Localization [/h2]
Localization for supported locales has been provided by using [url=https://github.com/CyberNord/CK3_LocalizationChanger]CK3_LocalizationChanger[/url].

[h2] Bug/Issues [/h2]
Due to the random nature of this event it is difficult to verify that the check correctly includes/excludes personality combinations.
If you think a character who received the conqueror trait should not have please let me know and I will investigate.
Please be aware of the inheritance notes above before doing so.



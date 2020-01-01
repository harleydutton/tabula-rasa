# Tabula-Rasa
## About
This README is not intended to be part of Tabula Rasa. Instead it is a meta-document for tracking design, philosophy, formatting, and tasks. Created by Harley Dutton.

## Philosophy
- players can create their own skills within the bounds of the setting
- plays quickly (10 mins a round and 1 hr tops for CC)
- generic with plug and play settings
- low entry barrier (4d6, counters, paper, and pens)
- roleplaying system first and a combat system second
- should be short (10 pages max) and only one file for ease of reading and sharing
- don't be preachy by telling people how they _should_ be roleplaying or storytelling
- don't let realism or balance get in the way of fun
- shouldn't include anything setting specific
- avoid complicated math and bookkeeping hell



## Design Options
<!--Use feature branches and a little merging to turn these on and off for various releases.-->
### Non-numeric combat
Characters will not have health, items will not have numeric values associated with them, and damage will be dealt in the form of wounds. Wounds are detrimental flavor based on the weapon and armor involved.
<!--The alternative would be to make a bunch of tables for and formulas for stuff-->
### No leveling up
<!-- Characters will start with a number of character points determined by the storyteller. -->
Characters will not level up but skills will. Characters will not have levels or experience. Instead _skills_ will level up when the character passes a number of checks with the skill equal to the skill's level. Track a each skill's experience with tally marks next to the skill. To combat experience whoring, a character can train for 8 hours in game to make one check with the skill.
### Gambits
At its most basic a gambit is a deal you make with the storyteller. Anyone can propose a gambit but all parties must agree before the dice are rolled for the gambit to take effect.
<!--Two common gambits would be to go for a called shot in combat or to take your time with an action out of combat. Raise the difficulty for the called shot and make it insta-kill. Lower the difficulty for the careful action and lower the quality of a success.-->
### no attributes
<!--This assumes that there will also be a list of common skills included with each setting-->
Rather than having a few attributes we could have a list of __mandatory skills__ for a setting. Every character would have to take some level in __all__ of these skills.



## Formatting 
- include definition for terms
- include examples for things
- sections should contain links to other sections they reference
- only one chart or table per page
- no page elements that cannot survive being printed (other than links)
- monospace for formulas and definitions
- block quotes for examples
- follows the DRY design philosophy by using links
- no misspellings and grammatically correct
- heading one will be reserved for the title at the very top
- headings two through four will be available for (sub)sections

- include a LEGEND of formatting choices?
- if the same keyword appears twice on a page should both include a link to the relevant page?
- should I capitalize common keywords like proper nouns? should i capitalize the keywords I make like proper nouns? I think just including links should be sufficient and none of this stuff should be capitalized... but I'm not sure.

## Outline
- INTRO
- TABLE OF CONTENTS
- GETTING STARTED
	- players go to CC
	- storyteller needs to have/make a setting
	- storyteller needs to have/make an adventure
- CHARACTER CREATION
	- how to use the setting
	- skills
	- flavor
	- group CC process (i think this might be getting into preachy territory)
	- other (action delay)
	- printable character sheet
<!--
	top: name, concept, setting, player, action delay
	skills column: level, name, exp, desc.
	flavor column: physique, knowledge, possessions, social, supernatural, wounds
-->
- CHECKS (how to play the game)
	- description of process
	- modifiers
	- skills
	- contested rolls
	- good/bad stuff die
	- skill progression
	- opposed checks
- SKILLS
	- definition
	- mandatory
	- common
	- player made
		- limiting factors
	- progression
- FLAVOR
	- definition
	- items
	- wounds
- ITEMS
	- definition
	- crafting
	- black market
	- value (in money)
- STEALTH
	- hidden
	- alerted
	- detected/caught
	- surprised
- LYING
	- suspicious
	- detected
	- fooled
- PERSUASION
	- willpower
- COMBAT
	- description of process (starting combat ie. rolling initiative)
		- surprise round for hidden characters acting in tandem and link to stealth section
	- action delay and actions
		- description of process (one turn)
		- reaction, mental, passive, major, minor, full, movement, free, bonus, continuous, teamwork, and prepared/held actions.
	- attacking
		- to hit
		- wounds as damage
	- off-turn actions
		- roll a check and spend reaction and possibly move actions
		- counter attacking
		- dodging
		- blocking
		- intervening
	- movement and distance
		- zones and AUDs
		- overlay a large grid on a bird's-eye-view image to get zones
		- changing zones costs a movement action
- SETTING
	- description and anatomy (of settings in general)
	- description (this is a part of every setting and should describe the setting instance)
		- magic and or technology
		- shop w/ prices and black market (this will involve baseline currency and AUCs)
		- peoples, culture, government, cities, government, history, etc.
		- biomes, flora, fauna, and resources
	- mechanical shit
		- typical action delay
		- starting character points
		- mandatory skills
		- common skills
		- starting equipment options
			- AUCs
			- clothes
			- possessions
			- tools
			- weapons and armor
			- followers
			- make up a skill
- STORYTELLER SECTION
	- making a setting
		- baseline currency in AUCs and stores in percentage of AUCs
		- modify an existing list of common and mandatory skills
		- make a starting CP/standard array recommendation based on number of mandatory skills
	- npcs
		- planned
		- unplanned
		- leveling
		- grouping them for combat
		- wars
	- making an adventure or story
		- story arc template tree thing
- GLOSSARY (page numbers and or brief descriptions)
	- storyteller
	- character
	- player
	- NPC
	- roleplaying
	- worldbuilding
	- setting
	- battlegrid





## To-Do
- [ ] make a graph of topics with categories, subcategories, and relates-to edges
- [ ] record the good ideas from old versions and remove the rest of them
- [ ] decide how I will be formatting the elements of this document
- [ ] implement branch protection and then give Ethan access
- [ ] export the document as a PDF (with pandoc for sublime or an Atom plugin)  
- [ ] learn how to make a tree in markdown
- [ ] learn how to make tables in markdown
- [x] find out if there is a way to put (html stlyed) comments into a markdown doc
- [x] convert all the files in the github project to markdown files or txt
- [x] find a grammar checker (in sublime preferences > settings > "spell_check":true)
- [x] provide one example of each useful piece of markdown here instead and delete example.md  
- [x] learn markdown formatting
- [x] host on a website (github)
- [x] version project with github





## formatting options
<!--html style comment-->
_italics_  
__bold__  
___both___  
~~strikethrough~~  
`monospace blocks`  
> block quotes
>> are nestable  

horizontal bar below
***

1. ordered
2. list   

- unordered
- list   

links to [About](#about) and [To-Do](#to-do) sections. The anchors these sym-links are using were made automatically by the heading markdown elements.

- [ ] check-box
- [x] checked box   

# Heading one
## Heading two
### Heading three
#### Heading four

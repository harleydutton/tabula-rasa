A character is a person in the story rather than one of the ones playing in it or telling it.

## Specification
def:
- info
	- name {string}
	- player {string}
	- setting {string}
	- spent CP {int}
	- hooks {int}
- attributes (mechanical)
	- default action delay - speed = action delay {final int - int = int}
	- wealth, currency and items {int + int / int} {list {string, int}}
	- body
		- wounds {list{string}}
	- mind
		- mental illnesses {list{string}}
	- spirit
		- sins {list{string}}
	- social [[problems]] this should really be communication...
		- scandals {list{string}}
- flavor (small mechanical influence)
	- motivations
	- species
	- adjectives
	- hooks and boons [[problems]] how do i represent these?
- skills (mechanical)
	- {list{string, int}}
- description (on optional second page)
	- concept {string}
	- visual {string+/img}
	- personality {string}
	- history {string}

# Character

[[meta/comments/Character comments]]
This chapter is for you, the Player. Characters are representations of the fictional people within the Setting. To be mechanically playable, your character needs an action delay, a motivation, skills, flavor and a number of other shit.

## Identification Information

This info is of little relevance to a character and of great relevance to the actual human people playing them. This stuff is useful to put on your sheet to keep things from getting lost or disorganized but you are welcome to skip it.

-   Name: The character's name
-   Concept: The characters role in the story
-   Player: The player's name
-   Setting: The name of the character's setting
-   Story: The name of the story the character was in

## Action Delay

This is how fast a character is. Making it lower makes the character faster. Action delay can be reduced by spending character points. See [combat](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#combat) for an explanation of how action delay works.


## Character Points

Character points are used to make a character stronger. They can be used to get new skills and flavor, level up skills, decrease action delay, and acquire minor purchases.

Character points are used to make a character stronger. They can be used to get new skills and flavor, level up skills, decrease action delay, and acquire minor purchases. The players will start with a number of character points (CP) as determined by the storyteller and noted on the [setting](https://docs.google.com/document/d/1IdpkyR5XzUpkYwrZ0e7dhVONLq8gUa03OIkV1lhy-ME/edit#heading=h.j7bs83i9z31d) document. Additionally, the storyteller will likely give the players additional CP throughout the story to represent character growth.

## Motivations

Characters must have at least one motivation. Motivations can be Ideals, Values, Causes, or anything else that gets the character out of bed in the morning.

> Alice is motivated by escaping wonderland and finding her way home. Harry is motivated to defeat the dark lord to protect his friends.

## Skills

Each character has a list of skills representing the actions they can take in the story. Skills do have to be things that a character can _do_ which also means they have to be able to fail as well. Characters may take levels in any skills listed on the setting document unless it wouldn't make sense for them to do so. Skills can be rare or common like `surgery` and `driving` are in modern times or more outlandish like `necromancy`.

Each character has a list of skills representing the actions they can take in the story. Skills do have to be things that a character can _do_ [[which also means they have to be able to fail as well]]. Skills can be either mandatory or available. All characters must have at least one level in all mandatory skills. Otherwise characters may take levels in available skills unless it doesn't make sense.

Each character has a list of skills representing the actions they can take in the story. Skills do have to be things that a character can _do_ which also means they have to be able to fail as well. Skills can be either mandatory or available. All characters must have at least one level in all mandatory skills. Otherwise characters may take levels in available skills unless it doesn't make sense.

Each character has a list of skills representing the actions they can take in the story. Skills do have to be things that a character can _do_ which also means they have to be able to fail as well. Characters may take levels in any skills listed on the setting document unless it wouldn't make sense for them to do so. Skills can be rare or common like surgery and driving are in modern times or more outlandish like necromancy.

### **Mandatory Skills**

Mandatory Skills are those that every character receives from the given Setting. This is meant to represent the Skills that every character should naturally have access to like seeing, strength, and persuasion. There are some characters who will have Flavor that renders these skills useless or remove them entirely. The flavors blind and paralyzed come to mind.

### **Available Skills**

Available skills are those that are present in the setting but not everyone has. They can be rare or common like surgery and driving are in modern times. The point is that not _every_ character has them but most characters are able to learn these skills. A few more modern-day examples are cooking, driving, computer programming, basketball, and surgery.
## Attributes

Attributes are very similar to skills with a few exceptions. Like skills, attributes can be used to roll checks but unlike skills attributes are as broad in [scope](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#scope) as they can be. Like skills, attributes can be leveled up using CP but they are far more expensive. Unlike skills, attributes act as a character's physical, mental, spiritual, and social health. Furthermore, attributes are often used defensively when no other skill would apply. Lastly, attributes can and often are used for perception checks.

## Flavor

Flavor is a mechanic in Tabula used to describe the interesting parts of a character. Almost anything unique that a character _is_ or _has_ is likely to be flavor. Flavor is used primarily for DTMS (does this make sense) checks and modifying the difficulty on checks. Flavor cannot refer to any part of the system, including AD, skills, or attributes. A few examples of flavor might be `armor`, `horse`, `landed noble`, `flaming sword`, `elf`, `big and tall`, etc. for an elvish knight of the summer court. Each piece of flavor should be a short, evocative description.

### Flavor Acquisition

Flavor can be gotten in three ways. First, it can be asked for an paid for with CP at character creation. It typically costs 1 CP per word for flavor at character creation unless modified by a deal. Second, it can be earned and paid for during the story similarly to at character creation. The only difference is that the storyteller may make you spend time in character to earn the flavor you want. Thirdly, flavor might be given to or inflicted upon a character as a result of the story. Lands and title may be given to a peasant after he rescues the princess but he may have also taken some fire damage from the dragon guarding her and have a half-melted face now.


### Bad Flavor

Negative Flavor is usually acquired in two ways. The first way is usually through deals. Rather than asking for a piece of flavor that does something good and something bad a player might ask for a piece of flavor that is mostly bad and ask that it not cost them CP. If the storyteller agrees that this is bad flavor then you can take it for free. The second way characters usually get negative flavor is from combat. When one character lops off another character's hand with a sword that new `-1 hand` will need to be remembered unless that character ceases to matter. Flavor can handle arbitrary negative effects like wounds perfectly.

### Deals

At character creation you may have noticed that there is no way to modify action delay. There is also no way to get any special racial abilities. There is also no way to become rich and famous. Etc. The point is you have to talk to the storyteller when you are creating your character, ask for the things you want, and represent them as flavor. Sometimes the things you want are OP as shit and the DM will want to keep your character in line by raising the cost above the normal for what you are asking for. Want to be super fast? Have -2 action delay by being a vampire (instead death by sunlight). Want to be big enough you can throw cars? Become an Ent for +3 action delay and a vulnerability to fire. Perhaps you can be a world famous boxer if you also have some gambling debts. The point is, talk to your DM and work it out. Sometimes it is appropriate to add a deal to the setting such that it is available to all players and NPCs.

### Items--comment: handled in money and items; remove--[[item flavor comment]]

Unlike most other roleplaying games which have extensive tables for equipment, in Tabula I have opted to represent equipment as flavor. This means that armor, weapons, tools, vehicles, and treasure should be represented as flavor. Typically equipment will modify the difficulty of checks with relevant skills sometimes reducing the difficulty from `impossible` and effectively granting a character new abilities.

### Money--comment: handled in money and items; remove

Money is represented as flavor in Tabula. Character points can be converted into minor purchases. Money-flavor represents a character's liquid assets or the stuff they have for trade. Money-flavor can be aliased to whatever the currency for you game is: `gold coins`, `spacebucks`, `dollars`, `bullets`, `litres (of water)`, etc. If you want to know more go visit the [Money](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#money-1) section. Typically money can be spent on things on the settings store as long as you find a store selling that thing in-game.

### Social Flavor

The in-game doors that position and status unlock are also represented by flavor. Typically this might look like `respected businessman`, `landed noble`, `kings advisor`, or `internet personality`. The effect of this stuff is purely RP and it will be up to the player to use it to its fullest. A character's job is always worth having as flavor because this has social implications in most societies. A character may or may not have a reputation but if they do it is worth putting down what it is and what group of people will know about it.

### Supernatural Flavor

Supernatural flavor is how one might represent being a priest to a specific god. Seriously just put down `priest of Khorn` to be that. Similarly if a character is `haunted`, `blessed`, or in a `demonic pact` just put those things down. That covers the social aspect of supernatural flavor. On the other hand a character could be `magically adept`, `unnaturally sweaty`, or `the chosen one`.

### Relationships

If you have another character as a companion you should list them as flavor or make a character sheet for them. Any animal companions, demonic familiars, slaves, shipboard AI, or loyal friends should be either listed as flavor or have their own character sheet made or both. Whatever is most apt. Consult the deals section and the storyteller.

### Knowledge [[Knowledge comment]]

Knowledge should be represented as flavor unless that [[knowledge would be better represented as a skill]]. You cannot have a flavor and skill that are functionally identical such that the flavor just lowers the difficulty on all of that skills checks. Languages, secrets, history, specific domains of skilled labor, culture, religious rites, etc. are all examples of in character knowledge that should be represented as flavor.

### Vehicles and Properties

Horses, boats, spaceships, cars, planes, tanks, etc. Houses, castles, countries, skyscrapers, private islands, secret bases, etc.

### Physical

Physicality is also represented as flavor. This includes but is not limited to body type, species, race, deformities, aesthetic, and disabilities. An example of each, in order, would be `fat`, `human`, `white`, `missing an ear`, `well dressed`, and `peg-leg`.
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

This looks like another spec:
from a design list of what should go on a character sheet:
    top: name consept, setting, player action delay
    left col: level, name, exp, desc
    right col: flavor type: physique, knowledge, possessions, social, supernatural, wounds
    flavor/skill type as dividers

unique item from yet another spec:
- number of hooks
Tracking # of hooks is an interesting idea.

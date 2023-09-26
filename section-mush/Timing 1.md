This section describes any extended competitive activity within a story where the order of events is relevant. Sword and gun fights certainly fit the mould, sure, but so do a number of other things like horse races, ritual summoning gone wrong, and trying to command a fleet with light-minutes of delay. The order and speed with which characters are allowed to act in this game is based on actions and cooldowns.

### **Tick Length**

In Tabula, timed scenes use ticks, an abstract and arbitrary unit of time to measure how long the scene has lasted and when any individual character can act. The storyteller determines the length of a tick for any given scene. Typically ticks are about a second long but for large scale scenes ticks might be days or even weeks.

### **Action Delay**

Each character has an AD (action delay) stat that governs how quickly they can act in timed scenes. Characters' actions refresh based on their AD. When a number of ticks have passed equal to a character's AD stat that character's [major action](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#major-action), [minor action](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#minor-action), and [reaction](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#reaction) come off of cooldown. The default AD for a setting will be defined on the setting document and represent the typical speed expected for the setting. A higher AD represents a character acting slower than normal and inversely a lower AD represents a character acting faster.

If a character with an AD of 7 acted on 11 that character's actions will refresh on ticks 18, 25, 32, 39, etc. until the scene ends.

### **Global Ticker**

Every timed scene starts with 0 ticks having passed. As a timed scene progresses the storyteller should announce the current tick by counting aloud, one by one. As the global ticker counts up, it is the responsibility of whoever controls a given character to know when that character acts next and call out that it is their turn.

### **Initiative**

To get started with a timed scene each character will need to have a first turn. Each player rolls 1d6 for their character and the storyteller rolls 1d6 for each NPC. This is the turn each character starts on. If a character is joining the scene late, their first turn is 1d6 after the current tick. See the surprise for special cases.

Tim is starting a pie eating contest with two of his friends. When he rolls 3 on 1d6 his first turn is on tick 3. Lets say the tick is 32 and one of the spectators, Joey, has decided he wants to participate. Joey rolls a 5 on 1d6 which means that Joey's first turn will be on tick 37.

### **Surprise**

When one character sneaks up on another using the [hidden information](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#hidden-information) section, and starts something they do not get any benefit. Instead, characters that are surprised are disadvantaged. By default, when a character joins a timed scene they start with all of their actions off cooldown. When a [suspicious](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#suspicious) character joins a timed scene they start with their major action on cooldown. If a character is [oblivious](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#unsuspicious) they start with their major action on cooldown and their cooldowns do not refresh on their first turn.

|   |   |   |
|---|---|---|
|**state**|**first turn on tick**|**actions on cooldown**|
|default|current tick + 1d6|none|
|suspicious|current tick + 1d6|major|
|oblivious|current tick + AD + 1d6|major|

### **Ties**

When two or more characters would act on the same tick, PCs go before NPCs. If two or more PCs act on the same tick the PC with lower AD acts first. If there is still a tie, break the tie randomly. The storyteller can use this method to break ties for NPCs but doesn't have to.
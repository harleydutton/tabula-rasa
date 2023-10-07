To get started with a timed scene each character will need to have a first turn. Each player rolls 1d6 for their character and the storyteller rolls 1d6 for each NPC. This is the turn each character starts on. If a character is joining the scene late, their first turn is 1d6 after the current tick. See the surprise section for special cases.

Tim is starting a pie eating contest with two of his friends. When he rolls 3 on 1d6 his first turn is on tick 3.

Lets say the tick is 32 and one of the spectators, Joey, has decided he wants to participate. Joey rolls a 5 on 1d6 which means that Joey's first turn will be on tick 37.

> Tim is starting a pie eating contest with two of his friends. When he rolls 3 on 1d6 his first turn is on tick 3.
> Lets say the tick is 32 and one of the spectators, Joey, has decided he wants to participate. Joey rolls a 5 on 1d6 which means that Joey's first turn will be on tick 37. 

---

When one character sneaks up on another using the [hidden information](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#hidden-information) section, and starts something they do not get any benefit. Instead, characters that are surprised are disadvantaged. By default, when a character joins a timed scene they start with all of their actions off cooldown. When a [suspicious](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#suspicious) character joins a timed scene they start with their major action on cooldown. If a character is [oblivious](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#unsuspicious) they start with their major action on cooldown and their cooldowns do not refresh on their first turn.

|   |   |   |
|---|---|---|
|**state**|**first turn on tick**|**actions on cooldown**|
|default|current tick + 1d6|none|
|suspicious|current tick + 1d6|major|
|oblivious|current tick + [[Action Delay\|AD]] + 1d6|major|

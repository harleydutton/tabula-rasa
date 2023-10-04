When one character sneaks up on another using the [hidden information](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#hidden-information) section, and starts something they do not get any benefit. Instead, characters that are surprised are disadvantaged. By default, when a character joins a timed scene they start with all of their actions off cooldown. When a [suspicious](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#suspicious) character joins a timed scene they start with their major action on cooldown. If a character is [oblivious](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#unsuspicious) they start with their major action on cooldown and their cooldowns do not refresh on their first turn.

|   |   |   |
|---|---|---|
|**state**|**first turn on tick**|**actions on cooldown**|
|default|current tick + 1d6|none|
|suspicious|current tick + 1d6|major|
|oblivious|current tick + [[Action Delay\|AD]] + 1d6|major|

This is a stat derived from the [[Setting]] base action delay and a character's [[Speed]]. base AD - speed = character AD

If a character has a speed of 3, the settings base action delay is 10, then they get to act in combat every 7 ticks.

---

Each character has an AD (action delay) stat that governs how quickly they can act in timed scenes. Characters' actions refresh based on their AD. When a number of ticks have passed equal to a character's AD stat that character's [major action](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#major-action), [minor action](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#minor-action), and [reaction](https://github.com/harleydutton/Tabula-Rasa/blob/develop/tabula-rasa.md#reaction) come off of cooldown. The default AD for a setting will be defined on the setting document and represent the typical speed expected for the setting. A higher AD represents a character acting slower than normal and inversely a lower AD represents a character acting faster.

If a character with an AD of 7 acted on 11 that character's actions will refresh on ticks 18, 25, 32, 39, etc. until the scene ends.
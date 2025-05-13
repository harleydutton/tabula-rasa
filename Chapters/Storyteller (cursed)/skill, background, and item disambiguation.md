heuristic: describe, in as few words as possible, how the new content would hypothetically affect the character and pay attention to the verb.

- "The character is..." = [[Background|Backgrounds]] (and [[Damage]])
- "The character owns..." = [[Items]]
- "The character can..." = [[Skills]]

---
## Working out the flowchart

```
Examples: Beautiful singing voice. Blademaster. Facial scar. Wise. Strong. Charming. Holy. Knowledgeable. Cybernetic implants. Friends in high places. Night vision. Extra limbs. Can talk to plants. Thinks he can talk to plants.   Plant whisperer. Plants talk to me. Magically adept. Knows Spanish. Knows the location of buried treasure. Has Dogs. Has Fleas. Has land and title. Has a gambling problem. Knows computer science. programmer. hacker. skilled hacker. famed hacker. Knows how to build a house. Surgeon. Good at <skill>. Good <job title>. Famed <job title>.
```

- Looks like I need a column for "has" and some filtering rules
- Looks like I need to do something with "knows"
- Good at `<attribute>/<job>/<skill>` seems like a problem

these problems are all solved by forcing the peg into one of the "can/is/owns" holes and adding downsides
## Heuristic: "The character ..."

| can == skill    | is (a/an/the) == background | owns (a/an/the) == item |
| --------------- | --------------------------- | ----------------------- |
| play the flute  | elf                         | plate armor             |
| talk to plants  | landed noble                | flaming sword           |
| shoot fireballs | tall                        | many decks of cards     |
|                 | large                       | horse                   |
|                 | handsome                    | spaceship               |
|                 | horned                      | night vision goggles    |
|                 | fat                         | library                 |
|                 | guard captain               | many rare books         |
|                 | sneaky                      | compass                 |
|                 | boring                      | castle                  |
|                 | scarred                     |                         |
|                 | liar                        |                         |
|                 | sociopath                   |                         |
|                 | liked by horses             |                         |
|                 | centaur                     |                         |
|                 | gambling addict             |                         |
|                 | known priest beater         |                         |
|                 | kind                        |                         |
|                 | kings advisor               |                         |
|                 | drug dealer                 |                         |
|                 | librarian                   |                         |
|                 | insane                      |                         |
|                 | insomniac                   |                         |
|                 | obligate carnivore          |                         |
|                 | leper                       |                         |
|                 | amputee                     |                         |
|                 | crippled                    |                         |
|                 | incorporeal                 |                         |
|                 | haunted by past             |                         |
|                 | haunted by ghosts           |                         |
|                 | stubborn                    |                         |
|                 | bloodthirsty                |                         |
|                 | polite                      |                         |
|                 | med school dropout          |                         |
|                 | cult leader                 |                         |
|                 | famed space pirate          |                         |
|                 | boxing world champion       |                         |
|                 | infertile                   |                         |
|                 | shift manager at maccas     |                         |
|                 | young and stupid            |                         |
|                 | evil                        |                         |
|                 | charitable                  |                         |
|                 | yale student                |                         |
|                 | vampire                     |                         |
|                 | muscular                    |                         |
|                 | attractive                  |                         |
|                 | fast                        |                         |
|                 | rich                        |                         |
|                 | Spanish                     |                         |
|                 | religious                   |                         |
|                 | prince's ward               |                         |

---

~~double check to make sure skills are fallible and backgrounds are not. skills are guaranteed to be fallible.~~ backgrounds that are fallible can be handled with attributes.

---

some things can be a skill or background depending on certainty. "flying" for instance is probably a background ("levitates" or "winged") unless it seems likely that other characters will frequently try to fly faster at which point it might be better as a skill. If it infrequent, an attribute could be used for those contests. really it doesn't matter though because it should be handled either way.

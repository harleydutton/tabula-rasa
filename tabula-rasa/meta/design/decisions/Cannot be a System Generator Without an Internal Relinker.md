I have through through the system generator idea some more. In order to effectively implement feature flags I would need the H&R block style "what kind of game do you want to play" form that would automatically fix all the internal links or it would be confusing as hell for the players because I would have to do something like this to disambiguate:

> Distance Disambiguation 
> - Distance as Theater of Mind 
> - Distance as Zones 
> - Distance as Squares  
> - Distance as Concrete Numbers

And then any time the doc links to distance it links there, the player checks the setting doc to see which system they are using, and goes to the correct page. This sounds like it would be in direct violation of my [[Avoid look-ups]] design decision.

---

I suppose I could just choose default systems. No disambiguation pages, just default to one of the systems, and make the others link-able so they could be referenced with the feature flags part of the setting document. This still runs into the problem where the player might need to do multiple lookups in order to get the info they need. I think this is where I realize that the title of this note is correct. Tabula cannot be a system generator without some programming to redo the internal links when swapping out systems. The reason I would include the alternative systems is to make it possible/easy to do that programming after I complete it. It may be functionally impossible to do without having planned for it from the beginning though.

When I say programming, all I would really need it an options page, some radio buttons, some way to persist variables, and some way to modify links based on those variables.

I haven't seen any good options: The templating plugin, frontmatter, and dataview seem to be the most relevant but there is still no way to persist/inject the variables.

This https://forum.obsidian.md/t/updating-and-referring-to-global-variables/41831 would probably allow this to work as a system generator for me at "compile time" but wouldn't be modifiable at "runtime".
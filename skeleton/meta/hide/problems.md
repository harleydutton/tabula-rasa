## graph
The usefulness of the graph view is being limited because all the links to/from problems/todo are clutering it up.
I wonder if there is a way to ask obsidian to ignore certian files?
I could also just delete the files or minimize the links.
## presentation
Making readable rules out of a bunch of individual documents is a pain. I need to figure out how to present the user with my doc as there isn't a good entrypoint or single document right now.
### Ideally...
I would like to prototype within obsidian using obsidian's embeds.
I would like to version on github.
It would be pleasant to be able to present on github through the readme with fake embeds, assuming all of the links still worked. I would need to find a way to present a ToC/glossary and I would probably lose the graph view.
### solutions
#### As one document
embedding everything in one file is an option that might work. Entrypoint is one candidate. I should probably look into a free software that would publish obsidian correctly including the embed links. I could also just pay for obsidian publish. I think this approach isn't as DRY.
##### script(multiple docs) -> README.md
I could use a bash shell script to put the obsidian files together into one document and then present it using githubs README.md. I would need to relearn the linking syntax for github's markdown. IIRC it's pretty simple.
It would need to handle links and maybe embeds, though I'm not using the embeds.
The linking syntax is simple enough and I could likely customize the syntax to suit my purpose better. `(!)[[<File>^<Heading>|<text>]]` though I may need to guarantee my headings are unique.
##### creative use of headings and embeds
I could add a H1 to each doc with the same name as the file and use this as the embed poing `![[Player#h1]]` to display everything correctly. The problems remaining would be that the links would go to the sub-docs rather than scrolling the main doc, the ToC wouldn't populate, and I would still be reliant on obsidian to present the doc.
#### As multiple documents
I think I could potentially present this as multiples documents with a single entry point. This would just use the natural links in obisdian. One page would need to be the main entrypoint to the doc with a getting started/Toc/glossary page.
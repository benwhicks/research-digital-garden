---
{"dg-publish":true,"permalink":"/readme/"}
---


This collection of work is for my PhD research around modelling systems.

[[- - home - -\|- - home - -]] is the content map for the overall PhD research.

[[- working-notebook -\|- working-notebook -]] contains todo lists and is a dump for future reading

# Note taking conventions

## Boundaries

When a concept is not deemed within scope of this vault then it is ==highlighted== as a reminder that this was considered as an atomic note but rejected as out of scope. For instance there are pages on `causal claims` that mention that this is a kind of ==claim==, which indicates that this vault will not get into the details of what claims, more broadly, are. 

## Naming
* Notes will typically be **lower-case-and-seperated-by-hyphens** . Important structure notes (like this one) have some `- - hyphens at the beginning and end - -` to help them stand out. 
* Notes that are a source that can be cited use their better bibtex key from Zotero, so are all in `@hicksThinkingCausalModels2022` style.
* Memo notes, such as notes recording an event (such as a meeting, or notes attending a talk, etc.) will start with a 6 digit date stamp in the form `yymmdd-`. 
* Notes about learning things will be prefixed with `learn--`.
* Notes about writing start with `writing--`

## Tags

### Action tags
- `#todo` : things to come back to
- `#todo/important` : important things
- `#read` : to come back and read / watch. Handy to paste a link to the Zotero pdf (requires the Zutilo plugin in Zotero)
- `#learn` : for new things I’d like to learn / understand.
- `#doubtful` : for thoughts that I should come back to and probably remove. Spring cleaning targets. 

### Note type tags
- `#memo` for notes that are records of meetings or workshop sessions or similar. 
- `#people` for notes that represent a person or group. This will also then subset into where they belong. So someone at CIC will have the tag `#people/UTS/CIC`
- `#group` for notes about a group, such as CIC. They follow the same folder nesting as the `#people` tags.
- `#resource/tool` note on a tool that might be useful
- `#📖` : bibliographical note or resource.
- `#author`: Is for work I have contributed to, and `#author/first` if I am the first author.
- `#writing` : more formal ideas to be formed into a cohesive piece of text. Might be subsetted like `#writing/blog` if useful. 
- Notes that are potential use cases for running a participatory modelling session and will also be tagged with `#case-study`
The note type tags should only have one type per note.

### Thematic / categorical tags
- `#graphical-modelling` : Related to causal modelling of a system using graphical structures.
- `#mathematical-modelling` : Related to causal modelling of a system using mathematical structure. Has subgroups, such as:
	- `/game-theory`
	- `/agent-based`
	- `/dynamic` or maybe DE?
- `#participatory-modelling` : Related to areas where this modelling can be done collaboratively. 
- `#theory` : Relating to systems thinking, thinking about learning, or complexity, or causation. This is a fuzzy boundary (everything is influenced by theory) but is meant to tag the more esoteric notes. Has subgroups:
	- `/causation`: What are causes anyway?
	- `/systems`: This includes complexity and the categorisation of kinds of systems.
	- `/learning`: For learning theories or more esoteric education notes. 
These themes can overlap. They should also be used for the atomic ideas only - not for collections of ideas such as writing or memo notes. 

## Note properties

Front matter is used for additional structuring notes. Yaml options are:
- type: These will only be specified for non-thinking, non-writing style notes. 
	- source : for `#📖`  notes, or other reference material that describes other people’s knowledge
	- memo : Notes on a meeting, or event, etc.
- summary : A high level summary of the note
- date : When the note was created, or relevant to. Primarily used for `memo` notes
- progress : for `learn` notes, and other task style notes. Begins at `not started` and is essentially free text to describe where it is up to. 

# Work flows

## From reading to writing

1. Read in Zotero, highlighting key phrases that will be useful to be brought into Obsidian. 
2. Import into Obsidian using the command palette (Cmd-P) and selecting "Zotero: Import Paper". This will place the note in "Sources/@{{citekey}}.md", copying all highlighted text, and utilises the [[Templates/zotero-import-paper\|zotero-import-paper]] template. 
3. Write up the key ideas in the paper that might be useful, as though they could be paragraphs in a paper. Organise any imported quotes underneath these key ideas. As these key ideas are written, ensure they link to any other notes. For instance if you end up writing about "causal claims" then use `[[causal-claims]]` to link to the relevant note. 
4. Support key ideas with new evidence. Consider what notes have been linked to this paper in step 3, can they be updated to include any new evidence or ideas from this paper? If there are good quotes to use put them in a block quote, quote type, with the link to the Obsidan paper note as the heading, for example: `> [!quote] [[@kittoPlacesInterveneComplex2024]]`
5. Support current writing projects with new evidence. As above but working with anything that has the `#writing` tag. 

Note that the Citations plugin only works when the file `PhD.bib` (in the Sources folder) is updated. This is done by exporting the entire library from Zotero as a Bibtex file and saving. 

## Worthy events

1. Create a memo note using [[Templates/template-memo\|template-memo]] on the day that things happened, even if it is untouched. 

# Resources

Pages on a tool will be tagged with a `#resource/tool` tag. There are others used as well. 

## Zotero plugins

- Betterbibtex for making the source notes nice
- Zotillo, for being able to copy link to pdf within local library. #todo install this and check it works. 

## Obsidian plugins

- Templates
- Zotero integration / import 

# Graph view

Current graph settings (would like to move "Sources" and "People" and "Memos" and "Writing" (maybe??) up so they are categorised first - colour the atomic ideas only):
![Pasted image 20250328134421.png](/img/user/Images/Pasted%20image%2020250328134421.png)





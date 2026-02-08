---
{"dg-publish":true,"permalink":"/requirements-for-a-causal-modelling-support-tool/"}
---

#thought 
#participatory-modelling

> [!important] Outline
> A list or table of the kind of requirements for making certain edits / prompts in a graphical causal modelling session. For the less technical knowledge ones this could be built into a card-based prompt system. For the more technical requirements a more complex tool, such as software, would be required. The idea is that a designer could use this requirements to build a software tool to support the more technical decisions. 

[[graphical-causal-model\|GCM]], [[participatory-causal-modelling\|participatory-causal-modelling]]

Could also be part of [[technical-democracy\|technical-democracy]] work by [[People/Kalvero Gulson\|Kalvero Gulson]], particularly around their methodology ( #getref - nice website that was part of the pre reading with the GenAI workshop)

## Tangible, trackable operations

It would be nice to visibly:
- Merge nodes, by dragging one into another, and track this behaviour
- Split a node by pulling it apart, they would need renaming and have a dotted link between with a `?` 
- Basically track all the naming decisions in the process, and graph operations, and feed this back to the user in some way

## Definitions and descriptions

Nodes to come with a description, and scalable names to be able to view. Depending on the zoom you would see different levels of detail. 

## Meaningful node colours

It's nice to colour them, but if that could be attached to a code / description / category it would make more sense. 

## Selectable / tiered detail on edges

So if you just want lines then start there, then adding:

- Direction / arrows
- Weights
- Polarity +/-

## Edge to edge

Not sure how to implement, but something to capture [[necessary-cause\|necessary cause]]


# Possibly implementation in [[loopy\|loopy]]

## Bug-ish fixes

These are the highest priority, and would make a huge difference.

- The "Node ..." settings are a bit annoying (when you click on a node and edit it's properties, these are "Start amount", "Node radius", "Node gain", "Node quantum")
	- The default of "Node gain" does not seem to be at unity (i.e. directly passing the input to output without changing the size of the signal)
	- It would be good to have them all set to just a 5-point scale, and the default being the middle. Currently some are 5, some are 7, and it some don't line up well with the selector so it is hard to see what is happening. 
- Word wrap on the node names so that longer names are a bit legible. 
- Draggable whole screen space. At the moment there is no way to click and drag the whole screen space, you have to drag each node individually. This is a problem sometimes when loading a saved graph from a different screen size - the graph will be out of screen and really hard to then move. Ideally clicking the whitespace and dragging (with the hand tool) would move the whole canvas position. An option to autozoom to fit everything in would also be great for this. 

## Additional export options

Currently it can be saved as a link and a file, but there are other options that would make this much, much more useful. 

- Export as DOT Language - https://graphviz.gitlab.io/doc/info/lang.html - You can see it implemented in the "Model code" section in DAGitty - https://www.dagitty.net/dags.html - it's just plain text that could be copied to clipboard. Would also be happy if there was an option to include / not include node position data (default would be to not include it). 

## Visual adjustments

These are probably the next best improvements to work on - will make a big difference to the user experience with (maybe) the least changes

- Visual clutter clean up
	- An option to hide the polarity (the +/-) on the edges. Nice options would be: Show +/-, Show - (i.e. hide unless it has been switched to -) and Always hide (you have to click on the edge to see)
	- An option to hide all the "amount" of each node, until you click "Play". I think for this mode perhaps each node is completely full of the colour. 
- Zoom! Currently no way to just zoom in or out.

## Less is more

- It would be nice to be able to customise which parts of the detail are needed when modelling. This would be a global setting. So for example, I click on a Node and all I see is Name, Description and nothing else, but there is an option to "show node features..." where you can include things like the Category, Start Amount, Node Size etc. Same for edges. I think the default starting point should be:
	- Nodes only show Name, Description, Category. Also visually they should be "hiding" the amount of each node (see the feature request in "visual adjustments") 
	- Edges only show "Relationship type" when clicked on, and this is hidden visually (again see "visual adjustments")

## Editing
- Keyboard: Delete key deletes the selected node / edge. This would be probably only safe with the undo feature as well (below).
- Undo last edit (not sure if that counts as minor adjustment - might be quite involved)

## Better node properties

Continuing from the options outlined under "bug-ish fixes" around node properties (5-point scale, etc)
- Under the node settings it would be great to have a *Description* as well as the *Name* field (paragraph length text). It might also be good to have *Abbreviation* as well (or even better, the Abbreviation is auto generated from the name). For instance you would type in "Student Knowledge" for the node name. Depending on the zoom level the graph would show "Student Knowledge" or "SK". If you click on the node you could then read a description field outlining what is meant by "Student Knowledge" (manually typed in).
- The colours are nice, but it would be better if these were named categories. So instead of choosing a colour, you select a category (which you could name) and then an option to assign this category a colour.


## More edge options

- Similar to the Node size, a 5-point scale of weighting for more / less important edges. 
- Additional options in "Relationship type" of:
	- Possible. This would have a `?` as an icon if shown, and be displayed as a dotted line. No signal would flow along this when you run the simulation. 
	- Undirected. This would have no arrows, and again not transmit signal. 

## More fancy things

These would be amazing, but certainly more work. 

- Split nodes - the ability to split a node into two. How this behaves with names and edges is a bit tricky though. 
- Merge nodes. 
- Edit tracking / export of data. Being able to track the generation of the graph as a series of graph operations (add, remove, edit nodes and edges and their features).
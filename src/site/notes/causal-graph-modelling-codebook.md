---
{"dg-publish":true,"permalink":"/causal-graph-modelling-codebook/"}
---

For thematic coding of [[participatory-causal-modelling\|Participatory Causal Modelling]] sessions. 

Each broad category should be internally mutually exclusive. So only one *graph* code should happen at any one time, and only one *causation* aspect should be discussed at one time. Some should overlap in particular ways, such as: `structure::path::reroute` should always wrap over a combo of `graph::edge::add` and `graph::edge::delete`. 

Coding procedure:
1. No audio, map basic graph edits. 
2. Add audio, looking for graph changes that might be encapsulated by structure changes.
3. Audio only. Listening for abstraction, theorising and causation language. 

It may also be useful to use surprise to detect interesting events / new info as [[surprise-might-be-a-way-to-measure-improved-thinking\|surprise-might-be-a-way-to-measure-improved-thinking]]. A possible process would be:

- Tokenisation and cleaning of words
- Text embedding. Something like [[word-2-vec\|Word2Vec]] which can handle conversational data and embeds some relative semantic meaning. [[bert\|BERT]] is better on well-structured text. 
- Dimension reduction (maybe?) using something like [[umap\|UMAP]]
- Looking at distance between successive units of the conversation. [[cosine-similarity\|Cosine similarity]] is probably a good choice (-1 opposite direction, 1 same, 0 orthogonal). 

Codebook draft one as image (delete later, for backup)

![Pasted image 20250502163355.png](/img/user/Images/Pasted%20image%2020250502163355.png)


# other thoughts on codes::

- divergence?
- surprise?

- [ ] #todo/this-week revise codes. So far graph and structure capture talk to model. Need better codes to capture graphical model to talk, and then perhaps talk between people / surprise / divergence. Is there a way this could be seen as moving between graph and participants, with self-feedback? Drawing graph is participants to graph, but there is also p->p, where they are reflecting. Is there a g->g code? Does the graph (with it's rules) somehow inform itself? Is this the facilitator prompting? Or editing / causal implications? Or do we need another node - the theory we are trying to form?? Does the facilitator need to come in as a node? What is it when the facilitator notices something about the graph, and uses it to probe into how the expert understands the system?
	- [ ] Thinking: graph + people, theory, graph interactions (below) + argumentation schemes + MAYBE TCM + MAYBE abstraction. Code with these and then look at what is useful.
- [ ] #todo/this-week Using an argumentation scheme? Might be a disctraction / to-formal? Simons book Argumentation Schemes by Walkton, Reed Macagno. CHAPTER 5. Encoding / Decoding from [[Sources/@rosenLifeItself1991\|@rosenLifeItself1991]].
- [ ] #todo/this-week Does the coding adequately answer the questions of: the graph helping people think *causally* about the system? Or more *formally*?
- [ ] #todo/this-week read the argumentation themes book. Has some good stuff. 

Is there a case for [[causal-diagrams-not-discerning-between-sufficient-and-necessary-causation\|causal-diagrams-not-discerning-between-sufficient-and-necessary-causation]]? In this case it might be prudent to code for discussion between [[sufficient-cause\|sufficient-cause]] and [[necessary-cause\|necessary-cause]], and what is harder to model as a [[graphical-causal-model\|graphical-causal-model]].

Triad: People, Theory, Graph / Model? Note that this "Theory" is really a "proto-theory". 

Theory -> People: Forming language around phenomena. 
Theory -> Graph: ? This would be causal discovery from text perhaps?? If we could do this then why bother with the 
People -> Graph: The drawing of the graph
People -> Theory: Asking questions about what we understand?? Surprise comes in here?
Graph -> Theory: Questions about the causal structure about the graph. Driven probably by facilitator. 
Graph -> People: Someone notices something in the graph shape.

# graph

This broader category is for graphical operations only. It should be able to be coded purely visually.

## graph::node

Operations on the nodes of the graph

### graph::node::add

A new node appears in the graph. 

### graph::node::delete

A node is removed from the graph. 

### graph::node::rename

The name of node is changed.


## graph::edge

### graph::edge::add

Adding an edge.

### graph::edge::delete

Deleting an edge. 

### graph::edge::direction

Any change to the direction of edges or paths, including the removal of direction. 

### graph::edge::polarity

Addition, deletion or change to graph edge polarity (+ or -).

### graph::edge::weight

Changes the 'weight' of the edge (stronger or weaker influence).

### graph::edge::function

Any notation added about the possible functional form of the graph - such as monotonic or switching behaviour. Probably unlikely to occur as this is harder to notate.

# structure

This category should overlap the graph edits. They will be higher level activites around a sequence of graph edits. 

## structure::node

### structure::node::fusion

When two nodes become one. This might be a bit challenging to see directly from the graph. Also use for grouping of nodes, where a set of nodes are grouped together under a new name, but the internal nodes are still kept on the graph. 

### structure::node::fission

When one node becomes two. This might be a little challenging to see directly from the graph.

## structure::path

This encapsulates changes to edges in the graph (a path directly between two nodes) but often the graph operations on edges are better seen in combination. This is because the operations are often performed as one conceptual move. Moving from A -> B to A -> M -> B is silly to see as delete AB, add AM, add MB. Really it is changing the path between A and B to include M as a mediator. 

### graph::path::reroute

Changing how A -> ... -> B moves. This could be inserting a mediator, or moving from a mediator to a direct connection. **This should occur over the top of an addition and deletion code.**

### graph::path::loop

Any addition or deletion of a cycle - either a self loop (A -> A) or a closed cycle (A -> B -> C -> A)


# abstraction

This is graph -> people? graph -> theory? The needs of the graph impose questions on the people.

## abstraction::bounding

Scope discussion. 

### abstraction::bounding::breadth

Discussion on whether variables should be included or not. 

### abstraction::bounding::values

What kinds of values should be included in the variables? This would capture things like "what types of students" and other context related discussion, such as restricting the discussion to "higher ed" only. 

### abstraction::bounding::time

## abstraction::fidelity

Discussion around how much to "zoom" in or out on model.


# theorising

This is people -> people. Or people -> theory? Or a mix between people and their understanding of the world (theory). 

[[theory-construction-methodology\|TCM]] come in here? - kind of in the Phenomena / Data / System??

### theorising::phenomena

Discussing the kinds of _phenomena_ that are important.

### theorising::generalising - explaining phenomena with an example might go here too?

Moving from *data* to *phenomena*. This would be thinking of examples, or instances, or actual data, and using it to describe more general phenomena. For instance, we could use some examples to help define a node, and how it relates to other nodes (so, part of the DAG, but not necessarily the whole thing). The “data provide evidence for the physical phenomena”.  Note that this is essentially step 1 of the TCM, identifying phenomena.

### theorising::explanation

Moving from _theory_ to _phenomena_. This would be along the lines of “well, if the model is like this then we should expect to see this kind of behaviour in the real world, or these kinds of relationships”. We would be quickly checking the explanatory power of the model. This could be from literature (i.e. theory knowledge) to aspects of the model (which nodes), or it could be from a general feeling of how the world works to descriptions of phenomena.

Is this also the place for missing data / paths? I.e. we look at the theory (graph) to identify what phenomena are missing? That is, a lack of explanatory power in the existing theory. 

Using the graph to interrogate the phenomena??

### theorising::abduction

Moving from *phenomena* to *theory*. This is the drawing of the DAG, or rather any kind of graph, and testing possible counter explanations. Thinking of potential confounders, mediators, alternative explanations - and then settling on the most probable model. Note that this is the second step of the TCM methodology, developing a proto-theory. I would posit that the formalisation of a proto-theory is done iteratively through abduction and explanation, and will be evidenced by the evolution of the DAG. The speed of the iteration may also be increased by the use of the diagram. This code may contain too much - it would account for drawing any kind of graph, and also for slowly becoming more precise…but maybe this is ok once it is looked at in conjunction with other codes?

Is node defining / scoping under this umbrella?? 

### theorising::prediction - or do examples go here??

Moving from _phenomena_ to _data_. If we think these things happen in the world, then we should expect to find some examples of it. For instance, we might discuss the general kind of observations we would expect to see (phenomena) and think of examples of those (the data), “phenomena predict specific patterns in the data”.

# causation

Based on [[ladder-of-causation\|ladder-of-causation]].

## causation::association

Discussion of _seeing_ patterns in the data - associations between variables.

## causation::influence

Discussion of variables causing / influencing one another

## causation::intervention

Discussions of the effect of changing the system by intervening, and what might the flow on effects be.

## causation::counterfactual

Discussion of scenarios counter to the fact - “what if?” questions.
---
{"dg-publish":true,"permalink":"/causal-graph-operation/"}
---

#graphical-modelling 

Making edits on a [[causal-dags\|causal-graph]].  

Would be good to understand these in terms of changes to the [[adjacency-matrix\|adjacency-matrix]] in terms of the [[space-of-possible-DAGs\|space-of-possible-DAGs]], as well as the [[path-space-of-DAGs\|path-space-of-DAGs]]. 

Also, these should all be in a [[requirements-for-a-causal-modelling-support-tool\|requirements-for-a-causal-modelling-support-tool]] such as [[loopy\|loopy]]


# Types of edits to a causal graph / DAG

## [[node\|Nodes]]

### Adding node

Could be adding causes or effects (which is a node + edge)
#### Adding free node
Just something that is important, no edges thought of.
#### Adding a mediator
#### Adding a common cause
#### Adding a common effect

### Removing node

#### Removing effects

### Node fusion

Two nodes become one

### Node fission

One node becomes two. This could be: 

#### Fission to two distinct nodes

#### Fission to two hierarchical nodes

One node is a subset of the other (typically represented as a downstream effect). 

## Edges / Paths [[edge\|edge]] / [[causal-paths\|path]]

### Edge addition

### Edge deletion

### Edge reversal??

### Edge shift??

Such as moving through somewhere, bypassing, stuff like that...


# Code book

See [[causal-graph-modelling-codebook\|causal-graph-modelling-codebook]] for these moves translated to a codebook for content analysis of [[participatory-causal-modelling\|Participatory Causal Modelling]] sessions. 




---
{"dg-publish":true,"permalink":"/identifiable/"}
---

#graphical-modelling 
A [[causal-dags\|DAG]] is **identifiable** regarding a particular causal path, $A \rightarrow B$, if it is possible to find an [[adjustment-set\|adjustment-set]] of variables to estimate the [[unbiased-causal-effect\|unbiased-causal-effect]] of $A$ on $B$. This is done by blocking all the [[back-door-paths\|back-door-paths]] between A and B, according to the [[do-calculus\|do-calculus]].

> [!quote] Ness, Causal AI pp50
> Causal inference can tell you when a causal prediction is “identified” (i.e., not “underspecified”), meaning a unique answer exists given the assumptions and the data.
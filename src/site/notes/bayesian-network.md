---
{"dg-publish":true,"permalink":"/bayesian-network/"}
---

A **Bayesian network** (also called a **Bayes net** or **BN**) is a type of **[[probabilistic-graphical-model\|probabilistic-graphical-model]]** that represents a set of random variables and their conditional dependencies using a **directed acyclic graph (DAG)**.

Here’s the breakdown:
- **[[node\|Nodes]]** → represent random variables.
- **[[edge\|Edges]] (arrows)** → represent conditional dependencies (e.g., rain → wet grass).
- **[[conditional-probability-distribution\|Conditional Prabability Distribution]] (CPDs)** → each node has an associated probability distribution that quantifies the effect of its parent nodes.

Mathematically, if the set of variables is $X_1, \dots, X_n$​, and the [[directed-acyclic-graph\|DAG]] encodes parent relationships, then the [[joint-probability-distribution\|join distribution]] factorizes as:

$$P(X_1, \dots, X_n) = \prod_{i=1}^n P(X_i \mid \text{Parents}(X_i))$$
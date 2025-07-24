---
{"dg-publish":true,"permalink":"/causal-dags/"}
---

#graphical-modelling

Causal Directed Acyclic Graphs (Causal [[directed-acyclic-graph\|DAG]]s, or simply DAGs) refer to the ==causal interpretation of a DAG== used to represent causal relationships between variables. It is a type of [[graphical-causal-model\|graphical-causal-model]] that has no loops / feedback. An underlying mathematical framework, the [[do-calculus\|do-calculus]], helps calculate [[implied-conditional-independencies\|implied-conditional-independencies]] you would expect to see in the data as well as implications of performing [[intervention\|intervention]] on the [[directed-acyclic-graph\|DAG]]. These implied independencies are closely related to the [[implied-probabilistic-model\|implied-probabilistic-model]] of a [[bayesian-network\|bayesian-network]]. 

The relationships only indicate some kind of causal effect, and not the functional form of it. With the functional form the become a Structural Causal Model ([[structural-causal-model\|SCM]]). If only the functional relationships are defined (usually for the linear case) then this is often called a Structural Equation Model ([[structural-equation-model\|SEM]]). 

### Thinking:
It might be worth splitting this out:
- DAGs 
- Bayesian Networks
A causal DAG is a particular interpretation of the two above.

### Imprecise Terminology
A [[directed-acyclic-graph\|DAG]] need not be interpreted causally - it is simply a collection of nodes and directed edges. However the community often refers to Causal DAGs simply as DAGs.

# Key results

## Conditional independence relationships

## Equivalence

Verma and Pearl (1990) prove that two DAGs are equivalent if and only if they have the same [[graph-skeleton\|skeleton]] and the same set of [[v-structures\|v-structures]] (from https://link.springer.com/content/pdf/10.1007/s10994-008-5057-7.pdf pg 268)

up:: [[graphical-causal-model\|graphical-causal-model]]



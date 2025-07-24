---
{"dg-publish":true,"permalink":"/sources/dawid-what-causal-graph2024/","title":"What Is a Causal Graph?","tags":["📖"]}
---


Dawid, P. (2024). What Is a Causal Graph? _Algorithms_, _17_(3), Article 3. [https://doi.org/10.3390/a17030093](https://doi.org/10.3390/a17030093)
[online](http://zotero.org/users/5872672/items/7THU7UCI) [local](zotero://select/library/items/7THU7UCI) [pdf](file:///Users/14055622/Zotero/storage/28JIW5S9/Dawid%20-%202024%20-%20What%20Is%20a%20Causal%20Graph.pdf)
 
Theory around #graphical-modelling 

Presented by [[People/Sally Cripps\|Sally Cripps]] at [[human-technology-institute\|human-technology-institute]] group (2024-10-30). By [[People/Philip Dawid\|Philip Dawid]] (more of a statistician), who has very different views to [[People/Judea Pearl\|Judea Pearl]].

Quite philosophical about what a [[causal-dags\|Causal DAG]] actually is, and precise about [[linking-models-to-causality\|linking-models-to-causality]]. 

### Thinking about DAGs

Is using this "immorality" / [[graph-morality\|graph-morality]] connections instead of [[d-separation\|d-separation]].

Graphs that are [[markov-equivalent\|markov-equivalent]] if they have the same [[graph-skeleton\|skeleton]] and the same [[graph-morality\|immoral]] pairs. 

### Informal Causal Semantics

This distinguish the [[map-and-the-territory\|map-and-the-territory]] really well: 

![Pasted image 20241030125912.png](/img/user/Images/Pasted%20image%2020241030125912.png)

Sally highlighted this:

![Pasted image 20241030132545.png](/img/user/Images/Pasted%20image%2020241030132545.png)

[[do-calculus\|do-calculus]] assumes the [[ignorability\|ignorability]] (that setting X=x is the same as observing X=x), but this argues that should not always be done.

### Distinguishing between Effects of Causes and Causes of Effects

Looks at [[effects-of-causes\|effects-of-causes]] where we consider the downstream consequences of interventions, and [[causes-of-effects\|causes-of-effects]].

This takes on a similar vein to the chapteron causation from [[Sources/@macagnoArgumentationSchemes2018\|@macagnoArgumentationSchemes2018]]

We can't unravel the causal bit, but we can unravel the [[probabilistic-causality\|probabilistic-causality]]:

$$PC=P(Y_0=0|X=1,Y_1=1)$$

# Words I didn't know

> Reification is ==the act of treating something abstract as if it were a concrete, physical thing==. It is a fallacy of ambiguity that can be used to describe a number of situations, including:

"Moralisation" - nodes that connect to a common cause but are not connected are "immoral", they have a child without being connected. Actually comes from thinking about bastard children. 

Covariance matrix $\Sigma$ inverse is called the "precision matrix" $\Lambda$, i.e. $\Lambda=\Sigma^{-1}$. Has some nice properties according to [[People/Sally Cripps\|Sally Cripps]]. Covariance matrix is "conditional", but precision is not. So for the DAG $X_1 \rightarrow X_3 \leftarrow X_2$ denotes an "immoral" relationship between $X_1$ and $X_2$. It will have zeros in the covariance matrix, but no zeros in the precision matrix. 

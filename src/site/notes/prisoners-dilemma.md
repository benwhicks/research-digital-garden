---
{"dg-publish":true,"permalink":"/prisoners-dilemma/"}
---

#mathematical-modelling/game-theory 

The Prisoners Dilemma (PD) is a [[game-theory-game\|game]] that models a situation where overall it is better if agents cooperate, but individually agents are better off if they do not cooperate. The scenario is described as two prisoners that have been accused of a crime. If they both *cooperate* (with each other, not with the authorities) and claim innocence they will receive a short sentence. They also have the option to *defect*, testifying against the other prisoner. In this case, if the other prisoner is claiming innocence (*cooperating*) then the *defecting* prisoners goes free (maximising their own utility) and their fellow prisoner receives the full sentence. 

Mathematically, the PD should satisfy two inequalities:

$$2V(C|C) > V(C|D) + V(D|C) > 2V(D|D)$$

and 

$$V(D|C) > V(C|C) > V(D|D) > V(C|D)$$

The first inequality shows that overall it is beneficial for both parties to cooperate. The second inequality shows that individually it is better to defect, not knowing what the other prisoner will do. Although this scenario uses prisoners, it can be extended to any situation with a choice between cooperation and self-interest is at stake. When extended over multiple games it is known as the Iterative Prisoner's Dilemma (IPD). A similar game is the [[snow-drift-game\|Snowdrift game]], which is almost identical except for the lower individual pay-offs. Both fall under the umbrella of [[cooperation-or-conflict-games\|cooperation-or-conflict-games]].

[[Sources/@mcelreathMathematicalModelsSocial2008\|@mcelreathMathematicalModelsSocial2008]] outlines this model in detail, and it's iterative variants, in chapter 3. 

#### Alternative notation

Sometimes the PD is described in terms of Reward (R) when both players cooperate, Punishment (P) when they both defect, a Temptation (T) when the defector gets the reward, and a sucker punishment (S) when a cooperator gets caught out by their opponent defecting. In this scenario, the PD is described as satisfying the inequality $T > R > P > S$, which is identical to the second inequality above. 
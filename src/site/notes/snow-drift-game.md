---
{"dg-publish":true,"permalink":"/snow-drift-game/"}
---

#mathematical-modelling/game-theory 

The snow drift [[game-theory-game\|game]] is an alternative way to examine the emergence of cooperation strategies to the Iterative [[prisoners-dilemma\|Prisoners Dilemma]] (IPD). The IPD usually does not produce as much cooperation as we see in many real world systems. The Iterative Snow Drift (ISD) adjusts the payoffs such that the risk of being exploited is less. 

Payoff matrix for snowdrift game

| Strategy | if they Cooperate | if they Defect |
| --- | --- | --- |
| Cooperate | 200 | 100 |
| Defect | 300 | 0 |


Compare this to the IPD payoff

| Strategy | if they Cooperate | if they Defect |
| --- | --- | --- |
| Cooperate | 300 | -100 |
| Defect | 400 | 0 |

If we use the notation $V(P|O)$ as the payoff to player $P$ if opponent plays $O$, with decisions from the set $\{C, D\}$, then the order of payoffs is:

- IPD: $V(D|C) > V(C|C) > V(D|D) > V(C|D)$
- ISP: $V(D|C) > V(C|C) > V(C|D) > V(D|D)$

The key difference is the much more acceptable risk of the other person defecting, in the PD the worst outcome is $V(C|D)$, where as in the SD game it is $V(D|D)$. This is closer to a group assignment proposition - it’s great if the other people contribute but if they are not going to it’s worth the risk to just do it yourself, you get a completed assignment and don’t go to jail (as per the PD).

> [!tldr] The Snowdrift game - description
> The situation of the Snowdrift game involves two drivers who are trapped on opposite sides of a snowdrift. Each has the option of staying in the car or shoveling snow to clear a path. Letting the opponent do all the work is the best option (with a pay-off of 300 used in this study), but being exploited by shoveling while the opponent sits in the car still results in a pay-off of 100. (The other two possibilities, both shoveling and both sitting, have pay-offs of 200 and 0, respectively.)
> - from this [blog post](https://phys.org/news/2007-10-snowdrift-game-tops-prisoner-dilemma.html), outlining work in “Human cooperation in social dilemmas: comparing the Snowdrift game with the Prisoner’s Dilemma”

Both these games, SD and PD, are variants on the [[hawk-dove-game\|hawk-dove-game]], and can be encapsulated as all kinds of [[cooperation-or-conflict-games\|cooperation-or-conflict-games]].

> [!seealso] Sources
> https://phys.org/news/2007-10-snowdrift-game-tops-prisoner-dilemma.html - has a good explanation, and references: 
> Citation: Kümmerli, Rolf, Colliard, Caroline, Fiechter, Nicolas, Petitpierre, Blaise, Russier, Flavien, and Keller, Laurent. “Human cooperation in social dilemmas: comparing the Snowdrift game with the Prisoner’s Dilemma.” _Proc. R. Soc. B_, doi:10.1098/rspb.2007.0793.

#todo analyse this from an EGT perspective
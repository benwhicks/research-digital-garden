---
{"dg-publish":true,"permalink":"/hawk-dove-game/"}
---

#mathematical-modelling/game-theory 
The Hawk Dove [[game-theory-game\|game]] describes the behaviour of two agents competing for resources. They can employ one of two strategies, the Hawk or the Dove. The Hawk always fights for the resource, and the Dove will always flee if confronted by a Hawk willing to fight. If two Doves meet, they perform a display to decide who gets the resource. The payoff matrix is as follows, with a resources of value $v$ and cost of fighting $c$: 

| | Hawk | Dove |
| --- | --- | --- |
| Hawk | $\frac{v-c}{2}$ | $v$ |
| Dove | 0 | $\frac{v}{2}$ |
---
{"dg-publish":true,"permalink":"/sources/pandey-gametheoretic-models-identify2016/","title":"Game-theoretic models identify useful principles for peer collaboration in online learning platforms","tags":["📖"]}
---

#mathematical-modelling/game-theory 

Pandey, V., & Chatterjee, K. (2016). Game-theoretic models identify useful principles for peer collaboration in online learning platforms. _Proceedings of the 19th ACM Conference on Computer Supported Cooperative Work and Social Computing Companion_, 365–368. [https://doi.org/10.1145/2818052.2869122](https://doi.org/10.1145/2818052.2869122)
[online](http://zotero.org/users/5872672/items/KGMJV6JN) [local](zotero://select/library/items/KGMJV6JN)

[[People/Vineet Pandey\|Vineet Pandey]], [[People/Krishnendu Chatterjee\|Krishnendu Chatterjee]]

[[game-theory\|game-theory]], [[game-theory-game\|game-theory-game]]

Implements a [[cooperation-or-conflict-games\|cooperation game]] simulation to show that design choices in a peer feedback system can dramatically influence the integrity of the peer feedback system. In particular, they examine the effect of including a threshold for the number of peer feedbacks a student must provide before seeing others feedback of their own work, with the game showing that without this requirement [[free-riders\|free loading]] behaviour arises and degrades the peer feedback system. 

This examines peer feedback systems in massive online learning spaces, in particular designing feedback systems for peer feedback of essays. The aim is to avoid [[free-riders\|free-riders]], who receive feedback but do not contribute. This seeks to address the [[intangible-data\|intangible-data]] of [[interactions-between-agents\|interactions-between-agents]] in a learning system. The [[game-theory-game\|game-theory-game]] is analysed through simulation, and a key parameter is the benefit ratio of cost of giving feedback to the reward for receiving feedback. Another was a threshold parameter: the number of feedbacks one must provide in order to see others feedback on their own work. Although not stated, this is a [[cooperation-or-conflict-games\|cooperation game]] framework, and with threshold at 0 (can see feedback straight away) this would lead to strategies emerging where players do not provide feedback, degrading the peer feedback system. 

> [!quote] Description of model
> **Game-theoretic model for peer feedback** 
> To understand how student behavior might be tweaked by design choices, we use game theory to model peer feedback at the scale of a thousand students. We demonstrate ways to identify better design choices, such as techniques to incentivize submitting feedback, **before** building the system. Our simulations do not assume rational behavior from the players (students in the peer feedback system). Instead, different players have strategies that evolve depending on payoffs provided by the game. A strategy that does not provide high payoff gets eliminated. Through simulations, we can predict parameters that help the game move towards favorable outcomes, which corresponds to more students submitting feedback. Previous work has used game theory to model peer reviews to minimize the error in grading assuming the availability of instructor grades [5]. We formally model peer feedback as a simple game without instructor involvement with the goal of increasing the number of students who provide feedback.

> [!quote] 
>  As an example, we explore the design space of a peer feedback system by modeling it using game theory. Our simulations show that incentivizing students to provide feedback requires the value obtained from receiving a feedback to exceed the cost of providing it by a large factor (greater than 7). Furthermore, hiding feedback from low-effort students incentivizes them to provide more feedback.


### Connections

supports:: [[Sources/@wuGameTheoryBased2015\|@wuGameTheoryBased2015]]
refutes:: 

### Notes
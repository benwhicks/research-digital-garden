---
{"dg-publish":true,"permalink":"/game-theory/"}
---

#mathematical-modelling/game-theory 
Game Theory is a branch of mathematical modelling that analyses the dynamics of a system by creating abstract models called *games*.  Although they are used to model actual games, from Rock, Paper, Scissors (Wang, 2014) to Chess, the analogy of a game can extend to a multitude of applications. Any systems in which *agents* interact with each other by employing different *strategies* can likely be modelled using a game theoretic model.  These agents are commonly individuals, such as people in social systems or animals in ecological systems, and each agent can employ a range of strategies in to achieve some desired outcome, such as acquiring resources. The strategies employed by agents describe how they interact with each other, and by describing these strategies and the population mathematically one can then make inferences using formal logic and analysis. 

Typically applications have been made in economics, politics, socio and evolutionary biology. There are a handful of applications in education, such as #getref which are primarily concerned with ...

Game Theory models are a deliberate oversimplification of reality, but they can provide valuable insight in situations where data is hard to obtain, and where the cumulative effect of many interactions in a heterogenous population is important. They are also useful as a theoreticians laboratory, using simple models to trade detail for clarity and offering tractable exploration of the system [[Sources/@mcelreathMathematicalModelsSocial2008\|@mcelreathMathematicalModelsSocial2008]]. 

Wang, Z., Xu, B., & Zhou, H. J. (2014). Social cycling and conditional responses in the Rock-Paper-Scissors game. _Scientific reports_, _4_(1), 5830.

``` bibtex
@article{wang2014social,
  title={Social cycling and conditional responses in the Rock-Paper-Scissors game},
  author={Wang, Zhijian and Xu, Bin and Zhou, Hai-Jun},
  journal={Scientific reports},
  volume={4},
  number={1},
  pages={5830},
  year={2014},
  publisher={Nature Publishing Group UK London}
}
```


## Related terms

- [[game-theory-agent\|game-theory-agent]]: Who is playing the game, also the players. 
- [[game-theory-game\|game-theory-game]]: The actual model. Analogous to a game being played between the agents. 
- [[game-theory-decision\|game-theory-decision]]
- [[game-theory-strategy\|game-theory-strategy]]
- [[game-theory-arena\|game-theory-arena]]: Where the game is played. 

[[evolutionary-game-theory\|Evolutionary Game Theory]] is a sub-branch of Game Theory that might have interesting parallels with how a learning ecosystem operates. As such, it might be interesting to exploring [[game-theoretic-models-of-learning-systems\|game-theoretic-models-of-learning-systems]], or [[game-theoretic-models-of-learning\|game-theoretic-models-of-learning]].

## Relationship to [[agent-based-models\|Multi-Agent Models]]

All games can be run as [[agent-based-models\|agent-based models]] (also called multi-agent models). This is necessary if there is no analytical solution to the game. Not all agent-based models can be expressed as games, however. Agent-based models are more general, with fewer assumptions on how the agents act, what they know, etc. 

> [!quote]- Blog on the [difference between game theory and agent-based modelling](https://www.abigaildevereaux.com/whats-the-difference-between-game-theory-and-agent-based-modeling/#:~:text=Game%20theory%20provides%20a%20theoretical,and%20are%20trying%20to%20achieve.).
> Game theory is a framework for strategic interaction developed so that players can generally “solve” for some strategy or mix of strategies that optimizes utility, profit, payoffs, or some other indicator of well-being. Even in complicated games, the idea is that players attempt to calculate some “best response” to all other possible strategy combinations that could be employed by their fellow players. Essentially, game theory is constructed so that the system reaches some kind of equilibrium or simple cyclic state as a result of every player employing their best response strategy (which may be a single strategy, a pattern of strategies, or a randomization of strategies).
> Evolutionary game theory involves another layer of calculation, whereby players are interested in not just the one-off maximum, but a long-term maximum. Remember, in evolutionary game theory, players want to maximize the aggregate payoff of some number of plays of the game. Evolutionary game theory expands the space of all strategy combinations or best responses available to the player. For instance, players may be able to avoid the anti-social equilibrium of the prisoner’s dilemma by employing a “trigger strategy” whereby they punish defection with defection for a certain number of turns. Depending on the expected payoff of defecting versus cooperating given the existence of a trigger strategy, and each player’s discount factor, players may be able to attain the welfare-maximizing optimum of the prisoner’s dilemma in evolutionary gameplay, while that optimum is not attainable in the absence of other contextual assumptions in one-off gameplay of the prisoner’s dilemma.
> Game theory provides a theoretical framework for 1) how players interact and 2) what they can and are trying to achieve through interaction. Agent-based modeling, on the other hand, leaves open-ended the questions of how players interact and what they can and are trying to achieve. Agents in agent-based models 1) interact with each other 2) towards some end. Agent characteristics, knowledge, and goals are left open-ended. Agents may not be trying to maximize utility, for instance, but are instead trying to maintain some kind of balance between the proportion of one type of agent in their immediate neighborhood versus another, as in the Schelling segregation model. Plan-ends are substituted for payoff maximization.
> In this sense, we see how agent-based models can easily c_ontain_ game theoretic models. We can define agents who play the prisoner’s dilemma with other agents. It’s typically easier to encode evolutionary gameplay in an agent-based model, since agents can record historical gameplay and update their states in most prefab agent-based frameworks like NetLogo.
> But agent-based modeling can go far beyond what is analytically feasible in traditional game theoretic frameworks. It can describe systems wherein not all agents play the same games, or play with each other. It allows for complex systemic outcomes, not just outcomes equivalent to static equilibria or simple patterns. It can more easily deal with nonintegral topologies of agent interaction, like when agent relationships constitute some kind of social network. It can track different levels of gameplay in the same system by updating one of a list of variables that describe the agent’s state.
> Most importantly, agent-based modeling doesn’t have the severe epistemological requirements of traditional, analytical game theory. That is, players are not assumed to have the cognitive or informational ability to completely solve for their best response. Generally, gameplay in agent-based models is locally constructive, meaning that agents play by taking into account their local states. So, a player on a social network plays according to the states of its nearest-neighbors, and not the states of the neighbors-of-their-neighbors, and so on, _even if those distant relationships do in fact influence the gameplay of their nearest neighbors._ That is, in agent-based modeling, there can be a system-level rationality that is not accessible by the individual agent.
> In traditional game theory, there is no separation between system-level and individual rationality. Even when players deviate from play that would increase their overall payoff if all other players cooperated, it’s not because they are unaware of this other system-level maximum, it’s because they do not believe it is accessible given the incentives faced by their fellow players. In agent-based modeling, there may be a number of system-level states that are generally unknown by the individual agent. This does not mean that agents cannot access these states. It just means they cannot access these states through direct computation of their existence.
> For more information on this very rich topic, I suggest looking at the work of [Scott Page](https://sites.lsa.umich.edu/scottepage/research-2/), [Jenna Bednar](http://www-personal.umich.edu/~jbednar/research.html), and [Leigh Tesfatsion](http://www2.econ.iastate.edu/tesfatsi/) on the connection between game theory and agent-based modeling. I have also [published a paper](https://journals.sagepub.com/doi/abs/10.1177/0569434518810506) on the subject, with a few more in the works at the time of writing this answer.

# Learning

https://gametheory101.com/courses/game-theory-101/ - some good reviews #learn/content

Two courses on Coursera with Stanford, https://www.coursera.org/learn/game-theory-1, and https://www.coursera.org/learn/game-theory-2

Yale online highly reccommended - https://online.yale.edu/courses/game-theory which has youtube version - https://www.youtube.com/playlist?list=PL6EF60E1027E1A10B

Big comprehensive book - https://www.cs.cmu.edu/~sandholm/cs15-892F13/algorithmic-game-theory.pdf 

## Tools

Worth checking out the Python package - https://www.sciencedirect.com/science/article/pii/S2589004223004960 - seems to be nice. Geared at EGT

And this one - https://www.sciencedirect.com/science/article/pii/S2589004223004960 ... wait is that the same? It is. Fucking look at it Ben. #todo/important 

## Applications



# Related reading 

This black swan book sounds great - https://www.amazon.com/Black-Swan-Improbable-Robustness-Fragility/dp/081297381X/ref=sr_1_1?ie=UTF8&s=books&qid=1275786808&sr=1-1 
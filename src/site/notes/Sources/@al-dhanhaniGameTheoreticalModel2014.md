---
{"dg-publish":true,"permalink":"/sources/al-dhanhani-game-theoretical-model2014/","title":"A game theoretical model for collaborative groups in social applications","tags":["📖"]}
---


Al-Dhanhani, A., Mizouni, R., Otrok, H., & Al-Rubaie, A. (2014). A game theoretical model for collaborative groups in social applications. _Expert Systems with Applications_, _41_(11), 5056–5065. [https://doi.org/10.1016/j.eswa.2014.02.050](https://doi.org/10.1016/j.eswa.2014.02.050)
[online](http://zotero.org/users/5872672/items/DAUSI4KJ) [local](zotero://select/library/items/DAUSI4KJ)

#mathematical-modelling/game-theory 

[[People/Ahmed Al-Dhanhani\|Ahmed Al-Dhanhani]], [[People/Rabeb Mizouni\|Rabeb Mizouni]], [[People/Hadi Otrok\|Hadi Otrok]], [[People/Ahmad Al-Rubaie\|Ahmad Al-Rubaie]]

The paper adopts the [[social-exchange-theory\|social-exchange-theory]] as a basis to build a [[game-theory\|game theoretic]] model of knowledge exchange between learners in an online environment, with the main trade being requesting help and answering questions. The [[prisoners-dilemma\|prisoners-dilemma]] is used as a starting point because of the need to analyse a situation were reciprocation is central to success of the group, and [[tit-for-tat-strategy\|tit-for-tat-strategy]] as a base starting strategy for simulation. They then suggest group reputation as a new [[tit-for-tat-strategy\|tit-for-tat-strategy]] to motivate free riders to be more collaborative.

Methods involve setting up the games, then running simulations to examine the overall fitness. 

Thoughts:
- Only one education citation, with this applied to a Moodle environment - https://www.tandfonline.com/doi/abs/10.1080/13614568.2023.2228249, in [[Sources/@nooraniEGTMoodleEducationalGame2023\|@nooraniEGTMoodleEducationalGame2023]]
- This model is specific to online. It could be extended to classroom (with a teacher presence, someone who answers more) or forum group (with multiple 'tutors' answering questions) to gauge design issues in forums. 
- Is one measure of fitness enough here? Or cost? Could there be a time cost, and a knowledge cost? I would have thought that the answerer of a question is also learning. 


> [!quote] Highlights (copied)
> - Proposing an analytical model for [collaborative groups](https://www.sciencedirect.com/topics/computer-science/collaborative-group "Learn more about collaborative groups from ScienceDirect's AI-generated Topic Pages") based on repeated game theory.
> - Simulating participants’ behaviours using different existing Tit for Tat strategies.
> - Analysing the impact of the [free riders](https://www.sciencedirect.com/topics/computer-science/free-rider "Learn more about free riders from ScienceDirect's AI-generated Topic Pages") in [collaborative groups](https://www.sciencedirect.com/topics/computer-science/collaborative-group "Learn more about collaborative groups from ScienceDirect's AI-generated Topic Pages") [survivability](https://www.sciencedirect.com/topics/engineering/survivability "Learn more about survivability from ScienceDirect's AI-generated Topic Pages").
> - Proposing the group reputation tit for tat strategy to motivate [free riders](https://www.sciencedirect.com/topics/computer-science/free-rider "Learn more about free riders from ScienceDirect's AI-generated Topic Pages").

## The model (copied)

Consider that we have a group of (_N_) participants in a social application, each user is a member of _m_ groups and posts made by users are restricted to groups. Each user is able to:

- 1.Post a request. 
- 2. Answer others’ requests
- 3. Ignore a request because s/he is not able to answer it.
- 4. Ignore a request although s/he is able to answer it. Such a behaviour is known as “selfish” or “free riding”.

We also assume that :
- 1. The social application is keeping track of all requests and responses of each participant.
- 2. The social application is updating each user with the cooperation status of the other users.
- 3. The group lifetime is infinite.
- 4. All participants are active.
- 5.  The community is well established and active and in a state where it is in need of more answers rather than requests.
- 6.  Any request may have more than one answer.

![Pasted image 20240725132643.png](/img/user/Images/Pasted%20image%2020240725132643.png)

![Pasted image 20240725132706.png](/img/user/Images/Pasted%20image%2020240725132706.png)

### Connections

supports:: [[Sources/@nooraniEGTMoodleEducationalGame2023\|@nooraniEGTMoodleEducationalGame2023]]
refutes:: 

### Notes


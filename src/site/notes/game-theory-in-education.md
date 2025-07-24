---
{"dg-publish":true,"permalink":"/game-theory-in-education/"}
---

#mathematical-modelling

The use of [[game-theory\|game-theory]] to analyse learning systems has a long but sparse history. Correa (1974), then again in [[Sources/@correaTeacherstudentInteractionGame1987\|@correaTeacherstudentInteractionGame1987]] used the mathematical framework of game theory to build a model of teacher-student interaction, hinged around the relationship between effort and (perceived) student academic achievement. This was later expanded by [[Sources/@montmarquetteCouldTeacherGrading1989\|@montmarquetteCouldTeacherGrading1989]] to show how lenient grade practices can arise as an unintended side effect of trying to improve student outcomes, and when included as a latent variable helped explain some apparent gains in improvement in standardised tests of their cohort of interest. 


	H. Correa, Abstract of a mathematical model of teacher-student interaction, in: Proceedings of the Fifth Annual Conference on Modeling and Simulation (School of Engineering, University of Pittsburgh, Pittsburgh, PA, 1974) 423-428.

## Patterns in how game theory models have been applied

The thesis here is that the model is usually based on some theory. This theory is then explored in a highly simplified and constrained model (the game), but even with these tight restrictions in can push towards further questions or suggestions for practice. Ideally then these are either tested in further models, or tested against the data, or possibly feedback into theory ( #getref - are there examples of these?).

Are they often used to analyse [[intangible-data\|intangible-data]]?

### Examples

Theory -> Model -> Extended model -> Informing data analysis
#todo - what theory was the original built on?. [[Sources/@montmarquetteCouldTeacherGrading1989\|@montmarquetteCouldTeacherGrading1989]] extended the model of teacher-student interaction developed by [[Sources/@correaTeacherstudentInteractionGame1987\|@correaTeacherstudentInteractionGame1987]] to include grading practices. This also led to informing the latent variable of a regression model to test their theory against the data. This same model was extended by [[Sources/@bonesronningVariationTeachersGrading1999\|@bonesronningVariationTeachersGrading1999]] to examine grading practices in Norway, and compared with data this suggested that harder grading was having a positive effect on (particularly high achieving) students, although further investigation was suggested before this headed towards policy decisions. They were concerned that "teacher quality" in particular was not accounted for. 

Theory -> Policy -> Implications -> 
[[Sources/@niklassonGamelikeRegulationUniversities1996\|@niklassonGamelikeRegulationUniversities1996]] looks at the theory of "responsive regulation" to build the model, replicates this as applied to the new Swedish policy, examines the implications, and then compares this with the data. #todo - is this good for LLMs?

Theory --> Model --> Learning design
[[Sources/@pandeyGametheoreticModelsIdentify2016\|@pandeyGametheoreticModelsIdentify2016]]
[[Sources/@nooraniFosteringPeerLearning2022\|@nooraniFosteringPeerLearning2022]]
[[Sources/@yusriTeensOnlineGameTheoryBased2021\|@yusriTeensOnlineGameTheoryBased2021]]

Phenomena --> Model --> Explanation
Some work around grade inflation might fit here, such as [[Sources/@correaGameTheoreticAnalysis2001\|@correaGameTheoreticAnalysis2001]] around faculty competition and academic standards. 

## Approaches of the application of game theory to education

### Education policy

> [!quote] From [[Sources/@cohenStudentEngagementPostgraduate2018\|@cohenStudentEngagementPostgraduate2018]]
> Game theory is concerned with the incentives, possible actions (and reactions) of participants, and the information that is available to each party. The theory provides a formal method that is useful in examining interactions that occur where cooperation or conflict exists. The use of game theory in the education literature has largely been confined to education policy (Law and Pan 2009; Niklasson 1996). This chapter extends that work into the classroom.


[[Sources/@grantFacultyEvaluationSocial1998\|@grantFacultyEvaluationSocial1998]] implement a two-levelled iterative [[prisoners-dilemma\|prisoners-dilemma]] that examines department level and individual level cooperation (or not) towards outcomes. Agents (either department or individual) are balancing allocation of resources towards Research, Teaching or Service. They conclude that the status quo does not support cooperation in a higher ed setting where tenure is a central goal, and that constructs such as reputation and trust are important. 

[[Sources/@selimEducationMarketEgypt2008\|@selimEducationMarketEgypt2008]] use a three stage [[game-theory-game\|game-theory-game]] to understand the apparent paradox of the current [[policy\|policy]] of 'free education for all' and it's unintended effects. The [[game-theory-game\|game]] is used to explore different possible worlds of education subsidization and how it might look different under different [[policy\|policy]] scenarios. [[Sources/@ekinciMCDMbasedGametheoreticApproach2022\|@ekinciMCDMbasedGametheoreticApproach2022]] also look at the dynamics between government and universities, taking a mathematical approach to solve for [[nash-equilibrium\|nash-equilibrium]] for various games. 

[[Sources/@olteanQualitativeGameTheoretic2016\|@olteanQualitativeGameTheoretic2016]] build on the work of [[Sources/@correaTeacherstudentInteractionGame1987\|@correaTeacherstudentInteractionGame1987]] outlined below as a social learning model, but then apply a policy lens to this. This is done through linking in with work around emerging or ideal free-market economies. Their end warning is that the system dynamics of poor funding and need for results can drive the system towards poorer outcomes in the longer term. 

[[Sources/@niklassonGamelikeRegulationUniversities1996\|@niklassonGamelikeRegulationUniversities1996]] explores the dynamics between government and universities. 

[[Sources/@lawGameTheoryEducational2009\|@lawGameTheoryEducational2009]]

### In the learning environment

> From [[Sources/@nooraniFosteringPeerLearning2022\|@nooraniFosteringPeerLearning2022]]:
> ![Pasted image 20240905144153.png](/img/user/Images/Pasted%20image%2020240905144153.png)
> ![Pasted image 20240905144214.png](/img/user/Images/Pasted%20image%2020240905144214.png)
> ![Pasted image 20240905144252.png](/img/user/Images/Pasted%20image%2020240905144252.png)

[[Sources/@correaTeacherstudentInteractionGame1987\|@correaTeacherstudentInteractionGame1987]] use an iterative form of the [[prisoners-dilemma\|prisoners-dilemma]] to examine teacher-student effort, and also other games on the influence of class size ^[H. Correa and G. W. Gruver, ‘‘Teacher-student interaction: A game theoretic extension of the economic theory of education,’’ Math. Social Sci., vol. 13, no. 1, pp. 19–47, 1987.] ^[H. Correa, ‘‘An economic analysis of class size and achievement in education,’’ Educ. Econ., vol. 1, no. 2, pp. 129–135, 1993]. 
#### Grading practices

[[Sources/@montmarquetteCouldTeacherGrading1989\|@montmarquetteCouldTeacherGrading1989]] extend the teacher-student effort model from [[Sources/@correaTeacherstudentInteractionGame1987\|@correaTeacherstudentInteractionGame1987]] model to examine teacher-student interactions around effort and outcomes (and grading practices in the [[Sources/@montmarquetteCouldTeacherGrading1989\|@montmarquetteCouldTeacherGrading1989]] model). Correa returns later in [[Sources/@correaGameTheoreticalAnalysis2003\|@correaGameTheoreticalAnalysis2003]] to model the interactions between instructors and students. The teacher-student interactions are very hard to get data on and the grading practices also. Much later [[Sources/@olteanQualitativeGameTheoretic2016\|@olteanQualitativeGameTheoretic2016]] present a model that reframes this in terms of student effort and teacher "verification", within the context of the international education system itself. They make a qualitative argument that an emerging economy, with teachers trying to survive and students trying to acquire degrees, pushes towards an uncooperative and suboptimal system. 

[[Sources/@cohenStudentEngagementPostgraduate2018\|@cohenStudentEngagementPostgraduate2018]] provide an argument that [[game-theory-game\|game-theory-game]]s can be used to help examine behaviour in learning systems. In particular these models can be used in situations where we put educators or students in situations with 'unpalatable choices', such as situations that lead to [[grade-inflation\|grade-inflation]]. 

#### Classroom cooperation


[[Sources/@al-dhanhaniGameTheoreticalModel2014\|@al-dhanhaniGameTheoreticalModel2014]] use an iterative form of the [[prisoners-dilemma\|prisoners-dilemma]] game to model cooperative and non-cooperative behaviour in online forums. Users were assigned various [[tit-for-tat-strategy\|tit for tat strategies]] and the scenarios were simulated. The authors offer a group reputation approach as being potentially useful in designing a learning space that fosters greater collaboration. This advice was then implemented and tested by [[Sources/@nooraniEGTMoodleEducationalGame2023\|@nooraniEGTMoodleEducationalGame2023]], with very positive results. [[Sources/@cohenStudentEngagementPostgraduate2018\|@cohenStudentEngagementPostgraduate2018]] make a qualitative argument that concepts from [[game-theory\|game-theory]] should be used to help foster [[student-engagement\|student-engagement]] in learning systems. 


[[Sources/@nooraniGameTheoreticApproachGroup2018\|@nooraniGameTheoreticApproachGroup2018]] build a model on a question-answer-explain scenario in a classroom, with one student offering their explanation of a solution to a question before moving on. They ground this in [[competition-based-learning\|competition-based-learning]] theory. Analysing the payoff matrix for [[nash-equilibrium\|Nash Equilibrium]] they show that the reward payoff for a good explanation should be three (or more) times the penalty for a bad one. They also implement this design in a classroom setting as an experiment. [[Sources/@nooraniFosteringPeerLearning2022\|@nooraniFosteringPeerLearning2022]] then move towards designing a peer assessment of group contribution, based on the [[prisoners-dilemma\|prisoners-dilemma]]. The idea was to increase the perceived payoff of the [[pareto-optimum\|Pareto efficiency]] strategy profile of (Cooperate, Cooperate) and move them away from the [[nash-equilibrium\|NE]] of (Defect, Defect). This was mechanised through public peer assessments of effort, and the ability to change teammates. 

[[Sources/@talankerEstablishingStudentsCooperation2019\|@talankerEstablishingStudentsCooperation2019]] examine [[tit-for-tat-strategy\|tit-for-tat-strategy]] in the context of building trust between student and teacher. They use a [[game-theoretic-explanations\|game-theoretic-explanations]] of the scenario of establishing trust (an [[intangible-data\|intangible-data]] point), suggesting that a TFxT strategy is best, where the choice (of the teacher) is to cooperate until a student defects x times. 

[[Sources/@zhangGamePerspectiveCollaborative2022\|@zhangGamePerspectiveCollaborative2022]] analyse a model of student collaboration using [[evolutionary-stable-strategy\|evolutionary-stable-strategy]]s. They note that students will increase collaboration when the academic and social payoff is higher, or the cost of time and effort is less. 


#### Peer feedback

[[Sources/@pandeyGametheoreticModelsIdentify2016\|@pandeyGametheoreticModelsIdentify2016]] implement a [[cooperation-or-conflict-games\|cooperation game]] simulation to show that design choices in a peer feedback system can dramatically influence the integrity of the peer feedback system (they build on the game-theory inspired mechanisms described in [[Sources/@wuGameTheoryBased2015\|@wuGameTheoryBased2015]]). In particular, they examine the effect of including a threshold for the number of peer feedbacks a student must provide before seeing others feedback of their own work, with the game showing that without this requirement [[free-riders\|free loading]] behaviour arises and degrades the peer feedback system. 

[[Sources/@zongExperiencesInteractionalInequality2022\|@zongExperiencesInteractionalInequality2022]] use [[game-theoretic-explanations\|game-theoretic-explanations]] to come up with hypothesis to test around [[peer-feedback\|peer-feedback]], using the [[prisoners-dilemma\|PD]] game as a basis. They find that experiencing inequality of perceived effort (I put more effort into the feedback I provided than what I received) changes the length of future feedback. 




There is a masters thesis on crowd sourcing education, to model incentives and contributions on crowdsourcing platforms. - de Mars, S. (2013). Crowdsourcing education: A game-theoretic analysis of contribution and learning in peer to peer education platforms. _bachelor of arts thesis, Department of Applied Mathematics, Harvard College_. But was hard to get into Zotero. 



### Not really examples

[[Sources/@lawGameTheoryEducational2009\|@lawGameTheoryEducational2009]] offers [[game-theoretic-explanations\|game-theoretic-explanations]] of phenomena.

[[Sources/@burguilloUsingGameTheory2010\|@burguilloUsingGameTheory2010]] uses game theory to inspire activities to [[gamification-of-education\|gamification-of-education]].

[[Sources/@quigleyWhereWeGo2013\|@quigleyWhereWeGo2013]] uses [[game-theoretic-explanations\|game-theoretic-explanations]] to provide more of a [[complex-system\|complex system]] argument, that [[learning-is-complex\|education is complex]] and needs decisions and strategy to happen at [[multi-scalar\|multiple scales]]. 

[[Sources/@wuGameTheoryBased2015\|@wuGameTheoryBased2015]] look at mechanisms for [[peer-feedback\|peer-feedback]] / grading, but are more using game theory informed mechanisms, rather than a model that is analysing dynamics as such. 


# Future applications

My ideas

- Model of LLMs as an invasive species
- Model of 'attention' as the key resource / utility. Could link to dopamine - obvious issues with other devices!
- Some models players have full knowledge of the state, others do not. Could learning be this knowledge increasing in some way?
- Could the classroom model of learning be around talk time? Could have student - teacher - LLM as the three components / strategies? Or better looking at different student strategies: ask peer, ask teacher, ask LLM?
- Does the introduction of an LLM offer a way to get resource without sharing? i.e. offers a new kind of defect strategy to the free rider
- Could use the model in [[Sources/@zhangGamePerspectiveCollaborative2022\|@zhangGamePerspectiveCollaborative2022]] between collaborating and non-collaborating students. Starting proportion $p$ on a line on a triangle. New strategy emerges, collaboration with LLM, instead of human. What are the dynamics? i.e. given establish norms in a classroom, what happens when an LLM invades?
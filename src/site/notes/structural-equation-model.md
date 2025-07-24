---
{"dg-publish":true,"permalink":"/structural-equation-model/"}
---


### Relationship to Multilevel Models
[Some believe](https://curran.web.unc.edu/wp-content/uploads/sites/6785/2015/03/Curran2003.pdf) in many cases [[multilevel-models\|multilevel-models]] are broadly identical to SEMs, despite quite different underlying assumptions. SEMs assume independence of residuals, whilst Multilevel Models explicitly model dependent data structures. There is [a paper](https://bpspsychub.onlinelibrary.wiley.com/doi/abs/10.1111/bmsp.12217) to #read on causal graph views that might help join the dots here. 




# Compost

``` latex
\documentclass{article}
\usepackage{graphicx} % Required for inserting images

\title{LAK24 Ben Practitioner report on SEMs to DAGs}
\author{Ben Hicks}
\date{September 2023}

\begin{document}

\maketitle

\section{Introduction}

% https://www.sciencedirect.com/science/article/pii/S0742051X21001621?casa_token=ds82zWMTnsAAAAAA:-OP7IlL2aRwTSaOp4AasyPY4VNQbl3ivOkH-zNcsJkq7dTCEVLb7qYK8sr-aG2AeBZgrMFmNTw
\cite{yin2021applying} review Teaching and Teaching Education (TATE) journal articles using SEM.Most use Covariance Based (CB) SEM, with 10 including some path analysis. They note these have been increasing over the years. They note that ``Theories such as the SDT, the JD-R model, and the TPB are frequently used to support research hypotheses and to help with the result interpretation.'' They also note that ``SEM studies should not be purely driven by data but should be reasonably led by theories''. They also highlight concerns with some methodological choices, such as the use of path analysis without the use of latent constructs or measurement errors, which should in turn not be treated as SEM analysis. In relation to making causal inferences they say \textbf{``although causes (independent variables) and effects (dependent variables) are specified in SEM, traditional SEM, like many other non-experimental methods, cannot really be used to demonstrate causal effects.''}

\section{Introduction}

Why are people using SEM?

What more is offered 

\section{Introduction}

\subsection{Institutional context / Student experience surveys}


Facts and figures about the uni (keeping in mind that it needs to be blinded)
https://www.uts.edu.au/about/university/facts-figures-and-rankings

\subsection{Structural equation modelling in Learning Analytics}

% \cite{yin2021applying} review Teaching and Teaching Education (TATE) journal articles using SEM. Most use Covariance Based (CB) SEM, with 10 including some path analysis. They note these have been increasing over the years. They note that ``Theories such as the SDT, the JD-R model, and the TPB are frequently used to support research hypotheses and to help with the result interpretation.'' They also note that ``SEM studies should not be purely driven by data but should be reasonably led by theories''. They also highlight concerns with some methodological choices, such as the use of path analysis without the use of latent constructs or measurement errors, which should in turn not be treated as SEM analysis. In relation to making causal inferences they say \textbf{``although causes (independent variables) and effects (dependent variables) are specified in SEM, traditional SEM, like many other non-experimental methods, cannot really be used to demonstrate causal effects.''}

Reviews of the use of SEMs in education have highlighted concerns in correct use of the methodology

\subsection{Modelling the causal structure}



\section{Research Q}

\begin{itemize}
    \item RQ1: What are the causal assumptions behind a neutral approach to SEM?
    \item RQ2: What causal structure can we discover from X?
    \item RQ3: What insights can be gained from imposing a causal structure on X?
\end{itemize}

\section{Implicit causal structure}

What do the assumptions behind a `typical' model look like?

Given outcome $Y$ and latent factors $X_i$ we might be tempted to `control' for everything in the model. 
This amounts to a model definition where the effect of each factor depends on the value of the other factors in the model, 

\begin{equation}
    Y \sim \sum_{i=1}^{n}{X_i}
\end{equation}

Starburst mode of SEM 

$Y \sim \begin{Bmatrix} f_1 \\ ... \\f_n \end{Bmatrix}$.

These are both niave in terms of any indirect effects. 

Existing model. SEM. 

Questions raised by the model.

Could profile - students getting support v students not getting support? At the moment student support is anti-correlated with student satisfaction...which has been removed from the original report. 


\section{Discovering causal structure}

The underlying causal structure, in some cases, can be discovered from the data \cite{}. 

\section{Imposing causal structure}

Making some stronger assumptions (maybe based on the causal discovery, possibly plus some science or expert knowledge). 

\section{Comparison / Discussion}

What is the difference in the calculation of key factors towards student satisfaction, based on the different methods? 
Would this change the recommendations for intervention?

\end{document}
```


# OptAzur: Optimization in French Riviera

OptAzur is an ongoing effort to foster collaborations among members of Université Côte d'Azur on different aspect of optimization and its applications to machine learning, imaging and signal processing, etc. 

## Seminar

OptAzur organizes a monthly seminar in Nice and Sophia-Antipolis, which alternates between the two sites and takes place on the third Monday of each month. [Google Calendar](https://calendar.google.com/calendar/u/0?cid=Nzc3NjM0ZDhlMjNkMjE2YTIyZjJlNDVkMmYxYzU2Y2ZkMWIyY2FmZDRkZWRiMGY0ODQ1OGE1NWJlZjRmN2EwZkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)

### Next talk

Monday, October 16th, 2023 (I3S, Sophia-Antipolis)

14h - [Gersende Fort](https://perso.math.univ-toulouse.fr/gfort/) (CNRS, Institut de Mathématiques de Toulouse)

**Stochastic Approximation beyond Gradient**

In Machine Learning, many analyzes and methods rely on Optimization, including its stochastic versions introduced for example to tackle non-closed forms of the objective function or to reduce the computational cost.
In 1951, H. Robbins and S. Monro introduced the method named "Stochastic Approximation" which is a root-finding method when the objective function is defined by an intractable expectation: it defines a sequence of iterates by using a Monte Carlo approximation of the expectation. Then, this method was generalized to solve a root-finding problem when only stochastic oracles of the objective field are available.

Stochastic Gradient algorithms are the most popular instances of Stochastic Approximation. Nevertheless, Stochastic Approximation also contains far more general algorithms said "beyond gradient" since roughly, they consist in solving a minimization problem by using a vector field which is not a gradient field.  These "beyong gradient" Stochastic Approximation methods often come with the additional difficulty that the stochastic oracles are biased approximations of the vector field.   They occur in Computational Statistics (for example, some stochastic versions of Expectation Maximization are an instance of this beyond gradient case) and in Machine Learning as well (for example, some Temporal Difference algorithms for the estimation of the value function in Reinforcement Learning, are another instance).

This talk will first detail examples of such beyond gradient Stochastic Approximation methods. We will then show how to derive a general enough theory, in order to encompass as many as possible instances of Stochastic Approximation: we will emphasize the theory devoted to finite time analysis and will discuss how to choose design parameters of the algorithm in order to reach an epsilon-stationary point. We will finally show how to improve the original Stochastic Approximation scheme by plugging a variance reduction technique.

This talk is based on joint works with Aymeric Dieuleveut (CMAP, Ecole Polytechnique), Eric Moulines (CMAP, Ecole Polytechnique) and Hoi-To Wai (Chinese University of Hong-Kong, Hong-Kong).

15h15 - [Samuel Vaiter](https://samuelvaiter.com) (CNRS, Laboratoire J. A. Dieudonné)

**Garanties de convergence pour la différentiation automatique**

Dans cet exposé, je présenterai quelques résultats de convergence concernant la différentiation automatique d'algorithmes itératifs, qu'ils soient "lisses" ou non. Alors que les asymptotiques des problèmes lisses sont bien compris (Gilbert 1992, Beck 1994), principalement grâce à l'utilisation d'un théorème de point fixe, le cas non-lisse présente davantage de difficultés. Je montrerai comment le cadre des Jacobiens conservatifs permet d'obtenir de tels résultats. J'illustrerai également une stratégie à adopter lorsque l'opérateur n'est pas contractant, en prenant pour motivation la différentiation de l'algorithme de Sinkhorn-Knopp. Enfin, j'introduirai la différentiation en un coup, une méthode qui alliera la simplicité de la différentiation automatique à la performance de la différentiation implicite. Cette approche, particulièrement adéquate pour les algorithmes rapides, sera illustrée à travers des méthodes d'optimisation superlinéaires et des scénarios d'optimisation bi-niveaux. Travaux en collaboration avec J. Bolte et E. Pauwels.

### Previous talks

Titles and abstracts [here](/previous)

- #1: [Jean-François Aujol](https://www.math.u-bordeaux.fr/~jaujol/) (Université de Bordeaux) and [Luca Calatroni](https://sites.google.com/view/lucacalatroni/home) (CNRS, I3S)

## Events

The members organize several conferences and workshops relevant to the optimization community, as detailled below.

- [Bilevel optimization in machine learning and imaging sciences workshop](https://iciam2023.org/registered_data?id=00400) @[ICIAM 2023](https://iciam2023.org/accepted_ms#00400_Bilevel_optimization_in_machine_learning_and_imaging_sciences), Tokyo, Japan. (Organizers: L. Calatroni, S. Vaiter)

- [Optimal control: methods and applications](https://iciam2023.org/registered_data?id=00731) @[ICIAM 2023](https://iciam2023.org), Tokyo, Japan. (Organizers: J.-B. Caillau, L. Dell'Elce, Clément Moreau)

## Scientific Committee

- [Laure Blanc-Féraud](https://www.i3s.unice.fr/~blancf/)
- [Luca Calatroni](https://sites.google.com/view/lucacalatroni/home) (co-organizer)
- [Jean-Baptiste Caillau](https://caillau.perso.math.cnrs.fr)
- [Yassine Laguel](https://yassine-laguel.github.io)
- [Samuel Vaiter](https://samuelvaiter.com) (co-organizer)

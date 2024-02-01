# Previous talks @OptAzur

## OptAzur #5 -- Monday, January 15th, 2024 (LJAD, Nice)

14h - [Marco Lorenzi](https://marcolorenzi.github.io) (Inria)

**Federated Learning in Healthcare Applications: from Theory to Practice**

This talk will illustrate current advances in federated learning (FL) for sensitive applications, from a both theoretical and practical perspectives. 
In spite of the wide interest in the federated learning paradigm, current applications to sensitive domains, such as healthcare, are still challenging due to the complexity in dealing with heterogeneous and complex data hosted in different hospitals, as well as to the practical difficulty of deploying federated architectures in the real world.
I will first cover a novel theory for modeling the impact of clients heterogeneity on the convergence guarantees of federated learning [1, 2]. In particular, I will study the robustness and variability of federated learning to heterogeneous conditions, by introducing the notion of stochastic aggregation weights. The proposed framework allows to derive novel federated optimization schemes to maximise the representativity and minimize the variability of clients contributions across federated optimization rounds.
I will also introduce a novel perspective to Federated Unlearning (FU), a novel FL problem aiming at providing theoretical guarantees on the removal of the contribution of a given client from a federated training procedure. Upon unlearning request from a given client, FU is based on the definition of criteria to identify the optimal FL iteration from which FL has to be reinitialized, along with randomized perturbation mechanism to provide unlearning guarantees [3]. 
Finally, from the practical standpoint, the talk will introduce Fed-BioMed, a development initiative aiming at translating federated learning to healthcare applications [4]. Fed-BioMed tackles the challenges required to meet real-world translation, concerning FL security, scalability and interoperability. I will give an illustration of the interplay between methodological development and translational effort that characterise the development of the Fed-BioMed FL platform, and discuss our current effort in delivering FL in hospitals networks. 
[1] Fraboni Y., Vidal R., Kameni L. and Lorenzi M. Clustered sampling: Low-variance and improved representativity for clients selection in federated learning., In International Conference on Machine Learning (pp. 3407-3416). PMLR. 
[2] Fraboni Y., Vidal R., Kameni L. and Lorenzi M. A General Theory for Federated Optimization with Asynchronous and Heterogeneous Clients Updates., Journal of Machine Learning Research (110):1-43, 2023.
[3] Fraboni Y., Vidal R., Kameni L. and Lorenzi M. Sequential Informed Federated Unlearning: Efficient and Provable Client Unlearning in Federated Optimization., arXiv preprint arXiv:2211.11656.
[4] Cremonesi F., et al.Fed-BioMed: Open, Transparent and Trusted Federated Learning for Real-world Healthcare Applications, White paper, arXiv:2304.12012.

## OptAzur #4 -- Monday, December 18th, 2023 (Sophia)

14h - [Maurizio Filippone](https://www.eurecom.fr/~filippon/) (EURECOM)

**One-Line-of-Code Data Mollification Improves Optimization of Likelihood-based Generative Models**

Generative Models (GMs) have attracted considerable attention due to their tremendous success in various domains, such as computer vision where they are capable to generate impressive realistic-looking images. Likelihood-based GMs are attractive due to the possibility to generate new data by a single model evaluation. However, they typically achieve lower sample quality compared to state-of-the-art score-based diffusion models (DMs). This paper provides a significant step in the direction of addressing this limitation. The idea is to borrow one of the strengths of score-based DMs, which is the ability to perform accurate density estimation in low-density regions and to address manifold overfitting by means of data mollification. We propose a view of data mollification within likelihood-based GMs as a continuation method, whereby the optimization objective smoothly transitions from simple-to-optimize to the original target. Crucially, data mollification can be implemented by adding one line of code in the optimization loop, and I will show that this provides a boost in generation quality of likelihood-based GMs, without computational overheads. I will then present results on real-world image data sets and UCI benchmarks with popular likelihood-based GMs, including variants of variational autoencoders and normalizing flows, showing large improvements in FID score and density estimation.

15h15 - [Yassine Laguel](https://yassine-laguel.github.io) (LJAD, Nice)

**High Probability and Risk-Averse Guarantees for Stochastic Saddle Point Problems**

We investigate the stochastic accelerated primal-dual algorithm for strongly-convex-strongly-concave saddle point problems, common in distributionally robust learning, game theory, and fairness in machine learning. Our algorithm offers optimal complexity in several settings and we provide high probability guarantees for convergence to a neighborhood of the saddle point. We derive analytical formulas for the limit covariance matrix and develop lower bounds to show that our analysis is tight. Our risk- averse convergence analysis characterizes the trade-offs between bias and risk in approximate solutions. We present numerical experiments on zero-sum games and robust learning problems.

## OptAzur #3 -- Monday, November 20th, 2023 (Nice)

14h - [Massimiliano Pontil](https://www.iit.it/people-details/-/people/massimiliano-pontil) (Italian Institute of Technology and University College London)

**Learning Dynamical Systems Via Koopman Operator Regression**

Non-linear dynamical systems can be handily described by the associated Koopman operator, whose action evolves every observable of the system forward in time.
These operators are instrumental to forecasting and interpreting the system dynamics, and have broad applications in science and engineering.
The talk gives a gentle introduction to this topic, with a focus on theory and algorithms.
We highlight the importance of algorithms that allow us to estimate the spectral decomposition of the Koopman operator well and explore how the quest for good representations for these operators can be formulated as an optimization problem involving neural networks.

15h15 - [Mathieu Carrière](https://www-sop.inria.fr/members/Mathieu.Carriere/) (Inria)

**A Framework to Differentiate Persistent Homology with Applications in Machine Learning and Statistics**

Solving optimization tasks based on functions and losses with a topological flavor is a very active and growing field of research in data science and Topological Data Analysis, with applications in non-convex optimization, statistics and machine learning. However, the approaches proposed in the literature are usually anchored to a specific application and/or topological construction, and do not come with theoretical guarantees. To address this issue, we study the differentiability of a general map associated with the most common topological construction, that is, the persistence map. Building on real analytic geometry arguments, we propose a general framework that allows to define and compute gradients for persistence-based functions in a very simple way. We also provide a simple, explicit and sufficient condition for convergence of stochastic subgradient methods for such functions. This result encompasses all the constructions and applications of topological optimization in the literature. Finally, we will showcase some associated code, that is easy to handle and to mix with other non-topological methods and constraints, as well as some experiments demonstrating the versatility of the approach.

## OptAzur #2 -- Monday, October 16th, 2023 (Sophia)

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

## OptAzur #1 -- Monday, September 18th, 2023 (Nice)

14h - [Jean-François Aujol](https://www.math.u-bordeaux.fr/~jaujol/) (Université de Bordeaux)

**FISTA is an automatic geometrically optimized algorithm for strongly convex functions**

This work is related with large scale optimization. We are interested in the famous FISTA algorithm. We show that FISTA is an automatic geometrically optimized algorithm for functions satisfying a quadratic growth assumption. This explains why FISTA works better than the standard Forward-Backward algorithm (FB) in such a case, although FISTA is known to have a polynomial asymptotical convergence rate while FB is exponential. We provide a simple rule to tune the α parameter within the FISTA algorithm to reach an ε-solution with an optimal number of iterations. These new results highlight the efficiency of FISTA algorithms, and they rely on new non asymptotic bounds for FISTA.
This is a joint work with Charles Dossal and Aude Rondepierre (INSA Toulouse).

15h15 - [Luca Calatroni](https://sites.google.com/view/lucacalatroni/home) (CNRS, I3S)

**Scaled, inexact and adaptive FISTA for (strongly) convex optimisation**

We design an inexact, scaled and generalised Fast Iterative Soft-Thresholding Algorithm (FISTA) for minimising the sum of two (possibly strongly) convex functions. Inexactness is explicitly taken into account for describing situations where proximal operators cannot be evaluated in closed form. The use of data-dependent scaling allows to incorporate Newton-type information along the optimisation via variable-metric updates. Finally, non-monotone backtracking is used to improve convergence speed.  Linear convergence for the function values is proved with rates depending on backtracking/scaling and strong convexity parameters. The performance of the proposed algorithm, named SAGE-FISTA, is validated on exemplar imaging problems where sparsity-promoting (l_1, TV) regularisation is combined with popular data-fidelity terms. Numerical results show improved performance and practical efficiency under limited computational budget.
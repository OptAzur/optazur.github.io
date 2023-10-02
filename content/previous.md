# Previous talks @OptAzur

## OptAzur #1 -- Monday, September 18th, 2023

14h - [Jean-François Aujol](https://www.math.u-bordeaux.fr/~jaujol/) (Université de Bordeaux)

**FISTA is an automatic geometrically optimized algorithm for strongly convex functions**

This work is related with large scale optimization. We are interested in the famous FISTA algorithm. We show that FISTA is an automatic geometrically optimized algorithm for functions satisfying a quadratic growth assumption. This explains why FISTA works better than the standard Forward-Backward algorithm (FB) in such a case, although FISTA is known to have a polynomial asymptotical convergence rate while FB is exponential. We provide a simple rule to tune the α parameter within the FISTA algorithm to reach an ε-solution with an optimal number of iterations. These new results highlight the efficiency of FISTA algorithms, and they rely on new non asymptotic bounds for FISTA.
This is a joint work with Charles Dossal and Aude Rondepierre (INSA Toulouse).

15h15 - [Luca Calatroni](https://sites.google.com/view/lucacalatroni/home) (CNRS, I3S)

**Scaled, inexact and adaptive FISTA for (strongly) convex optimisation**

We design an inexact, scaled and generalised Fast Iterative Soft-Thresholding Algorithm (FISTA) for minimising the sum of two (possibly strongly) convex functions. Inexactness is explicitly taken into account for describing situations where proximal operators cannot be evaluated in closed form. The use of data-dependent scaling allows to incorporate Newton-type information along the optimisation via variable-metric updates. Finally, non-monotone backtracking is used to improve convergence speed.  Linear convergence for the function values is proved with rates depending on backtracking/scaling and strong convexity parameters. The performance of the proposed algorithm, named SAGE-FISTA, is validated on exemplar imaging problems where sparsity-promoting (l_1, TV) regularisation is combined with popular data-fidelity terms. Numerical results show improved performance and practical efficiency under limited computational budget.
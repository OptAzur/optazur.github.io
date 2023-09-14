# OptAzur: Optimization in French Riviera

OptAzur is an ongoing effort to foster collaborations among members of Université Côte d'Azur on different aspect of optimization and its applications to machine learning, imaging and signal processing, etc. 

## Seminar

OptAzur organizes a monthly seminar in Nice and Sophia-Antipolis, which alternates between the two sites and takes place on the third Monday of each month. [Google Calendar](https://calendar.google.com/calendar/u/0?cid=Nzc3NjM0ZDhlMjNkMjE2YTIyZjJlNDVkMmYxYzU2Y2ZkMWIyY2FmZDRkZWRiMGY0ODQ1OGE1NWJlZjRmN2EwZkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)

### Next talk

Monday, September 18th, 2023 (Salle Fizeau, LJAD, Nice)

14h - [Jean-François Aujol](https://www.math.u-bordeaux.fr/~jaujol/) (Université de Bordeaux)

**FISTA is an automatic geometrically optimized algorithm for strongly convex functions**

This work is related with large scale optimization. We are interested in the famous FISTA algorithm. We show that FISTA is an automatic geometrically optimized algorithm for functions satisfying a quadratic growth assumption. This explains why FISTA works better than the standard Forward-Backward algorithm (FB) in such a case, although FISTA is known to have a polynomial asymptotical convergence rate while FB is exponential. We provide a simple rule to tune the α parameter within the FISTA algorithm to reach an ε-solution with an optimal number of iterations. These new results highlight the efficiency of FISTA algorithms, and they rely on new non asymptotic bounds for FISTA.
This is a joint work with Charles Dossal and Aude Rondepierre (INSA Toulouse).

15h15 - [Marco Lorenzi](https://marcolorenzi.github.io) (Inria)

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

### Previous talks

## Events

The members organize several conferences and workshop relevant to the optimization community, as detailled below.

- [Bilevel optimization in machine learning and imaging sciences workshop](https://iciam2023.org/registered_data?id=00400) @[ICIAM 2023](https://iciam2023.org/accepted_ms#00400_Bilevel_optimization_in_machine_learning_and_imaging_sciences), Tokyo, Japan. (Organizers: L. Calatroni, S. Vaiter)

- [Optimal control: methods and applications](https://iciam2023.org/registered_data?id=00731) @[ICIAM 2023](https://iciam2023.org), Tokyo, Japan. (Organizers: J.-B. Caillau, L. Dell'Elce, Clément Moreau)

## Scientific Committee

- [Laure Blanc-Féraud](https://www.i3s.unice.fr/~blancf/)
- [Luca Calatroni](https://sites.google.com/view/lucacalatroni/home) (co-organizer)
- [Jean-Baptiste Caillau](https://caillau.perso.math.cnrs.fr)
- [Yassine Laguel](https://yassine-laguel.github.io)
- [Samuel Vaiter](https://samuelvaiter.com) (co-organizer)

---
title: "Learning and Optimization in Côte d'Azur 2024"
---

**September 23-25, 2024**

The workshop focuses on optimization applied to solving problems in imaging and machine learning. This event will bring together experts to explore the latest advancements in these themes. Participants will have the opportunity to exchange innovative ideas to tackle current challenges in optimization and machine learning.

## Speakers

- [Aurélien Bellet](http://researchers.lille.inria.fr/abellet/) (Inria)
- [Jérôme Bolte](https://www.tse-fr.eu/fr/people/jerome-bolte) (Toulouse School of Economics)
- [Claire Boyer](https://perso.lpsm.paris/~cboyer/) (Sorbonne Université)
- [Julie Delon](https://judelo.github.io/) (Université Paris-Descartes)
- [Anna Korba](https://akorba.github.io/) (ENSAE)
- [Jérôme Malick](https://membres-ljk.imag.fr/Jerome.Malick/index.html) (CNRS, Université Grenoble-Alpes)
- [Gabriel Peyré](https://www.gpeyre.com/) (CNRS, École Normale Supérieure)
- [Gabriele Steidl](https://page.math.tu-berlin.de/~steidl/) (TU Berlin)

## Location

The workshop will take place at the [I3S](https://www.i3s.unice.fr/en/) institute, room 007, Université Côte d'Azur, Sophia-Antipolis, France.

## Schedule

### September 23: Mini-course

- 13:30: Registration & Welcome
- 14:00-15:30: Mini-course "Optimal Transport in Machine Learning" by [Elsa Cazelles](https://www.irit.fr/~Elsa.Cazelles/)
- 15:30-16:00: Coffee break
- 16:00-17:30: Mini-course "Optimal Transport in Machine Learning" by [Elsa Cazelles](https://www.irit.fr/~Elsa.Cazelles/)

### September 24: Conference

- 09:00-09:30: Welcome
- 09:30-10:30: Jérôme Bolte

**TBA**

Abstract: TBA

- 10:30-11:00: Coffee break
- 11:00-12:00: Aurélien Bellet

**Differentially Private Optimization with Coordinate Descent and Fixed-Point Iterations**

Abstract: Machine learning models are known to leak information about individual data points used to train them. Differentially private optimization aims to address this problem by training models with strong differential privacy guarantees. This is achieved by adding controlled noise to the optimization process, for instance during the gradient computation steps in the case of the popular DP-SGD algorithm. In this talk, I will discuss how to beyond DP-SGD by (i) introducing private coordinate descent algorithms that can better exploit the problem structure, and (ii) leveraging the framework of fixed-point iterations to design and analyze new private optimization algorithms for centralized and federated settings. 

- 12:00-14:00: Lunch
- 14:00-15:00: Session poster
- 15:00-16:00: Julie Delon

**TBA**

Abstract: TBA

- 16:00-16:30: Coffee break
- 16:30-17:30: Claire Boyer

**A primer on physics-informed learning**

Abstract: Physics-informed machine learning combines the expressiveness of data-based approaches with the interpretability of physical models. In this context, we consider a general regression problem where the empirical risk is regularized by a partial differential equation that quantifies the physical inconsistency. 
Practitioners often resort to physics-informed neural networks (PINNs) to solve this kind of problem. After discussing some strengths and limitations of PINNs, we prove that for linear differential priors, the problem can be formulated directly as a kernel regression task, giving a rigorous framework to analyze physics-informed ML. In particular, the physical prior can help in boosting the estimator convergence.


### September 25: Conference

- 09:30-10:30: Anna Korba

**Implicit Diffusion: Efficient Optimization through Stochastic Sampling**

Abstract: We present a new algorithm to optimize distributions defined implicitly by parameterized stochastic diffusions. Doing so allows us to modify the outcome distribution of sampling processes by optimizing over their parameters. We introduce a general framework for first-order optimization of these processes, that performs jointly, in a single loop, optimization and sampling steps. This approach is inspired by recent advances in bilevel optimization and automatic implicit differentiation, leveraging the point of view of sampling as optimization over the space of probability distributions. We provide theoretical guarantees on the performance of our method, as well as experimental results demonstrating its effectiveness. We apply it to training energy-based models and finetuning denoising diffusions.

- 10:30-11:00: Coffee break
- 11:00-12:00: Gabriel Peyré

**Transformers are Universal In-context Learners**

Abstract: Transformers deep networks define “in-context mappings'”, which enable them to predict new tokens based on a given set of tokens (such as a prompt in NLP applications or a set of patches for vision transformers). This work studies the ability of these architectures to handle an arbitrarily large number of context tokens. To mathematically and uniformly address the expressivity of these architectures, we consider that the mapping is conditioned on a context represented by a probability distribution of tokens (discrete for a finite number of tokens). The related notion of smoothness corresponds to continuity in terms of the Wasserstein distance between these contexts. We demonstrate that deep transformers are universal and can approximate continuous in-context mappings to arbitrary precision, uniformly over compact token domains. A key aspect of our results, compared to existing findings, is that for a fixed precision, a single transformer can operate on an arbitrary (even infinite) number of tokens. Additionally, it operates with a fixed embedding dimension of tokens (this dimension does not increase with precision) and a fixed number of heads (proportional to the dimension). The use of MLP layers between multi-head attention layers is also explicitly controlled. This is a joint work with Takashi Furuya (Shimane Univ.) and Maarten de Hoop (Rice Univ.).

- 12:00-14:00: Lunch
- 14:00-15:00: Jérôme Malick

**Towards more resilient, robust, responsible decisions**

This talk will be a gentle introduction to — and a passionate advocacy for — distributionally robust optimization (DRO). Beyond the classical empirical risk minimization paradigm in machine learning, DRO has the ability to effectively address data uncertainty and distribution ambiguity, thus paving the way to more robust and fair models. In this talk, I will highlight the key mathematical ideas, the main algorithmic challenges, and some versatile applications of DRO. I will insist on the statistical properties of DRO with Wasserstein uncertainty, and I will finally present an easy-to-use toolbox (with scikit-learn and PyTorch interfaces) to make your own models more robust.

Abstract: TBA

- 15:00-15:30: Coffee break
- 15:30-16:30: Gabriele Steidl

**Gradient flows, non-smooth kernels and generative models for posterior sampling in inverse problems**

Abstract: This talk is concerned with inverse problems in imaging from
a Bayesian point of view, i.e. we want to sample from the posterior 
given noisy measurement. 
We tackle the problem by studying gradient flows of particles in high dimensions.
More precisely, we analyze Wasserstein gradient flows 
of maximum mean discrepancies defined with respect to different kernels, 
including non-smooth ones.
In high dimensions, we propose the efficient flow computation via Radon transform (slicing) and
subsequent sorting or Fourier transform at nonequispaced knots.
Special attention is paid to non-smooth Riesz kernels.
We will see that Wasserstein gradient flows 
of corresponding maximum mean discrepancies have a rich structure. 
In particular, singular measures can become absolutely continuous 
ones and conversely.
Finally, we approximate our particle flows by conditional generative neural networks 
and apply them for conditional image generation and in inverse image restoration problems
like computerized tomography and superresolution.
This is joint work with 
Johannes Hertrich (UCL) and 
Paul Hagemann, Fabian Altekrüger, Robert Beinert, Jannis Chemseddine, Manual Gräf, Christian Wald (TU Berlin).

## Scientific committee
- Laure Blanc-Féraud
- Jean-Baptiste Caillau
- Luca Calatroni
- Yassine Laguel
- Samuel Vaiter

## Sponsors

![Université Côte d'Azur](/img/unica.png)
![I3S](/img/i3s.png)
![LJAD](/img/ljad.png)
![Morpheme](/img/morpheme.png)
![RT MAIAGES](/img/maiages.png)
![Inria](/img/inria.png)
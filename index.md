---
layout: default
---

At UC Berkeley's [Center for Targeted Machine Learning and Causal Inference](https://ctml.berkeley.edu/), our **OTMLE** (**O**ptimal Transport and **T**argeted **M**aximum **L**ikelihood **E**stimation) reading group explores the intersection of optimal transport theory and TMLE, offering a fresh perspective on how TMLE fluctuations of probability measures can be understood. The group covers key topics, including _history of optimal transport_, _Wasserstein metrics_, _geodesics_, _gradient flows_, _statistical estimation_, and _information geometry_. Each session focuses on one of these themes, providing participants with a comprehensive foundation to bridge optimal transport with statistical estimation techniques in TMLE.

We invite _all_ enthusiasts, researchers, and practitioners—regardless of affiliation with the CTML—to join our reading group sessions. Your interest and contributions are highly valued, as we believe that a diverse community fosters richer discussions and deeper understanding. Whether you're new to the field or have extensive experience, we welcome you to be part of our collaborative exploration of optimal transport and TMLE.

To stay informed about our reading group sessions and the latest developments at the CTML, we invite you to subscribe to both our [reading group's mailing list](https://forms.gle/bg4UQBNcc1rHEr6p6) and the [CTML newsletter](https://berkeley.us21.list-manage.com/subscribe?u=2abb346cb31a2e829e779ecbb&id=c7203ec4f3). Joining these mailing lists ensures you receive timely updates on meeting schedules, discussion topics, and upcoming events.

![Optimal Transport](https://www.microsoft.com/en-us/research/uploads/prod/2020/09/OTDD_Shovel-Figure.png)

<span style="font-size: 10px;">*Image courtesy of Microsoft Research. [Original image link](https://www.microsoft.com/en-us/research/uploads/prod/2020/09/OTDD_Shovel-Figure.png). Used under [Microsoft's terms of use](https://www.microsoft.com/en-us/legal/terms-of-use).*</span>

Our weekly reading materials will be drawn from the following list, though it is not exhaustive. We have carefully hand-picked these resources to offer not only a comprehensive introduction to optimal transport theories but also to emphasize aspects that are potentially useful in relation to TMLE.

# Core References
- Agueh, M., & Carlier, G. (2011). Barycenters in the Wasserstein space. _SIAM Journal on Mathematical Analysis, 43_(2), 904-924.
- Ambrosio, L., Gigli, N., & Savaré, G. (2008). _Gradient flows: in metric spaces and in the space of probability measures._ Springer Science & Business Media.
- Peyré, G., & Cuturi, M. (2019). Computational optimal transport: With applications to data science. _Foundations and Trends® in Machine Learning, 11_(5-6), 355-607.
- Villani, C. (2009). _Optimal transport: old and new_ (Vol. 338, p. 23). Berlin: springer.
- Villani, C. (2021). _Topics in optimal transportation_ (Vol. 58). American Mathematical Soc..

# Supplementary References
- Agueh, M., & Carlier, G. (2017). Vers un théorème de la limite centrale dans l'espace de Wasserstein?. _Comptes Rendus. Mathématique_, 355(7), 812-818.
- Benamou, J. D., & Brenier, Y. (2000). A computational fluid mechanics solution to the Monge-Kantorovich mass transfer problem. _Numerische Mathematik, 84_(3), 375-393.
- Chernozhukov, V., Galichon, A., Hallin, M., & Henry, M. (2017). Monge–Kantorovich depth, quantiles, ranks and signs.
- Engquist, B., Froese, B. D., & Yang, Y. (2016). Optimal transport for seismic full waveform inversion. _arXiv preprint arXiv:1602.01540._
- Figalli, A., & Glaudo, F. (2021). _An invitation to optimal transport, Wasserstein distances, and gradient flows._
- Gibbs, A. L., & Su, F. E. (2002). On choosing and bounding probability metrics. _International statistical review, 70_(3), 419-435.
- Jordan, R., Kinderlehrer, D., & Otto, F. (1998). The variational formulation of the Fokker--Planck equation. _SIAM journal on mathematical analysis, 29_(1), 1-17.
- Panaretos, V. M., & Zemel, Y. (2019). Statistical aspects of Wasserstein distances. _Annual review of statistics and its application, 6_(1), 405-431.
- Panaretos, V. M., & Zemel, Y. (2020). _An invitation to statistics in Wasserstein space_ (p. 147). Springer Nature.
- Santambrogio, F. (2015). Optimal transport for applied mathematicians. _Birkäuser, NY_, 55(58-63), 94.
- Tsybakov, A. B. (2009). Lower bounds on the minimax risk. _Introduction to Nonparametric Estimation_, 77-135.
- Van der Laan, M. J., & Rose, S. (2011). _Targeted learning: causal inference for observational and experimental data_ (Vol. 4). New York: Springer.
- Van der Laan, M. J., & Rose, S. (2018). _Targeted learning in data science._ Cham: Springer International Publishing.
- Wainwright, M. J. (2019). High-dimensional statistics: A non-asymptotic viewpoint (Vol. 48). Cambridge university press.


# Fall 2024: Foundations of Optimal Transport
The Fall 2024 semester introduces participants to the foundational concepts of optimal transport, covering the three primary formulations: Monge, Kantorovich, and Benamou-Brenier formulations. These are explored alongside their respective characterizations of the Wasserstein distance and the optimal transport plans that emerge in each framework. This exploration provides a comprehensive understanding of how optimal transport establishes metrics over probability spaces and how these relate to statistical estimation and hypothesis testing.

A key focus is understanding TMLE as a dynamic path in probability space, where optimal transport provides a spatial and geometric viewpoint. Participants examine how properties of optimal transport plans—such as monotonicity, duality, geodesics, and gradient flows—inform the theoretical underpinnings of TMLE. This semester emphasizes building a strong foundation and connecting the "moving mass" perspective of optimal transport to the iterative updates in TMLE.

## [Introduction]
> **Date**: September 25th, 2024
>
> **Presenter**: Kaiwen Hou
>
> **Optional Reading**: Villani (2021) Sections 0.1-0.3, 2.1-2.3.1
*   Purpose of the reading group and its role in advancing targeted learning
*   Logistics: meeting times, room assignments, and reading materials for the semester
*   Basic concepts: source measure, target measure, transport map, and pushforward
*   Monge's formulation, existence, and uniqueness
*   Kantorovich's relaxation and transport plan
*   Property of the optimal transport map: monotonicity
*   Optimal transport map implied by TMLE
>
> **Unresolved Questions**:
*   Compactness of the coupling space
*   Weierstrass theorem: existence in Kantorovich's formulation
*   Existence of suboptimal transport plan in proving monotonicty


## [Geometry of Optimal Transport]
> **Date**: October 2nd, 2024
>
> **Presenter**: Kaiwen Hou
>
> **Reading**: Villani (2021) Sections 2.2-2.3.2, 1.1.1-1.1.5; Santambrogio (2015) Box 1.1, Theorem 1.4
>
> **Optional Reading**: Villani (2021) Sections 4.1, 1.1.6-1.2, 2.1.1-2.1.3; Santambrogio (2015) Section 1.2
*   Construction of optimal transport map
*   Cyclical monotonicity and Rockafellar's theorem
*   Monge–Ampère equation
*   Existence of optimal transport plan in Kantorovich's formulation


## [Wasserstein Distances]
> **Date**: October 9th, 2024
>
> **Presenter**: [Qiuran Lyu](https://lqrrrrr.github.io/)
>
> **Reading**: Villani (2021) Sections 7.1, 7.4, Exercise 7.11
>
> **Optional Reading**: Villani (2021) Sections 7.2-7.3; [Engquist, Froese & Yang (2016)](https://arxiv.org/pdf/1602.01540) Theorem 5
*   Wasserstein metric: nonnegativity and symmetry
*   Gluing lemma to prove the triangle inequality
*   Proof of gluing lemma
*   Ordering and interpolation inequalities
*   Topological properties: robustness to oscillations
*   Convexity properties and behavior under rescaled convolution


## [Statistical Inference Based on Wasserstein Distances]
> **Date**: October 16th, 2024
>
> **Presenter**: [Wenxin Zhang](https://ctml.berkeley.edu/people/wenxin-zhang)
>
> **Reading**: Villani (2021) Sections 2.1.5, 5.1.3; [Agueh & Carlier (2011)](https://hal.science/hal-00637399/document) Sections 1-3, 6; [Panaretos & Zemel (2019)](https://arxiv.org/pdf/1806.05500) Sections 2.1, 3.1
>
> **Optional Reading**: Villani (2021) Sections 5.2.1-5.2.2; Santambrogio (2015) Lemma 5.29, Proposition 5.32; [Agueh & Carlier (2017)](https://www.sciencedirect.com/science/article/pii/S1631073X17301528); Panaretos & Zemel (2020)
*   Properties of Wasserstein distances under shifts, scaling, and product measures
*   Subadditivity of Wasserstein distances w.r.t. convolutions
*   Wasserstein test statistics for empirical measures and/or two samples
*   Asymptotic distributions of Wasserstein test statistics under univariate measures
*   Wasserstein Fréchet mean of univariate location family: sufficient condition
*   Wasserstein Fréchet mean of two measures: displacement interpolation
*   Wasserstein Fréchet mean of Gaussian distributions is Gaussian


## [Ten Metrics on Probability Measures]
> **Date**: October 23rd, 2024
>
> **Presenter**: [Qiuran Lyu](https://lqrrrrr.github.io/)
>
> **Reading**: [Gibbs & Su (2002)](https://arxiv.org/pdf/math/0209021) Figure 1, Sections 2-3
>
> **Optional Reading**: [Peyré & Cuturi (2019)](https://arxiv.org/pdf/1803.00567) Sections 8.1-8.4; Tsybakov (2009) Section 2.4; Wainwright (2019) Chapter 15
*   Definitions
*   f-divergence
*   Metric inequalities and [proof](./notes/metric_inequalities.pdf)


## [Monge–Kantorovich Depth]
> **Date**: October 30th, 2024
>
> **Presenter**: [Yilong Hou](https://statistics.berkeley.edu/people/yilong-hou)
>
> **Reading**: Villani (2021) Proposition 2.4, Theorem 2.9; [Chernozhukov et al. (2017)](https://arxiv.org/pdf/1412.8434) Paragraphs "Notation, conventions and preliminaries", "MK depth is halfspace depth in dimension 1", Sections 2.3, 3.2-3.3, A, B3-4
>
> **Optional Reading**: [Duality and Double Convexification](./notes/double_convexification.pdf) (scribed by [Qiuran Lyu](https://lqrrrrr.github.io/))
*   [Statistical depth and Tukey halfspace depth](./notes/preliminary_statistical_depth.pdf)
*   Monge–Kantorovich depth
*   Kantorovich-Brenier theorem
*   Empirical depth, quantiles, and ranks
*   Uniform convergence of empirical transport maps


## [Euler Equation and Geodesics]
> **Date**: November 6th, 2024
>
> **Presenter**: Mingxun Wang
>
> **Reading**: Figalli & Glaudo (2021) Sections 1.3, 2.5.4
>
> **Optional Reading**: Villani (2021) Theorem 3.8, Sections 3.1-3.3; [Notes](./notes/polar_factorization.pdf)
*   Basics of Riemannian geometry: tangent space, gradient, arc length parameterization, Riemannian distance, and geodesic
*   Incompressible Euler equation
*   Arnold's geodesic interpretation: measure-preserving orientation-preserving diffeomorphism
*   Brenier's approximate geodesics: midpoint projection onto closure
*   Polar factorization theorem
*   Helmholtz decomposition of differentiable vector fields into irrotational and solenoidal vector fields


## [Benamou-Brenier Formulation (1)]
> **Date**: November 13th, 2024
>
> **Presenter**: [Yi Li](https://ctml.berkeley.edu/people/yi-li)
>
> **Reading**: Villani (2021) Sections 8.1-8.2
>
> **Optional Reading**: Villani (2021) Sections 5.1, 8.3
*   Continuity equation: velocity field and Lagrangian specification of flow field
*   Benamou-Brenier formulation of Wasserstein distance: kinetic energy and action functional
*   Otto's calculus and interpretation


## [Variational Formulation of Fokker-Planck Equation]
> **Date**: November 20th, 2024
>
> **Presenter**: [Yi Li](https://ctml.berkeley.edu/people/yi-li)
>
> **Reading**: [Jordan, Kinderlehrer & Otto (1998)](https://francahoffmann.com/wp-content/uploads/2018/07/302ca7465ae824f3d2d629bfeaacfb56b4b8.pdf) Sections 1-2, 4-5
>
> **Optional Reading**: Villani (2021) Sections 8.4-8.5; Ambrosio, Gigli & Savaré (2008) Definition 3.1.1
*   Fokker-Planck equation: unique stationary solution as the steepest descending direction
*   Gradient flows, JKO scheme, and minimimizing movement
*   L1-weak convergence of interpolated JKO process to the solution of Fokker-Planck equation
*   Connections between Wasserstein gradient flows and Benamou-Brenier formulation


## [Continuity Equation in the Sense of Distributions (1)]
> **Date**: November 27th, 2024
>
> **Presenter**: Mingxun Wang
>
> **Reading**: Ambrosio, Gigli & Savaré (2008) Section 8.1
>
> **Optional Reading**: Ambrosio, Gigli & Savaré (2008) Sections 1.1, 10.0-10.1; [Continuity Equation and Benamou-Brenier Formulation](./notes/Michael_continuity_equation_and_BB_formulation.pdf); [Divergence Theorem](./notes/Michael_Gauss_divergence_theorem.pdf); [Gradient Flows](./notes/Michael_gradient_flow.pdf); [Brenier ODE](./notes/Michael_Brenier_ODE.pdf)
*   Divergence theorem
*   Bounded variation, rectifiable curve, geodesic, metric derivative, and arc-length reparameterization
*   Distribution: integration by parts, test function, local integrability
*   Weak derivative and Sobolev space
*   Continuity equation and weak solution


## [Gradient Flows]
> **Date**: December 4th, 2024
>
> **Presenter**: Kaiwen Hou
>
> **Reading**: Ambrosio, Gigli & Savaré (2008) Sections 8.3-8.4, 11.1
>
> **Optional Reading**: Ambrosio, Gigli & Savaré (2008) Example 11.1.10, Definitions 5.1.11, 10.1.1, Theorem 8.3.1, Lemma 10.4.1
*   Quantum drift-diffusion equation as gradient flow of the Fisher information
*   Four approaches to Wasserstein gradient flows: variational approximation scheme, curves of maximal slope, pointwise differential formulation, and systems of evolution variational inequalities
*   Duality map: Fréchet differential of Lp norm, compatibility with norm, and compatibility with inner product
*   Tangent bundle and smooth cylindrical test functions
*   Gradient flow equation: Fréchet subdifferential in Wasserstein space and differential inclusion
*   Variational integral lemma: strong subdifferential is the gradient of first variation
*   Gradient flow example: evolutionary parabolic PDEs of diffusion type


# Spring 2025: Geometry of Probability Space Optimization
In Spring 2025, participants further investigate the geometry of probability spaces and the implications for TMLE’s structure and behavior. Topics include deeper explorations of how optimal transport’s spatial and dynamic properties provide insights into likelihood-based optimization and its role in semiparametric models. Rather than diving into specific optimization techniques like natural gradient descent or Newton’s method, this semester focuses on laying the theoretical groundwork for understanding such methods in probability spaces. Participants refine their understanding of how probability space-based optimization differs fundamentally from traditional parameter space approaches. This exploration highlights the theoretical richness of TMLE’s operations in probability space and prepares participants to extend these ideas to advanced methods and practical implementations in their future work.

## [Benamou-Brenier Formulation (2)]
> **Date**: January 24th, 2025
>
> **Presenter**: [Qiuran Lyu](https://lqrrrrr.github.io/)
>
> **Computational Reading**: [Peyré & Cuturi (2019)](https://arxiv.org/pdf/1803.00567) Sections 7.1, 7.6, Remark 2.30
>
> **Optional Reading**: [Benamou & Brenier (2000)](https://link.springer.com/article/10.1007/s002110050002)
*   Convex formulation using momentum
*   Connections with displacement interpolation
*   Dynamic formulation over the paths space: displacement interpolation and entropic interpolation


## [Continuity Equation in the Sense of Distributions (2)]
> **Date**: January 31st, 2025
>
> **Presenter**: Kaiwen Hou
>
> **Theoretical Reading**: Ambrosio, Gigli & Savaré (2008) Theorem 8.3.1, Lemma 8.3.2, Proposition 8.3.3
*   Distributions in duality with smooth cylindrical test functions
*   Tangent vector field as the velocity field with smallest Lp norm and equal to the metric derivative


## [Tangent Space (1)]
> **Date**: February 7th, 2025
>
> **Presenter**: 
>
> **Theoretical Reading**: Ambrosio, Gigli & Savaré (2008) Section 8.0, Equations 0.20-0.26, Definition 8.4.1, Lemma 8.4.2, Propositions 8.4.3, 8.4.5, 8.4.6
*   Tangent bundle of 2-Wasserstein space
*   General definition of tangent bundle of Wasserstein space
*   Variational selection of tangent vectors
*   Variational characterization of divergence-free vector fields
*   Tangent vector to absolutely continuous curves
*   Optimal transport plans along absolutely continuous curves


## [Tangent Space (2)]
> **Date**: February 14th, 2025
>
> **Presenter**: 
>
> **Theoretical Reading**: Ambrosio, Gigli & Savaré (2008) Remark 8.4.4, Section 8.5
*   Cotangent space and duality
*   Tangent space constructed from optimal maps
*   Optimal displacement maps are tangent


## [Geodesic Convexity (1)]
> **Date**: February 21st, 2025
>
> **Presenter**: 
>
> **Computational Reading**: [Peyré & Cuturi (2019)](https://arxiv.org/pdf/1803.00567) Remarks 9.10, 9.13
>
> **Theoretical Reading**: Ambrosio, Gigli & Savaré (2008) Section 9.0-9.2
*   Geodesically convex functionals
*   Squared 2-Wasserstein distance function is not convex along geodesics
*   Convexity along generalized geodesics


## [Otto Calculus]
> **Date**: February 28th, 2025
>
> **Presenter**: [Yi Li](https://ctml.berkeley.edu/people/yi-li)
>
> **Theoretical Reading**: Villani (2009) Formulas 15.2, 15.7
*   Gradient formula in Wasserstein space
*   Hessian formula in Wasserstein space


## [Subdifferential Calculus (1)]
> **Date**: March 7th, 2025
>
> **Presenter**: [Wenxin Zhang](https://ctml.berkeley.edu/people/wenxin-zhang)
>
> **Theoretical Reading**: Ambrosio, Gigli & Savaré (2008) Sections 10.1-10.3


## [Subdifferential Calculus (2)]
> **Date**: March 14th, 2025
>
> **Presenter**: [Wenxin Zhang](https://ctml.berkeley.edu/people/wenxin-zhang)
>
> **Theoretical Reading**: Ambrosio, Gigli & Savaré (2008) Section 10.4


## [Monge–Ampère Equation]
> **Date**: March 21th, 2025
>
> **Presenter**: Kaiwen Hou
>
> **Reading**: 


## [Linearization of the Optimal Transport Problem]
> **Date**: 
>
> **Presenter**: 
>
> **Reading**: 


## [Second Variation]
> **Date**: April 4th, 2025
>
> **Presenter**: 
>
> **Reading**: 


## [Hessians and Convexity]
> **Date**: April 11th, 2025
>
> **Presenter**: 
>
> **Reading**: 


## [Examples of Functionals with Known Hessians]
> **Date**: April 18th, 2025
>
> **Presenter**: 
>
> **Reading**: 


## [Regularity Theory from Hessians]
> **Date**: April 25th, 2025
>
> **Presenter**: 
>
> **Reading**: 


## [Geodesic Convexity (2)]
> **Date**: **April 30th, 2025**
>
> **Presenter**: 
>
> **Reading**: 


## [Spectral Analysis]
> **Date**: 
>
> **Presenter**: 
>
> **Reading**: 




Join us on [Zoom](https://berkeley.zoom.us/j/91970465738) if you can’t attend in person, and don't forget to subscribe to [this channel](https://kaltura.berkeley.edu/channel/CTML+Channel/358899692/subscribe) for access to the recordings.

---
number: 7
title: Equilibrium Computation and Machine Learning
datetime:
    start: 2021-11-10T16:15:00
    end: 2021-11-10T18:00:00
lecturer: 
    - name: Constantinos Daskalakis
      link: http://people.csail.mit.edu/costis/
      affiliation: MIT
material:
    name: Slides
    url: /slides/lecture-07.pdf
references:
    - "Daskalakis, C. et al. (2018). *Training GANs with Optimism.* [arXiv:1711.00141](https://arxiv.org/abs/1711.00141). **[Pages 1–10].**"
    - "Daskalakis, C. et al. (2020). *The Complexity of Constrained Min-Max Optimization.* [arXiv:2009.09623](https://arxiv.org/abs/2009.09623). **[Pages 1–8; optional!].**"
    - "Daskalakis, C. et al. (2021). *Near-Optimal No-Regret Learning in General Games.* [arXiv:2108.06924](https://arxiv.org/abs/2108.06924). **[Optional!]**"
math: false
---

Machine learning has recently made significant advances in single-agent learning challenges, much of that progress being fueled by the empirical success of gradient descent-based methods in computing local optima of non-convex optimization problems. 
In multi-agent learning challenges, the role of single-objective optimization is played by equilibrium computation. 
On this front, however, optimization methods have remained less successful in settings, such as adversarial training and multi-agent reinforcement learning, motivated by deep learning applications.
Gradient-descent based methods commonly fail to identify equilibria, and even computing local approximate equilibria has remained daunting. 
We discuss equilibrium computation challenges motivated by machine learning applications through a combination of learning-theoretic, complexity-theoretic, game-theoretic and topological techniques, presenting obstacles and opportunities for machine learning and game theory going forward. 
No deep learning / complexity theory knowledge will be assumed for this talk.

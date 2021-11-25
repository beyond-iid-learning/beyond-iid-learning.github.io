---
number: 9
title: Symbolic regression and equation learning for identifying sparse non‑linear models
datetime:
    start: 2021-11-24T16:15:00
    end: 2021-11-24T18:00:00
lecturer: 
    - name: Georg Martius
      link: https://www.is.mpg.de/person/gmartius
      affiliation: MPI-IS
references:
    - "Sahoo, S. et al. (2018). *Learning Equations for Extrapolation and Control*. [arXiv:1806.07259](https://arxiv.org/abs/1806.07259)."
    - "Biggio, L. et al. (2021). *Neural Symbolic Regression that Scales*. [arXiv:2106.06427](https://arxiv.org/abs/2106.06427). **[Optional]**"
    - "Project website: [Equation Learner for Extrapolation and Control](https://al.is.mpg.de/research_projects/equation-learner) **[Optional]**"
material:
    name: Slides
    url: /slides/lecture-09.pdf
recording:
    url: https://video.ethz.ch/lectures/d-infk/2021/autumn/263-5156-00L/ae8e001a-771b-440b-a581-24f157ad89e7.html
math: false
---

In classical machine learning, regression is treated as a black box process of identifying a suitable function without attempting to gain insight into the mechanism connecting inputs and outputs. 
In the natural sciences, however, finding an interpretable function for a phenomenon is the prime goal as it allows to understand and generalize results.
Following the theme of the lecture by Nathan Kutz, we will consider the search for parsimonious models. 
In this lecture we will consider non-linear models represented by concise analytical expressions. 
The problem of finding such expressions is generally called symbolic regression. 
Traditionally, this problem is solved with evolutionary search. 
In recent years, machine learning methods have been proposed for this task. One of the first works in this direction was the "equation learner" (EQL), which I will cover in some detail. 
Very recently, a different approach was presented that uses pretraining and language models to predict likely equations (NeSymReS). 
I will also talk about this method and compare them.
An interesting aspect of the search for the most compact description of data is its connection to causal models and the identification of the true underlying relationships. 
In general, prior knowledge is required to make this work, but if successful, we can enjoy great generalization capabilities.

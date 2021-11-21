---
number: 8
title: Deep learning for the discovery of parsimonious physics models
datetime:
    start: 2021-11-17T16:15:00
    end: 2021-11-17T18:00:00
lecturer: 
    - name: Nathan Kutz
      link: http://faculty.washington.edu/kutz/
      affiliation: University of Washington
material:
    name: Slides
    url: /slides/lecture-08.pdf
recording:
    url: https://video.ethz.ch/lectures/d-infk/2021/autumn/263-5156-00L/7cb2fe86-fd0f-4c22-9e71-7077da7000dc.html
references:
    - "Champion, K. et al. (2019). *Data-driven discovery of coordinates and governing equations.* Proceedings of the National Academy of Sciences, 116(45), 22445–22451. [DOI:10.1073/pnas.1906995116](https://www.pnas.org/content/116/45/22445)."
math: false
---

A major challenge in the study of dynamical systems is that of model discovery: turning data into reduced order models that are not just predictive, but provide insight into the nature of the underlying dynamical system that generated the data. 
We introduce a number of data-driven strategies for discovering nonlinear multiscale dynamical systems and their embeddings from data. 
We consider two canonical cases: 
(i) systems for which we have full measurements of the governing variables, and 
(ii) systems for which we have incomplete measurements. 
For systems with full state measurements, we show that the recent sparse identification of nonlinear dynamical systems (SINDy) method can discover governing equations with relatively little data and introduce a sampling method that allows SINDy to scale efficiently to problems with multiple time scales, noise and parametric dependencies.
For systems with incomplete observations, we show that the Hankel alternative view of Koopman (HAVOK) method, based on time-delay embedding coordinates and the dynamic mode decomposition, can be used to obtain a linear models and Koopman invariant measurement systems that nearly perfectly captures the dynamics of nonlinear quasiperiodic systems. 
Neural networks are used in targeted ways to aid in the model reduction process. 
Together, these approaches provide a suite of mathematical strategies for reducing the data required to discover and model nonlinear multiscale systems.

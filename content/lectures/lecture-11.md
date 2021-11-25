---
number: 11
title: Learning Under Algorithmic Triage
datetime:
    start: 2021-12-08T16:15:00
    end: 2021-12-08T18:00:00
lecturer: 
    - name: Manuel Gomez Rodriguez
      link: https://people.mpi-sws.org/~manuelgr/
      affiliation: MPI-SWS
references:
    - "Okati, N. et al. (2021): *Differentiable Learning Under Triage*. [arXiv:2103.08902](https://arxiv.org/abs/2103.08902)."
math: false
---

Under algorithmic triage, a machine learning model does not predict all instances but instead defers some of them to human experts. 
The motivation that underpins learning under algorithmic triage is the observation that, while there are high-stake tasks where machine learning models have matched, or even surpassed, the average performance of human experts, they are still less accurate than human experts on some instances, where they make far more errors than average. 
The main promise is that, by working together, human experts and machine learning models are likely to achieve a considerably better performance than each of them would achieve on their own. 
In this talk, I will present several algorithms to learn under algorithmic triage that we have developed in recent years, discuss their theoretical properties, and present a variety of experimental results demonstrating their potential in improving medical diagnosis, content moderation and scientific discovery.
---
number: 10
title: Causal insights from merging data sets and merging data sets via causal insights
datetime:
    start: 2021-12-01T16:15:00
    end: 2021-12-01T18:00:00
lecturer: 
    - name: Dominik Janzing
      link: https://janzing.github.io/
      affiliation: Amazon
references:
    - "Janzing, D. (2018): *Merging joint distributions via causal model classes with low VC dimension*. [arXiv:1804.03206](https://arxiv.org/abs/1804.03206)."
    - "Garrido Mejia, S. et al. (2021): *Obtaining causal information by merging data sets with MaxEnt.* [arXiv:2107.07640](https://arxiv.org/abs/2107.07640). **[optional]**"
    - "Janzing, D. (2021): *Causal versions of Maximum Entropy and Principle of Insufficient Reason* [arXiv:2102.03906](https://arxiv.org/abs/2102.03906). **[optional]**"
math: false
---

While humans often draw causal conclusions from putting observations into the broader context of causal knowledge, AI still needs to develop these techniques. 
I show how causal insights can be obtained from the synergy of datasets referring to different sets of variables and argue that causal hypotheses then predict joint properties of variables that have never been observed together. 
This way, causal discovery becomes a prediction task in which additional variable sets play the role of additional data points in traditional iid learning. 
For instance, a causal DAG can be seen as a binary classifier that tells us which conditional independences are valid, which then enables a statistical learning theory for learning DAGs.
I describe "Causal MaxEnt" (a modified version of MaxEnt that is asymmetric with respect to causal directions) as one potential approach to infer DAGs and properties of the joint distribution from a set of marginal distributions of subsets of variables and derive causal conclusions for toy examples. 

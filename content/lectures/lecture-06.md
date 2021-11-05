---
number: 6
title: Developing Counterfactual Explanations
datetime:
    start: 2021-11-03T16:15:00
    end: 2021-11-03T18:00:00
lecturer: 
    - name: Chris Russell
      link: https://scholar.google.com/citations?user=RM2sHhYAAAAJ&hl=en
      affiliation: Amazon
recording:
    url: https://video.ethz.ch/lectures/d-infk/2021/autumn/263-5156-00L/97738414-971b-409e-a72a-9c1fafb5a978.html
references:
    - "Wachter, S., et al. (2018). *Counterfactual explanations without opening the black box: automated decisions and the GDPR.* Harvard Journal of Law & Technology, 31(2). [Available online.](https://jolt.law.harvard.edu/assets/articlePDFs/v31/Counterfactual-Explanations-without-Opening-the-Black-Box-Sandra-Wachter-et-al.pdf) **[Chapters I–IV]**"
    - "Elliott, A. et al. (2021). *Explaining Classifiers using Adversarial Perturbations on the Perceptual Ball.* [Available online.](https://openaccess.thecvf.com/content/CVPR2021/papers/Elliott_Explaining_Classifiers_Using_Adversarial_Perturbations_on_the_Perceptual_Ball_CVPR_2021_paper.pdf)"
math: false
---

Counterfactual Explanations are a relatively recent form of explanation designed to explicitly meet the needs of non-technical users.
Unlike methods such as Shapley values that providing measures of the relative importance of features, counterfactual explanations offer simple direct explanations of the form:
You were not offered a loan because your salary was <span>$</span>30k, if it had been <span>$</span>45k instead, you would have been offered the loan.
These forms of explanation are very popular in legal and governance areas of AI, and are cited in the guidelines to the GDPR.
We will discuss the development of counterfactuals explanations, including why previous forms of explanation are often unsuitable for end-users, and the limitations of counterfactual explanations, and what they can and can not tell you, and the challenges of extending them to high-dimensional problems in computer vision.
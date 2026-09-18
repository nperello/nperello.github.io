---
title: "Marrying Fairness and Explainability in Supervised Learning"
collection: publications
permalink: /publication/facct2022
excerpt: ""
description: "FAccT 2022 paper formalizing direct and induced discrimination causally and proposing post-processing methods that nullify the protected attribute's influence."
date: 2022-04-04
venue: 'ACM Conference on Fairness, Accountability, and Transparency'
paperurl: https://dl.acm.org/doi/10.1145/3531146.3533236
pubtype : 'archival'
citation: 'Przemyslaw A. Grabowicz, Nicholas Perello, and Aarshee Mishra. Marrying Fairness and Explainability in Supervised Learning. In ACM Conference on Fairness, Accountability, and Transparency (ACM FAccT), 2022.'
---

## Abstract

Machine learning algorithms that aid human decision-making may inadvertently discriminate against certain protected groups. We formalize direct discrimination as a direct causal effect of the protected attributes on the decisions, while induced discrimination as a change in the causal influence of non-protected features associated with the protected attributes. The measurements of marginal direct effect (MDE) and SHapley Additive exPlanations (SHAP) reveal that state-of-the-art fair learning methods can induce discrimination via association or reverse discrimination in synthetic and real-world datasets. To inhibit discrimination in algorithmic systems, we propose to nullify the influence of the protected attribute on the output of the system, while preserving the influence of remaining features. We introduce and study post-processing methods achieving such objectives, finding that they yield relatively high model accuracy, prevent direct discrimination, and diminishes various disparity measures, e.g., demographic disparity.

## Links

- [ACM Digital Library (DOI)](https://dl.acm.org/doi/10.1145/3531146.3533236)
- [PDF (FAccT 2022 proceedings)](https://facctconference.org/static/pdfs_2022/facct22-3533236.pdf)
- [arXiv](https://arxiv.org/abs/2204.02947)

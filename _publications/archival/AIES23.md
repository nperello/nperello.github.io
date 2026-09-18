---
title: "Learning from Discriminatory Training Data"
collection: publications
permalink: /publication/AIES23
excerpt: ""
description: "AIES 2023 paper proposing a fair learning method that provably minimizes error on fair datasets while training on data poisoned with direct discrimination."
date: 2023-03-03
venue: 'AAAI/ACM Conference on Artificial Intelligence, Ethics, and Society'
paperurl: https://dl.acm.org/doi/10.1145/3600211.3604710
pubtype : 'archival'
citation: 'Przemyslaw A. Grabowicz*, Nicholas Perello*, and Kenta Takatsu. Learning from Discriminatory Training Data. In AAAI/ACM Conference on Artificial Intelligence, Ethics, and Society (AIES), 2023'
---

## Abstract

Supervised learning systems are trained using historical data and, if the data was tainted by discrimination, they may unintentionally learn to discriminate against protected groups. We propose that fair learning methods, despite training on potentially discriminatory datasets, shall perform well on fair test datasets. Such dataset shifts crystallize application scenarios for specific fair learning methods. For instance, the removal of direct discrimination can be represented as a particular dataset shift problem. For this scenario, we propose a learning method that provably minimizes model error on fair datasets, while blindly training on datasets poisoned with direct additive discrimination. The method is compatible with existing legal systems and provides a solution to the widely discussed issue of protected groups' intersectionality by striking a balance between the protected groups. Technically, the method applies probabilistic interventions, has causal and counterfactual formulations, and is computationally lightweight: it can be used with any supervised learning model to prevent direct and indirect discrimination via proxies while maximizing model accuracy for business necessity.

## Links

- [ACM Digital Library (DOI)](https://dl.acm.org/doi/10.1145/3600211.3604710)
- [arXiv](https://arxiv.org/abs/1912.08189)

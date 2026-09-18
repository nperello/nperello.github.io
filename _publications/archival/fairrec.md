---
title: "Discrimination Induced by Algorithmic Recourse Objectives"
collection: publications
permalink: /publication/fairrecourse
excerpt: ""
description: "FAccT 2025 paper introducing induced discrimination in algorithmic recourse and a welfare-based recourse method that is robust across recourse objectives."
date: 2025-07-07
venue: 'ACM Conference on Fairness, Accountability, and Transparency'
paperurl: https://doi.org/10.1145/3715275.3732110
pubtype : 'archival'
citation: 'Nicholas Perello, Cyrus Cousins, Yair Zick, Przemyslaw A. Grabowicz. Discrimination Induced by Algorithmic Recourse Objectives. In ACM Conference on Fairness, Accountability, and Transparency (ACM FAccT), 2025.'
---

## Abstract

We study fairness in algorithmic recourse, which provides users who receive undesirable outcomes from decision-making systems with explanations on how to achieve their desired results. To produce explanations that emulate real-world settings and preferences, the literature proposes various constraints, e.g., sparsity, on the objective of recourse methods. We argue that these constrained objectives can induce disparate recourse costs between protected groups, especially when groups' recourse objectives differ from the objectives of the methods providing them recourse. We formalize discrimination in algorithmic recourse with respect to legal notions and the cost of recourse. Namely, we introduce a novel notion of induced discrimination that captures the excess cost of recourse induced by having misaligned objectives between groups and methods. Using this definition, we show that recourse objectives can induce discriminatory recourse, independent from the bias of the model being explained. To inhibit discrimination, we extend prior work on welfare-based group-fair supervised learning to measure group welfare under multiple recourse objectives. We then propose a recourse method that maximizes group welfare and empirically show its robust performance over multiple recourse objectives.

## Links

- [ACM Digital Library (DOI)](https://doi.org/10.1145/3715275.3732110)
- [PDF (FAccT 2025 proceedings)](https://facctconference.org/static/docs/facct2025-206archivalpdfs/facct2025-final613-acmpaginated.pdf)

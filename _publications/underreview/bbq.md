---
title: "Grilling BBQ: The Limits of Bias Benchmarking in LLM Safety Reporting"
collection: publications
permalink: /publication/bbq
excerpt: ""
description: "Under review, 2026. An audit showing how BBQ's scoring and reporting conventions hide selective abstention and group-concentrated stereotyping in safety-trained LLMs."
date: 2026-09-01
venue: 'Under review'
paperurl:
pubtype : 'underreview'
citation: 'Nicholas Perello, Przemyslaw A. Grabowicz, Yair Zick. Grilling BBQ: The Limits of Bias Benchmarking in LLM Safety Reporting. Under review, 2026.'
---

## Abstract

The Bias Benchmark for Question Answering (BBQ) is among the most widely adopted bias evaluations for large language models, e.g., it is the primary bias benchmark in both Anthropic's system cards and Stanford's HELM Safety framework. However, its scoring and reporting conventions have two structural blind spots for safety-trained LLMs: the bias score is invariant to "unknown" responses on questions the context fully answers, so a model that selectively abstains on specific demographic groups can score zero bias, and aggregation masks stereotyping concentrated on individual groups. Auditing three LLMs from three labs on all 58,492 examples, we find near-zero bias scores coexisting with template-concentrated abstention spreads of up to 47% points and stereotyping rates over 40% on groups whose aggregate scores stay near zero. Controlled prompt variants identify three triggers behind the elevated abstention and reveal a same-race pair comparison gap, strongest on an affirmative-action question. An audit of two newer models from one of these labs, both of whose cards report abstention-driven accuracy drops, finds one model near its card score under our setup and the other scores 16% points above it, a gap that cannot be resolved while the cards leave their evaluation setup unpublished. We propose disaggregated, abstention-aware measures, all but one computable from existing BBQ outputs, and reporting practices that would surface these failures.

This paper is currently under review. The preprint is available on request.

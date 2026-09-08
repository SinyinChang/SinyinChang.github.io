---
title: "I-CALM: Incentivizing Confidence-Aware Abstention for LLM Hallucination Mitigation"
collection: publications
permalink: /publication/20260405-ICML-ICALM
date: 2026-04-05
venue: 'Epistemic Intelligence in Machine Learning Workshop, co-located with ICML 2026'
paperurl: 'https://arxiv.org/pdf/2604.03904'
citation: 'Haotian Zong, Binze Li, Yufei Long, <b><u>Sinyin Chang</u></b>, Jialong Wu, Gillian K Hadfield. I-CALM: Incentivizing Confidence-Aware Abstention for LLM Hallucination Mitigation. Epistemic Intelligence in Machine Learning Workshop, co-located with ICML 2026'
---
## Abstract

Large language models (LLMs) often produce confident but incorrect answers, in part because standard evaluation incentives reward guessing over expressing uncertainty. We study epistemic abstention for factual questions with verifiable answers, where the goal is to improve selective answering, making LLMs abstain when they are likely to be wrong while preserving correct answers. Inspired by human behavioral decisions in question answering, we introduce I-CALM, a prompt-level framework for black-box LLMs. I-CALM combines elicited verbal confidence, announced answer/abstain payoffs, and normative guidance emphasizing truthfulness, humility, evidential support, and responsibility. To distinguish targeted abstention from indiscriminate refusal, we use a two-stage evaluation protocol, in which LLMs first choose whether to answer or abstain, and are then forced to provide a best guess for the abstained ones. Across models and factual QA datasets, I-CALM improves selective answering by reducing false-answer rate among surfaced responses and improving abstention quality, shifting error-prone cases into abstention while retaining answers the model would have answered correctly. Overall, I-CALM offers a lightweight way to improve inference-time selective answering without retraining or access to model’s internal states. 

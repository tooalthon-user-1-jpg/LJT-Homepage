---
title: 'On the Universal Truthfulness Hyperplane Inside LLMs'
venue: 'EMNLP 2024'
date: 2024-01-01
category: 'conference'
permalink: /publication/universal_truthfulness_hyperplane
link: 'https://arxiv.org/abs/2402.03023'
excerpt: 'We investigate the internal representations of LLMs and discover a universal truthfulness hyperplane that spans across different model architectures. This hyperplane provides a geometric framework for understanding and mitigating hallucinations in large language models.'
pubnotes: 'First author'
---

We investigate the internal representations of LLMs and discover a universal truthfulness hyperplane that spans across different model architectures. This hyperplane provides a geometric framework for understanding and mitigating hallucinations in large language models.

{% include figure.html path="assets/img/teaser_truthfulness_hyperplane.png" link="https://github.com/" caption="Universal truthfulness hyperplane in LLM representations." %}

### Abstract

Hallucinations remain a significant challenge in large language models. We propose a geometric framework for understanding truthfulness in LLMs by identifying a universal truthfulness hyperplane within their internal representations. Our analysis reveals that this hyperplane consistently separates truthful from hallucinated outputs across different model architectures and task types. Based on this insight, we develop a simple yet effective intervention method that projects representations toward the truthfulness hyperplane, significantly reducing hallucinations.

### Authors

Junteng Liu, Shiqi Chen, Yu Cheng, Junxian He

### Code

The code repository for this work is available as Universal_Truthfulness_Hyperplane.

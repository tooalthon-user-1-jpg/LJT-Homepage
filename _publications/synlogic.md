---
title: 'SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond'
venue: 'ArXiv'
date: 2025-01-01
category: 'conference'
permalink: /publication/synlogic
link: 'https://arxiv.org/abs/2501.00023'
excerpt: 'We introduce SynLogic, a data synthesis framework for training verifiable reasoning models at scale. Our method automatically generates step-by-step reasoning traces with intermediate verification, enabling large-scale training of models capable of complex logical reasoning tasks.'
pubnotes: 'First author'
---

We introduce SynLogic, a data synthesis framework for training verifiable reasoning models at scale. Our method automatically generates step-by-step reasoning traces with intermediate verification, enabling large-scale training of models capable of complex logical reasoning tasks.

{% include figure.html path="assets/img/teaser_synlogic.png" link="https://github.com/" caption="Overview of SynLogic framework. We synthesize verifiable reasoning data at scale using LLMs to train models for complex logical reasoning." %}

### Abstract

Large language models (LLMs) have demonstrated remarkable capabilities in complex reasoning tasks, yet they often struggle with verifiability and correctness. We present SynLogic, a novel data synthesis framework that automatically generates high-quality, verifiable reasoning traces at scale. Our approach leverages chain-of-thought prompting with intermediate verification steps, ensuring each reasoning step can be independently checked for correctness. We evaluate our framework on a comprehensive suite of logical reasoning benchmarks, showing substantial improvements over existing methods.

### Authors

Junteng Liu, Yuanxiang Fan, Zhuo Jiang, Han Ding, Yongyi Hu, Chi Zhang, Yiqi Shi, Shitong Weng, Aili Chen, Shiqi Chen, Yunan Huang, Mozhi Zhang, Pengyu Zhao, Junjie Yan, Junxian He

### Code

The code repository for SynLogic is available on GitHub.

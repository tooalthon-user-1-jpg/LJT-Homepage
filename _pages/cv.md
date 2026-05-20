---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**Ph.D. in Computer Science** (2024 – Present)
- Hong Kong University of Science and Technology (HKUST)
- HKUST NLP Group
- Advisor: Professor Junxian He

**B.Eng.** (2020 – 2024)
- Shanghai Jiao Tong University (SJTU)
- Graduated in June 2024
- Received the Zhiyuan Honor Scholarship

## Research Experience

**Research Intern**, MINIMAX (February 2025 – Present)

**Research Intern**, Tencent WXG (June 2024 – September 2024)

**Research Intern**, Shanghai AI Lab (June 2023 – December 2023)

## Skills

- **Natural Language Processing**: Large Language Models, Transformer Architectures, LLM Reasoning, Reinforcement Learning
- **Machine Learning**: LLM Training, Parameter-Efficient Learning, Hallucination Mitigation, Model Interpretability
- **Vision-Language Models**: Chart Understanding, Perception Analysis, VLM Evaluation

## Languages

- **English**: Proficient
- **Chinese**: Native

## Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models
- LLM Truthfulness and Interpretability

## Publications

<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

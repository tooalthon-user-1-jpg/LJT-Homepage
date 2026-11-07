---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology (HKUST). I graduated from Shanghai Jiao Tong University (SJTU) in June 2024 with a B.Eng. My research focuses on natural language processing and machine learning.

## Academic Background

- **Ph.D. in Computer Science (2024-Present)** — Hong Kong University of Science and Technology (HKUST), supervised by Professor Junxian He.
- **B.Eng. (2020-2024)** — Shanghai Jiao Tong University (SJTU).
- Received the Zhiyuan Honor Scholarship at Shanghai Jiao Tong University.

## Research Experience

- **Research Intern at MINIMAX** (February 2025 - Present)
- **Research Intern at Tencent WXG** (June 2024 - September 2024), advised by Zifei Shan.
- **Research Intern at Shanghai AI Lab** (June 2023 - December 2023), advised by Prof. Yu Cheng.

## Research Interests

- Natural Language Processing
- Machine Learning
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM truthfulness and Interpretability

## Publications

{% assign publications = site.publications | sort: "date" | reverse %}
{% for post in publications %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y" }}). Published in {{ post.venue }}.
{% endfor %}

## Contact

- Email: jliugi@connect.ust.hk
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Google Scholar Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

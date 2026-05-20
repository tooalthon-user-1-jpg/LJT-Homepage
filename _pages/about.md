---
permalink: /
title: "Junteng Liu - Personal Website"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello! I'm **Junteng Liu**, a first-year PhD candidate at the [HKUST NLP Group](https://www.cse.ust.hk/pg/?page=research&id=384), supervised by [Professor Junxian He](https://omegazhang.github.io/). I graduated from [Shanghai Jiao Tong University (SJTU)](https://en.wikipedia.org/wiki/Shanghai_Jiao_Tong_University) in June 2024 with a Bachelor of Engineering.

My research focuses on **Natural Language Processing** and **Machine Learning**, with specific interests in:

- **LLM Reasoning and Reinforcement Learning**
- **Hallucination in Vision-Language Models (VLM)**
- **LLM Truthfulness and Interpretability**

## Academic Background

- **Ph.D. in Computer Science** (2024–Present)
  - Hong Kong University of Science and Technology (HKUST)
  - Advisor: Professor Junxian He

- **B.Eng.** (2020–2024)
  - Shanghai Jiao Tong University (SJTU)
  - Graduated in June 2024
  - Received the Zhiyuan Honor Scholarship

## Research Experience

- **Research Intern**, MINIMAX (February 2025 – Present)
- **Research Intern**, Tencent WXG (June 2024 – September 2024)
- **Research Intern**, Shanghai AI Lab (June 2023 – December 2023)

## Publications

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% assign all = post %}
  {% include archive-single.html %}
{% endfor %}

## Contact

- **Email**: jliugi@connect.ust.hk
- **GitHub**: [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar**: [Junteng Liu](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter)**: [@junteng88716710](https://twitter.com/junteng88716710)

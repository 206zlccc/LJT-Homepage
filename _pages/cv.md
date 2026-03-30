---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Junteng Liu**  
Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk) | GitHub: [Vicent0205](https://github.com/Vicent0205)

---

## Education

### Ph.D. in Computer Science (2024 - Present)
**Hong Kong University of Science and Technology (HKUST)**  
*Supervisor: Prof. Junxian He*  
HKUST NLP Group

### Bachelor of Engineering (2020 - 2024)
**Shanghai Jiao Tong University (SJTU)**  
*Graduated in June 2024*  
*Received Zhiyuan Honor Scholarship*

---

## Research Experience

### Research Intern (February 2025 - Present)
**MINIMAX**  
*Researching LLM Reasoning and Reinforcement Learning*

### Research Intern (June 2024 - September 2024)
**Tencent WXG**  
*Advisor: Zifei Shan*  
*Researching VLM hallucination mitigation*

### Research Intern (June 2023 - December 2023)
**Shanghai AI Lab**  
*Advisor: Prof. Yu Cheng*  
*Researching C-Eval: A Multi-Level Multi-Discipline Chinese Evaluation Suite for Foundation Models*

---

## Skills

- **Natural Language Processing**: LLM, NLP, Machine Learning, Transformer, VLM
- **Deep Learning**: PyTorch, TensorFlow, Hugging Face, PEFT
- **Programming Languages**: Python, C++, Bash, LaTeX
- **Research Skills**: Experimental Design, Data Analysis, Paper Writing, Reproducible Research

---

## Languages

- **Chinese**: Native
- **English**: Professional

---

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

---

## Selected Awards

- **Zhiyuan Honor Scholarship** - Shanghai Jiao Tong University

---

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

---

## Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}

---

## Teaching

{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
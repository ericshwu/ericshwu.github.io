---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a first year Ph.D. student at Gaoling School of Artificial Intelligence in Renmin University of China, supervised by Prof. Yankai Lin. 
My research interests focus on foundation language models pre-training, particularly Mixture-of-Experts (MoE).

# News within this year
- *2026.04*: Two papers are accpeted by ACL 2026.
- *2025.09*: One paper is accepted by NeurIPS 2025.
- *2025.06*: I am selected by 2025 CCF-Tencent Rhino-Bird Elite Talent Program, mentored by [Ruobing Xie](https://ruobingxie.github.io/).
- *2025.05*: One paper is accepted by ICML 2025.

# Publications
## Foundation Language Models
- Union-of-Experts: Neurons in Mixture-of-Experts are Secretly Routers. **Songhao Wu** et al.
- PEAR: Position-Embedding-Agnostic Attention Re-weighting Enhances Retrieval-Augmented Generation with Zero Inference Overhead. <br> Tao Tan\*, Yining Qian\* and Ang Lv\* et al. Proceedings of the ACM on Web Conference 2025, *(WWW'25 Oral)*.
- Autonomy-of-Experts Models. Ang Lv et al. Proceedings of the 42nd International Conference on Machine Learning, *(ICML’25)*.

## Efficient LLM
- PolarQuant: Leveraging Polar Transformation for Efficient Key Cache Quantization and Decoding Acceleration. <br> **Songhao Wu** and Ang Lv\* etal. Thirty-ninth Annual Conference on Neural Information Processing Systems, *(NeurIPS' 25).*

## Information Retrieval
- Bridge the Gap between Past and Future: Siamese Model Optimization for Context-Aware Document Ranking. <br> **Songhao Wu** et al. Proceedings of the 33rd ACM International Conference on Information and Knowledge Management, *(CIKM'24)*.
- Unify Graph Learning with Text: Unleashing LLM Potentials for Session Search. <br> **Songhao Wu** et al. Proceedings of the ACM on Web Conference 2024, *(WWW'24)*.

## Others
- From 1,000,000 Users to Every User: Scaling Up Personalized Preference for User-level Alignment. Jia-Nan Li et al.

# Academic Services
- Conference Reviewer: ICLR, ICML, ARR Reviewer

# Internships
- 2025.6- Now, Tencent Hunyuan, mentored by Ruobing Xie
- 2024.12 - 2025.5, Meituan
- 2023.9 - 2024.11, Ant Group

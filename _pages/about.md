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
- *2026.05*: One paper is accepted by KDD 2026.
- *2026.04*: Two papers are accpeted by ACL 2026.
- *2025.09*: One paper is accepted by NeurIPS 2025.
- *2025.06*: I am selected by 2025 CCF-Tencent Rhino-Bird Elite Talent Program, mentored by [Ruobing Xie](https://ruobingxie.github.io/).
- *2025.05*: One paper is accepted by ICML 2025.

# Publications & Preprint
## Foundation Language Models
- [Redesign Mixture-of-Experts Routers with Manifold Power Iteration.](https://arxiv.org/abs/2606.12397) **Songhao Wu** et al. *(Preprint)*
- Union-of-Experts: Neurons in Mixture-of-Experts are Secretly Routers. **Songhao Wu** et al.
- [Autonomy-of-Experts Models.](https://arxiv.org/html/2501.13074v1) Ang Lv et al. Proceedings of the 42nd International Conference on Machine Learning, *(ICML’25)*.
- [PEAR: Position-Embedding-Agnostic Attention Re-weighting Enhances Retrieval-Augmented Generation with Zero Inference Overhead.](https://arxiv.org/abs/2409.19745) <br> Tao Tan\*, Yining Qian\* and Ang Lv\* et al. Proceedings of the ACM on Web Conference 2025, *(WWW'25 Oral)*.

## Efficient LLM
- [PolarQuant: Leveraging Polar Transformation for Efficient Key Cache Quantization and Decoding Acceleration.](https://arxiv.org/abs/2502.00527) [![GitHub stars](https://img.shields.io/github/stars/ericshwu/PolarQuant?style=flat-square)](https://github.com/ericshwu/PolarQuant) <br>
**Songhao Wu** and Ang Lv\* etal. Thirty-ninth Annual Conference on Neural Information Processing Systems, *(NeurIPS' 25).*

## Information Retrieval
- [Your UnEmbedding Matrix is Secretly a Feature Lens for Text Embeddings.](https://arxiv.org/abs/2606.07502) [![GitHub stars](https://img.shields.io/github/stars/CentreChen/EmbFilter?style=flat-square)](https://github.com/CentreChen/EmbFilter) <br>
**Songhao Wu** and Zhongxin Chen et al.
- Bridge the Gap between Past and Future: Siamese Model Optimization for Context-Aware Document Ranking. <br> **Songhao Wu** et al. Proceedings of the 33rd ACM International Conference on Information and Knowledge Management, *(CIKM'24)*.
- Unify Graph Learning with Text: Unleashing LLM Potentials for Session Search. <br> **Songhao Wu** et al. Proceedings of the ACM on Web Conference 2024, *(WWW'24)*.

## Other Publications
- From 1,000,000 Users to Every User: Scaling Up Personalized Preference for User-level Alignment. Jia-Nan Li et al.

# Academic Services
- Conference Reviewer: ICML, NeurIPS, ICLR, ARR Reviewer

# Internships
- 2025.6- Now, Tencent Hunyuan, LLM Dept
- 2024.12 - 2025.5, Meituan
- 2023.9 - 2024.11, Ant Group

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

I am Hao Fang, a Master's graduate from the Institute of Automation, Chinese Academy of Sciences (CASIA), where I was supervised by Prof. Jun Wan and [Prof. Ziqiang Li](https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN) (IEEE Fellow).

My research interests include computer vision and multimodal large language models. Previously, I served as a Multimodal LLM Engineer Intern at Alibaba's AMAP (Gaode Maps). Currently, I work as an Advertising LLM Engineer at Meituan.

For academic collaborations, please feel free to contact me via email.

# 🔥 News

- *2026*: &nbsp; UniAttack: Unified Physical-Digital Face Attack Detection, *International Journal of Computer Vision* (**IJCV**).
- *2026*: &nbsp; HySpeFAS: A Hyperspectral Face Anti-Spoofing Dataset Based on Snapshot Compressive Imaging, *IEEE Transactions on Information Forensics and Security* (**TIFS**).
- *2025*: &nbsp; UBG: An Unreal BattleGround Benchmark With Object-Aware Hierarchical Proximal Policy Optimization, *IEEE Transactions on Neural Networks and Learning Systems* (**TNNLS**).
- *2024*: &nbsp; Unified Physical-Digital Face Attack Detection (**IJCAI**).
- *2024*: &nbsp; VL-FAS: Domain Generalization via Vision-Language Model for Face Anti-Spoofing, *IEEE International Conference on Acoustics, Speech and Signal Processing* (**ICASSP**).
- *2023*: &nbsp; Surveillance Face Anti-Spoofing, *IEEE Transactions on Information Forensics and Security* (**TIFS**).
- *2023*: &nbsp; Surveillance Face Presentation Attack Detection Challenge, *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops* (**CVPRW**).
- *2023*: &nbsp; Bandpass Filter Based Dual-Stream Network for Face Anti-Spoofing, *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (**CVPR**).

# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-text'>
    <div class='paper-box-image'>
      <img src='../images/papers/ReRec.png' alt='ReRec publication teaser'>
    </div>
    <div class='paper-title'>ReRec: Reasoning-Augmented LLM-based Recommendation Assistant via Reinforcement Fine-tuning</div>
    <div class='paper-authors'><strong>Jiani Huang</strong>, Shijie Wang, Liangbo Ning, Wenqi Fan, Qing Li</div>
    <div class='paper-venue'>ACL 2026</div>
    <div class='paper-summary'>With the rise of LLMs, there is an increasing need for intelligent recommendation assistants that can handle complex queries and provide personalized, reasoning-driven recommendations. LLM-based recommenders show potential but face challenges in multi-step reasoning, underscoring the need for reasoning-augmented systems. To address this gap, we propose ReRec, a novel reinforcement fine-tuning (RFT) framework designed to improve LLM reasoning in complex recommendation tasks. Our framework introduces three key components: (1) Dual-Graph Enhanced Reward Shaping, integrating recommendation metrics like NDCG@K with Query Alignment and Preference Alignment Scores to provide fine-grained reward signals for LLM optimization; (2) Reasoning-aware Advantage Estimation, which decomposes LLM outputs into reasoning segments and penalizes incorrect steps to enhance reasoning of recommendation; and (3) Online Curriculum Scheduler, dynamically assess query difficulty and organize training curriculum to ensure stable learning during RFT. Experiments demonstrate that ReRec outperforms state-of-the-art baselines and preserves core abilities like instruction-following and general knowledge. </div>
    <div class='paper-links'>
      <a href='https://arxiv.org/abs/2604.07851'>Paper</a>
      <a href='https://github.com/jiani-huang/ReRec'>Code</a>
    </div>
  </div>
</div>

# 🎖 Honors and Awards

# 📖 Education

- *2021.09 - 2024.06*, Master's, Institute of Automation, Chinese Academy of Sciences (CASIA), Supervisors: Prof. Jun Wan, [Prof. Ziqiang Li](https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN) (IEEE Fellow).

# 💻 Working Experience

- *2024.04 - Present*, Advertising LLM Engineer, Meituan.
- *2023.06 - 2024.03*, Multimodal LLM Engineer Intern, Alibaba AMAP (Gaode Maps).

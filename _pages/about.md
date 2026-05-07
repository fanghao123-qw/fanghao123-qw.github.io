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

I am Hao Fang, a Master's graduate from the Institute of Automation, Chinese Academy of Sciences (CASIA), where I was supervised by [Prof. Wan Jun](https://scholar.google.com/citations?user=bSbc7FQAAAAJ&hl=zh-CN) (IEEE Fellow). and [Prof. Stan Z. Li](https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN) (IEEE Fellow).

My research interests include computer vision and multimodal large language models. Previously, I served as a Multimodal LLM Engineer Intern at Alibaba's AMAP (Gaode Maps). Currently, I work as an Advertising LLM Engineer at Meituan.

For academic collaborations, please feel free to contact me via email.

# 🔥 News

- *2026*: &nbsp; UniAttack: Unified Physical-Digital Face Attack Detection, *International Journal of Computer Vision* (**IJCV,CCF-A**).
- *2026*: &nbsp; HySpeFAS: A Hyperspectral Face Anti-Spoofing Dataset Based on Snapshot Compressive Imaging, *IEEE Transactions on Information Forensics and Security* (**TIFS,CCF-A/SCI一区**).
- *2025*: &nbsp; UBG: An Unreal BattleGround Benchmark With Object-Aware Hierarchical Proximal Policy Optimization, *IEEE Transactions on Neural Networks and Learning Systems* (**TNNLS,SCI一区**).
- *2024*: &nbsp; Unified Physical-Digital Face Attack Detection (**IJCAI,CCF-A**).
- *2024*: &nbsp; VL-FAS: Domain Generalization via Vision-Language Model for Face Anti-Spoofing, *IEEE International Conference on Acoustics, Speech and Signal Processing* (**ICASSP,CCF-B,ORAL**).
- *2023*: &nbsp; Surveillance Face Anti-Spoofing, *IEEE Transactions on Information Forensics and Security* (**TIFS,CCF-A/SCI一区**).
- *2023*: &nbsp; Surveillance Face Presentation Attack Detection Challenge, *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops* (**CVPRW**).
- *2023*: &nbsp; Bandpass Filter Based Dual-Stream Network for Face Anti-Spoofing, *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (**CVPRW**).

# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-text'>
    <div class='paper-box-image'>
      <img src='../images/papers/uni.png' alt='UniAttack publication'>
    </div>
    <div class='paper-title'>Unified physical-digital face attack detection</div>
    <div class='paper-authors'><strong>Hao Fang</strong>, A Liu, H Yuan, J Zheng, D Zeng, Y Liu, J Deng, S Escalerai</div>
    <div class='paper-venue'>IJCAI 2024</div>
    <div class='paper-summary'>Face Recognition (FR) systems can suffer from physical (i.e., print photo) and digital (i.e., DeepFake) attacks. However, previous related work rarely considers both situations at the same time. This implies the deployment of multiple models and thus more computational burden. The main reasons for this lack of an integrated model are caused by two factors: (1) The lack of a dataset including both physical and digital attacks with ID consistency which means the same ID covers the real face and all attack types; (2) Given the large intra-class variance between these two attacks, it is difficult to learn a compact feature space to detect both attacks simultaneously. To address these issues, we collect a Unified physical-digital Attack dataset, called UniAttackData. The dataset consists of  participations of 2 and 12 physical and digital attacks, respectively, resulting in a total of 29,706 videos. Then, we propose a Unified Attack Detection framework based on Vision-Language Models (VLMs), namely UniAttackDetection, which includes three main modules: the Teacher-Student Prompts (TSP) module, focused on acquiring unified and specific knowledge respectively; the Unified Knowledge Mining (UKM) module, designed to capture a comprehensive feature space; and the Sample-Level Prompt Interaction (SLPI) module, aimed at grasping sample-level semantics. These three modules seamlessly form a robust unified attack detection framework. Extensive experiments on UniAttackData and three other datasets demonstrate the superiority of our approach for unified face attack detection. </div>
    <div class='paper-links'>
      <a href='https://arxiv.org/abs/2401.17699'>Paper</a>
      <a href='https://arxiv.org/abs/2401.17699'>Code</a>
    </div>
  </div>
</div>

# 🎖 Honors and Awards

# 📖 Education



# 💻 Working Experience

- *2024.04 - Present*, Advertising LLM Engineer, Meituan.
- *2023.06 - 2024.03*, Multimodal LLM Engineer Intern, Alibaba AMAP (Gaode Maps).

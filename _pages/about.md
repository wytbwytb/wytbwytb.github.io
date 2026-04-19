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

I am a PhD student at Beihang University, supervised by <a href='https://xlliu-beihang.github.io/'>Prof. Xianglong Liu</a>. My research focuses on the alignment of foundation models (LLMs/LVLMs), with a specific interest in inference-time interventions such as activation steering and knowledge editing. I am currently seeking internship opportunities to apply my research to real-world challenges. I am driven by the belief that advanced AI should not only push the boundaries of technology but also bring tangible convenience and positive impact to people's daily lives.

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 I am awarded the Bronze Medal in the Artificial Intelligence Track of the Autel Physical AI Challenge.
- *2026.02*: &nbsp;🎉🎉 One first-author paper is accepted by ICLR 2026. 
- *2026.01*: &nbsp;🎉🎉 One paper is accepted by WWW 2026.

# 📝 Publications 

## 2026
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/AFTER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AFTER: Mitigating the Object Hallucination of LVLM via Adaptive Factual-Guided Activation Editing](https://arxiv.org/pdf/2601.01957)

**Tianbo Wang**, Yuqing Ma, Kewei Liao, Zhange Zhang, Simin Li, Jinyang Guo, Xianglong Liu

[**Github**](https://github.com/wytbwytb/AFTER) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes AFTER, a novel adaptive factual-guided activation editing approach to mitigate object hallucinations and language bias in Large Vision-Language Models. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/QRAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Query-Routed Activation Editing with Truth-hierarchical Preference Optimization](https://ojs.aaai.org/index.php/AAAI/article/view/40468)

Kewei Liao\*, **Tianbo Wang\***(Equal Contribution), Yuqing Ma, Zhange Zhang, Zhicheng Geng, Xiaowei Zhao, Jiakai Wang, Xianglong Liu

[**Github**](https://github.com/liaokewei/QRAE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes QRAE, a novel query-routed activation editing framework to leverage query-specific semantics for adaptive hallucination mitigation in LLMs. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/CASE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CASE: Conflict-assessed Knowledge-sensitive Neuron Tuning for Lifelong Model Editing](https://dl.acm.org/doi/abs/10.1145/3774904.3792427)

Zhange Zhang, Yuqing Ma, Yulong Wang, **Tianbo Wang**, Jiakai Wang, Simin Li, Xianglong Liu

[**Github**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes CASE, a novel conflict-assessed knowledge-sensitive neuron tuning approach to address subspace allocation issues and editing conflicts in lifelong model editing.
</div>
</div>

## 2025
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 Oral</div><img src='images/TAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Token-Aware Editing of Internal Activations for Large Language Model Alignment](https://aclanthology.org/2025.emnlp-main.480/)

**Tianbo Wang**, Yuqing Ma, Kewei Liao, Chengzhao Yang, Zhange Zhang, Jiakai Wang, Xianglong Liu

[**Github**](https://github.com/wytbwytb/TAE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes TAE, a novel token-aware activation editing approach to utilize token-level alignment information for superior inference-time behavior mitigation in LLMs. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCIS 2025</div><img src='images/SWEAR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Universal X-ray Security Inspection: A Benchmark and Stereoscopic-Aware Oriented Prohibited Item Detection Framework](https://link.springer.com/article/10.1007/s11432-024-4732-x)

**Tianbo Wang**, Kewei Liao, Zhange Zhang, Yuqing Ma, Hongping Zhi, Aishan Liu, Ruihao Gong, Xianglong Liu

[**Github**](https://github.com/wytbwytb/SWEAR) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes SWEAR, a novel stereoscopic-aware oriented detection framework to suppress background interference and improve prohibited item detection in oriented X-ray security inspection. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Spotlight</div><img src='images/CAKE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Conflict-Aware Knowledge Editing in the Wild: Semantic-Augmented Graph Representation for Unstructured Text](https://openreview.net/forum?id=wHm5J9uanV)

Zhange Zhang, Zhicheng Geng, Yuqing Ma, **Tianbo Wang**, Kai Lv, Xianglong Liu

[**Github**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes CAKE, a novel conflict-aware knowledge editing framework to enable precise knowledge extraction and refinement from wild unstructured text in LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/DRAG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Lexical Diversity-aware Relevance Assessment for Retrieval-Augmented Generation](https://link.springer.com/article/10.1007/s11432-024-4732-x)

Zhange Zhang, Yuqing Ma, Yulong Wang, Shan He, **Tianbo Wang**, Siqi He, Jiakai Wang, Xianglong Liu

[**Github**](https://github.com/Zhange21/DRAG) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes DRAG, a novel lexical diversity-aware relevance assessment method to achieve granular relevance analysis and improve document retrieval precision in RAG systems. 
</div>
</div>

## Early Publication

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='images/WEN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Few-shot X-ray Prohibited Item Detection: A Benchmark and Weak-feature Enhancement Network](https://dl.acm.org/doi/abs/10.1145/3503161.3548075)

Renshuai Tao, **Tianbo Wang**, Ziyang Wu, Cong Liu, Aishan Liu, Xianglong Liu

[**Github**](https://github.com/wytbwytb/WEN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes WEN, a novel weak-feature enhancement network to overcome performance degradation caused by occlusion and color fading in few-shot X-ray prohibited item detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/PSN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Endogenous Shift for Cross-domain Detection: A Large-scale Benchmark and Perturbation Suppression Network](https://ieeexplore.ieee.org/abstract/document/9878613/)

Renshuai Tao, Hainan Li, **Tianbo Wang**, Yanlu Wei, Yifu Ding, Bowei Jin, Hongping Zhi, Xianglong Liu, Aishan Liu

[**Github**](https://github.com/DIG-Beihang/PSN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes PSN, a novel perturbation suppression network to handle endogenous domain shifts caused by intrinsic imaging mechanisms in cross-domain object detection. 
</div>
</div>


# 🎖 Honors and Awards
- *2026.04* Bronze Medal of Autel Artificial Intelligence Competition.
- *2024.10* Outstanding Student Award of Beihang University.
- *2022.06* Excellent Graduate of Beihang University. 

# 📖 Educations
- *2022.09 - now*, PhD student, Beihang University. 
- *2018.09 - 2022.06*, Undergrad student, Beihang University.

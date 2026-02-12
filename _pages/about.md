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

Hi! I’m Qiuchen Wang, a final year graduate student at University of Science and Technology of China. I am co-supervised by Prof. [Feng Zhao](https://en.auto.ustc.edu.cn/2021/0616/c26828a513169/page.htm) and Prof. [Feng Wu](https://scholar.google.com/citations?user=5bInRDEAAAAJ). Previously, I obtained my B.Eng. degree in Electronic Information and Communications of Huazhong University of Science and Technology, under the guidance of Prof. [Xinge You](https://bmal.hust.edu.cn/EN.htm).

My research interest includes Multi-modal Large Language Models, Multi-modal Agents, and Reinforcement Learning.

# 🔥 News
- **2026.1**: Two papers got accepted to ICLR 2026
- **2025.9**: One paper got accepted to NeurIPS 2025
- **2025.8**: One paper got accepted to EMNLP 2025
- **2025.6**: We released [VRAG-RL](https://github.com/Alibaba-NLP/VRAG), a purely visual RAG agent that enables VLMs to progressively gather information from a coarse-grained to a fine-grained perspective.
- **2025.3**: We released [ViDoRAG](https://github.com/Alibaba-NLP/ViDoRAG), a novel multi-agent RAG framework for visually rich documents and the ViDoSeek retrieval-reasoning dataset.
- **2025.1**: Two papers got accepted to ICLR 2025
- **2024.7**: We released [MindSearch(思·索)](https://mindsearch.netlify.app/), which is an awesome AI search engine comparable to Perplexity.ai Pro. Welcome to use and provide your feedback!
- **2024.4**: One paper got accepted to ACL 2024
- **2024.3**: We released [Agent-FLAN](https://github.com/InternLM/Agent-FLAN), which explores the construction of high-quality agent corpus for LLMs.

# 📝 Publications 

<!-- vimrag -->
<div class='paper-box'><div class='paper-box-image'><div><img src='../images/vimrag.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**VimRAG: Navigating Massive Visual Context in Retrieval-Augmented Generation via Multimodal Memory Graph**

**Qiuchen Wang**, Shihang Wang, Yu Zeng, Qiang Zhang, Fanrui Zhang, Zhuoning Guo, Bosi Zhang, Wenxuan Huang, Lin Chen, Zehui Chen, Pengjun Xie, Ruixue Ding, Feng Zhao

*The work done at Tongyi Lab, Alibaba Group. The training code is currently under review by the company.*

[[**Paper**]]()&nbsp;
[[**Code**]](https://github.com/Alibaba-NLP/VRAG)[![GitHub stars](https://img.shields.io/github/stars/Alibaba-NLP/VRAG?style=social)](https://github.com/Alibaba-NLP/VRAG)
<!-- [[**Models**]](https://huggingface.co/autumncc/Qwen2.5-VL-7B-VRAG)&nbsp;
[[**Wechat(机器之心)**]](https://mp.weixin.qq.com/s/q3HD4xHK08-_fV_ovr_PpQ) -->

</div>
</div>
<!-- vimrag -->

<!-- vdr -->
<div class='paper-box'><div class='paper-box-image'><div><img src='../images/vdr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Vision-DeepResearch: Incentivizing DeepResearch Capability in Multimodal Large Language Models**

Wenxuan Huang\*, Yu Zeng\*, **Qiuchen Wang**\*, Zhen Fang, Shaosheng Cao, Zheng Chu, Qingyu Yin, Shuang Chen, Zhenfei Yin, Lin Chen, Zehui Chen, Yao Hu, Philip Torr, Feng Zhao, Wanli Ouyang

*Work as co-first author. The first open-sourced long-horizon multimodal deep-research.*

[[**Paper**]](https://arxiv.org/abs/2601.22060)&nbsp;
[[**Project**]](https://osilly.github.io/Vision-DeepResearch/)&nbsp;
[[**Code&Data&Models**]](https://github.com/Osilly/Vision-DeepResearch)[![GitHub stars](https://img.shields.io/github/stars/Osilly/Vision-DeepResearch?style=social)](https://github.com/Osilly/Vision-DeepResearch)

</div>
</div>
<!-- vdr -->


<!-- vrag -->
<div class='paper-box'><div class='paper-box-image'><div><img src='../images/vrag.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**VRAG-RL: Empower Vision-Perception-Based RAG for Visually Rich Information Understanding via Iterative Reasoning with Reinforcement Learning**

**Qiuchen Wang**,
Ruixue Ding,
Yu Zeng,
Zehui Chen,
Lin Chen,
Shihang Wang,
Pengjun Xie,
Fei Huang,
Feng Zhao

*The Thirty-Ninth Annual Conference on Neural Information Processing Systems (**NeurIPS**), 2025*

[[**Paper**]](https://arxiv.org/abs/2505.22019)&nbsp;
[[**Models**]](https://huggingface.co/autumncc/Qwen2.5-VL-7B-VRAG)&nbsp;
[[**Wechat(机器之心)**]](https://mp.weixin.qq.com/s/q3HD4xHK08-_fV_ovr_PpQ)
[[**Code**]](https://github.com/Alibaba-NLP/VRAG)[![GitHub stars](https://img.shields.io/github/stars/Alibaba-NLP/VRAG?style=social)](https://github.com/Alibaba-NLP/VRAG)

</div>
</div>
<!-- vrag -->


<!-- vidorag -->
<div class='paper-box'><div class='paper-box-image'><div><img src='../images/vidorag.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**ViDoRAG: Visual Document Retrieval Augmented Generation via Dynamic Iterative Reasoning Agents**

**Qiuchen Wang**,
Ruixue Ding,
Zehui Chen,
Weiqi Wu,
Shihang Wang,
Pengjun Xie,
Feng Zhao

*Conference on Empirical Methods in Natural Language Processing (**EMNLP Main**), 2025*

[[**Paper**]](https://arxiv.org/abs/2502.18017)&nbsp;
[[**Dataset**]](https://huggingface.co/datasets/autumncc/ViDoSeek)&nbsp;
[[**Code**]](https://github.com/Alibaba-NLP/ViDoRAG)[![GitHub stars](https://img.shields.io/github/stars/Alibaba-NLP/ViDoRAG?style=social)](https://github.com/Alibaba-NLP/ViDoRAG)

</div>
</div>

<!-- vidorag -->


<!-- psedet -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='../images/psedet.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box'><div class='paper-box-image'><div><img src='../images/psedet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**PseDet: Revisiting the Power of Pseudo Label in Incremental Object Detection**

**Qiuchen Wang**,
Zehui Chen,
Chenhongyi Yang,
JIaming Liu,
Zhenyu Li,
Feng Zhao

*International Conference on Learning Representations (**ICLR**), 2025*

[[**Paper**]]()&nbsp;
[[**Code**]](https://github.com/wang-qiuchen/PseDet)

</div>
</div>
<!-- psedet -->

<!-- mindsearch -->
<div class='paper-box'><div class='paper-box-image'><div><img src='../images/mindsearch.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**MindSearch: Mimicking Human Minds Elicits Deep AI Searcher**

Zehui Chen\*, Kuikun Liu\*, **Qiuchen Wang**, Jiangning Liu, Wenwei Zhang, Kai Chen, Feng Zhao

*International Conference on Learning Representations (**ICLR**), 2025*

[[**Project**]](https://mindsearch.netlify.app/)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2407.20183)&nbsp;
[[**Code**]](https://github.com/InternLM/MindSearch)[![GitHub stars](https://img.shields.io/github/stars/InternLM/MindSearch?style=social)](https://github.com/InternLM/MindSearch)


</div>
</div>
<!-- mindsearch -->

<!-- agentflan -->
<div class='paper-box'><div class='paper-box-image'><div><img src='../images/agentflan.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models**

Zehui Chen, Kuikun Liu, **Qiuchen Wang**, Wenwei Zhang, Jiangning Liu, Dahua Lin, Kai Chen, Feng Zhao

*Findings of the Association for Computational Linguistics (**ACL Findings**) , 2024*


[[**Project**]](https://internlm.github.io/Agent-FLAN)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2403.12881)&nbsp;
[[**Code**]](https://github.com/InternLM/Agent-FLAN)[![GitHub stars](https://img.shields.io/github/stars/InternLM/Agent-FLAN?style=social)](https://github.com/InternLM/Agent-FLAN)

</div>
</div>
<!-- agentflan -->


<div class='paper-box-text' markdown="1">
**WebWatcher: Breaking New Frontiers of Vision-Language Deep Research Agent**

Xinyu Geng, Peng Xia, Zhen Zhang, Xinyu Wang, **Qiuchen Wang**, Ruixue Ding, Chenxi Wang, Jialong Wu, Kuan Li, Yida Zhao, Huifeng Yin, Yong Jiang, Pengjun Xie, Fei Huang, Huaxiu Yao, Yi R. Fung, Jingren Zhou

*The Fourteenth International Conference on Learning Representations (**ICLR**), 2026*

[[**Project**]](https://tongyi-agent.github.io/blog/introducing-tongyi-deep-research/)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2508.05748)&nbsp;
[[**Code**]](https://github.com/Alibaba-NLP/DeepResearch)[![GitHub stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=social)](https://github.com/Alibaba-NLP/DeepResearch)
</div>


<div class='paper-box-text' markdown="1">
**Agentic Jigsaw Interaction Learning for Enhancing Visual Perception and Reasoning in Vision-Language Models**

Yu Zeng, Wenxuan Huang, Shiting Huang, Xikun Bao, Yukun Qi, Yiming Zhao, **Qiuchen Wang**, Lin Chen, Zehui Chen, Huaian Chen, Wanli Ouyang, Feng Zhao 

*The Fourteenth International Conference on Learning Representations (**ICLR**), 2026*

[[**Project**]](https://yuzeng0-0.github.io/AGILE/)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2510.01304)&nbsp;
[[**Code**]](https://github.com/yuzeng0-0/AGILE)[![GitHub stars](https://img.shields.io/github/stars/yuzeng0-0/AGILE?style=social)](https://github.com/yuzeng0-0/AGILE)
</div>



## *Preprint*

<div class='paper-box-text' markdown="1">
**ArenaRL: Scaling RL for Open-Ended Agents via Tournament-based Relative Ranking** 

**🌟 This project has already been commercially deployed in Amap(Gaode Map, Xiaogao Teacher) with hundreds of millions of users.**

Qiang Zhang, Boli Chen, Fanrui Zhang, Ruixue Ding, Shihang Wang, **Qiuchen Wang**, Yinfeng Huang, Haonan Zhang, Rongxiang Zhu, Pengyong Wang, Ailin Ren, Xin Li, Pengjun Xie, Jiawei Liu, Ning Guo, Jingren Zhou, Zheng-Jun Zha

[[**Project**]](https://tongyi-agent.github.io/blog/arenarl)&nbsp;
[[**Paper**]](https://arxiv.org/abs/2601.06487)&nbsp;
[[**Code**]](https://github.com/Alibaba-NLP/qqr)[![GitHub stars](https://img.shields.io/github/stars/Alibaba-NLP/qqr?style=social)](https://github.com/Alibaba-NLP/qqr)
</div>




<div class='paper-box-text' markdown="1">
**AsyncTool: Evaluating the Asynchronous Function Calling Capability under Multi-Task Scenarios**

Kou Shi, Ziao Zhang, Shiting Huang, Avery Nie, Zhen Fang, **Qiuchen Wang**, Lin Chen, Huaian Chen, Zehui Chen, Feng Zhao

[[**Project**]]()&nbsp;
[[**Paper**]]()&nbsp;
<!-- [[**Code**]](https://github.com/InternLM/Agent-FLAN)[![GitHub stars](https://img.shields.io/github/stars/InternLM/Agent-FLAN?style=social)](https://github.com/InternLM/Agent-FLAN) -->

</div>



# 🎖 Awards
- National Scholarship, 2025.
- $1^{st}$ place at VCL2023 Challenge, Multitask Learning for Robustness Track! (**ICCV 2023** Workshop)
- Outstanding Graduates of Huazhong University of Science and Technology, 2023.
- Merit Student of Huazhong University of Science and Technology, 2021, 2022.
- The First Prize of the 12th China Undergraduate Mathematics Competition, 2020.

# 📖 Educations
- *2023.09 - present*, M.E. at University of Science and Technology of China. 
- *2019.09 - 2023.06*, B.E. in Electronic Information and Communications of Huazhong University of Science and Technology. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.08 - present*, LLM Research Intern, Qwen RAG Group at Alibaba-inc, Hangzhou, China.
- *2023.03 - 2023.06*, Autonomous Driving Intern, iMotion, Suzhou, China.

---
permalink: /
title: ""

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

Hi, I obtained my master degree and bachelor degree from ***[School of Computing](https://www.comp.nus.edu.sg/), National University of Singapore (NUS)*** and ***Hong Kong Baptist University (HKBU)***, respectively. I am currently pursuing my PhD degree at ***Hong Kong University of Science and Technology*** under the supervision of [Prof.Xuming HU](https://xuminghu.github.io/) (Assistant Professor of AI Thrust, GZ Campus) and [Prof.James KWOK](https://www.cse.ust.hk/~jamesk/) (Professor of CSE, CWB Campus; IEEE Fellow). I am also conducting research at ***Alibaba Group***.

Previously, I had extensive internship experience in both industry and academia, including ***NLP Team, ByteDance AI Lab*** (supervised by Mr.Yang WANG and [Dr.Hang LI](https://www.linkedin.com/in/hang-li-84aa6314/?originalSubdomain=cn), director of ByteDance Research), ***AI Research, Squirrel AI*** (supervised by [Dr.Qingsong WEN](https://sites.google.com/site/qingsongwen8/), head of AI and chief scientist), ***LLM Group, Institute for Advanced Algorithms Research*** (co-supervised by [Dr.Zhiyu LI](https://openreview.net/profile?id=~Zhiyu_li2), [Dr.Feiyu XIONG](https://scholar.google.com/citations?user=GOKgLdQAAAAJ&hl=en), and [Prof.Weinan E](https://web.math.princeton.edu/~weinan/)), ***Reefknot Investment*** (co-supervised by [Mr.Marc DRAGON](https://reefknotinvestments.com/team/marc-dragon/), managing director of Reefknot, and [Prof.Wei Ngan CHIN](https://www.comp.nus.edu.sg/~chinwn/), vice dean of SoC, NUS), and ***University of California, Berkeley*** (supervised by [Dr.Qing ZHU](https://bids.berkeley.edu/people/qing-zhu), research scientist at Lawrence Berkeleey National Laboratory). I also conducted research at CityMind Lab, HKUST(GZ) (led by [Prof.Yuxuan LIANG](https://yuxuanliang.com/)) before.

My research interests include ***natural language processing <img src='./images/text-mining.png' style='height: 1.5em;'>, multimodal representation learning <img src='./images/multimedia.png' style='height: 1.5em;'>, data mining applications including urban computing <img src='./images/infrastructure.png' style='height: 1.5em;'> and recommendation systems <img src='./images/rating.png' style='height: 1.5em;'>***. Look forward to any academic collaboration.



<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!--
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📖 Education
- *Now*, PhD, ***Hong Kong University of Science and Technology*** <img src='./images/HKUST_cwb.png' style='height: 3.0em;'>
- *2021 - 2023*, Master, ***National University of Singapore*** <img src='./images/NUS.png' style='height: 1.5em;'>
- *2017 - 2021*, Undergraduate, ***Hong Kong Baptist University*** <img src='./images/HKBU.png' style='width: 6em;'> (President's Honour Roll <img src='./images/certificate.png' style='height: 1.5em;'>)

# 📝 Selected Publications
**Note**: \* as Co-first Author; † as Corresponding Author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/mathagent_acl25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MathAgent: Leveraging a Mixture-of-Math-Agent Framework for Real-World Multimodal Mathematical Error Detection](https://arxiv.org/abs/2503.18132)

**<u>Yibo Yan</u>**, Shen Wang, Jiahao Huo, Philip S. Yu, Xuming Hu†, Qingsong Wen†

- A novel Mixture-of-Math-Agent framework designed specifically to address mutlimodal error detection.

63rd Annual Meeting of the Association for Computational Linguistics, Vienna, Austria (**ACL'25 Industry**)

<img src='./images/flames.png' style='height: 1.5em;'> **<span style="color:red;">Oral Presentation</span>**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL Finding 2025</div><img src='images/math_mllm_survey_acl25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey of Mathematical Reasoning in the Era of Multimodal Large Language Model: Benchmark, Method & Challenges](https://arxiv.org/abs/2412.11936)

**<u>Yibo Yan</u>**, Jiamin Su, Jianxiang He, Fangteng Fu, Xu Zheng, Yuanhuiyi Lyu, Kun Wang, Shen Wang, Qingsong Wen, Xuming Hu†

-  First comprehensive analysis of mutlimodal mathematical reasoning in the era of MLLMs.

63rd Annual Meeting of the Association for Computational Linguistics, Vienna, Austria (**ACL'25 Findings**)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2024</div><img src='images/urbanclip_www24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UrbanCLIP: Learning Text-enhanced Urban Region Profiling with Contrastive Language-Image Pretraining from the Web](https://arxiv.org/abs/2310.18340)

**<u>Yibo Yan</u>**, Haomin Wen, Siru Zhong, Wei Chen, Haodong Chen, Qingsong Wen, Roger Zimmermann, Yuxuan Liang†

- First-ever LLM-enhanced framework that integrates the knowledge of textual modality into urban imagery profiling.

The International World Wide Web Conference 2024, Singapore (**WWW'24**)

<img src='./images/flames.png' style='height: 1.5em;'> **<span style="color:red;">Oral Presentation</span>**

</div>
</div>

<!-- **Project** <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- First-ever LLM-enhanced framework that integrates the knowledge of textual modality into urban imagery profiling.
</div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/georeasoner_cikm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GeoReasoner: Reasoning On Geospatially Grounded Context For Natural Language Understanding](https://arxiv.org/abs/2408.11366)

**<u>Yibo Yan</u>**, Joey Lee†

- A pipeline integrating linguistic and geospatial information, showcasing the advantages of an LLM-assisted workflow over conventional methods in geo-reasoning tasks.

33rd ACM International Conference on Information and Knowledge Management, Idaho, USA (**CIKM'24**)

<img src='./images/flames.png' style='height: 1.5em;'> **<span style="color:red;">Best Short Paper Award</span>**

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR Workshop 2025</div><img src='images/errorradar_icml25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ErrorRadar: Benchmarking Complex Mathematical Reasoning of Multimodal Large Language Models Via Error Detection](https://arxiv.org/abs/2410.04509)

**<u>Yibo Yan</u>**, Shen Wang, Jiahao Huo, Hang Li, Boyan Li, Jiamin Su, Xiong Gao, Yi-Fan Zhang, Tianlong Xu, Zhendong Chu, Aoxiao Zhong, Kun Wang, Hui Xiong, Philip S. Yu, Xuming Hu†, Qingsong Wen†

- First benchmark designed to assess MLLMs' complex reasoning capabilities in multimodal error detection.

Workshop on Reasoning and Planning for LLMs, 13th International Conference on Learning Representations, Singapore (**ICLR Workshop'25**)


</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/mllm4sci_position_icml25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Position: Multimodal Large Language Models Can Significantly Advance Scientific Reasoning](https://arxiv.org/abs/2502.02871)

**<u>Yibo Yan</u>**, Shen Wang, Jiahao Huo, Jingheng Ye, Zhendong Chu, Xuming Hu†, Philip S. Yu, Carla Gomes, Bart Selman, Qingsong Wen†

-  This position paper argues that MLLMs can significantly advance scientific reasoning across disciplines such as mathematics, physics, chemistry, and biology.

Under Review

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL Finding 2025</div><img src='images/mmunlearner_acl25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMUnlearner: Reformulating Multimodal Machine Unlearning in the Era of Multimodal Large Language Models](https://arxiv.org/abs/2502.11051)

Jiahao Huo\*, **<u>Yibo Yan</u>**\*, Xu Zheng, Yuanhuiyi Lyu, Xin Zou, Zhihua Wei, Xuming Hu†

-  We propose to reformulate the task of multimodal MU in the era of MLLMs, and develop a novel geometry-constrained gradient descent method MMUnlearner.

63rd Annual Meeting of the Association for Computational Linguistics, Vienna, Austria (**ACL'25 Findings**)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL Finding 2025</div><img src='images/essayjudge_acl25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EssayJudge: A Multi-Granular Benchmark for Assessing Automated Essay Scoring Capabilities of Multimodal Large Language Models](https://arxiv.org/abs/2502.11916)

Jiamin Su\*, **<u>Yibo Yan</u>**\*, Fangteng Fu, Han Zhang, Jingheng Ye, Xiang Liu, Jiahao Huo, Huiyu Zhou, Xuming Hu†

-   First multimodal benchmark to evaluate Automated Essay Scoring (AES)   capabilities across lexical-, sentence-, and discourse-level traits.

63rd Annual Meeting of the Association for Computational Linguistics, Vienna, Austria (**ACL'25 Findings**)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">InfoFusion 2024</div><img src='images/multimodal_survey_InformationFusion24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Learning for Cross-Domain Data Fusion in Urban Computing: Taxonomy, Advances, and Outlook](https://arxiv.org/abs/2402.19348)

Xingchen Zou\*, **<u>Yibo Yan</u>**\*, Xixuan Hao, Yuehong Hu, Haomin Wen, Erdong Liu, Junbo Zhang, Yong Li, Tianrui Li, Yu Zheng, Yuxuan Liang†

- First comprehensive survey that systematically reviews studies on deep learning-based multimodal and multi-source data fusion models in urban computing.

Information Fusion Journal (**<span style="color:red;">IF=15</span>**)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/phantomcircuit_emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pierce the Mists, Greet the Sky: Decipher Knowledge Overshadowing via Knowledge Circuit Analysis](https://arxiv.org/pdf/2505.14406?)

Haoming Huang\*, **<u>Yibo Yan</u>**\*, Jiahao Huo, Xin Zou, Xinfeng Li, Kun Wang, Xuming Hu†

- A novel framework designed to comprehensively analyze and detect knowledge overshadowing, a particularly challenging variant of LLM hallucinations.

Under Review

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/physicsarena_emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PhysicsArena: The First Multimodal Physics Reasoning Benchmark Exploring Variable, Process, and Solution Dimensions](https://arxiv.org/pdf/2505.15472?)

Song Dai\*, **<u>Yibo Yan</u>**\*, Jiamin Su, Dongfang Zihao, Yubo Gao, Yonghua Hei, Jungang Li, Junyan Zhang, Sicheng Tao, Zhuoran Gao, Xuming Hu†

- First multimodal physics reasoning benchmark designed to holistically evaluate MLLMs across three critical dimensions: variable identification, physical process formulation, and solution derivation.

Under Review

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/causalmm_iclr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mitigating Modality Prior-Induced Hallucinations in Multimodal Large Language Models via Deciphering Attention Causality](https://arxiv.org/abs/2410.04780)

Guanyu Zhou, **<u>Yibo Yan</u>**, Xin Zou, Kun Wang, Aiwei Liu, Xuming Hu†

- A causal inference framework that applies structural causal modeling to MLLMs, treating modality priors as a confounder between attention mechanisms and output.

13th International Conference on Learning Representations, Singapore (**ICLR'25**)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/mmneuron_emnlp24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMNeuron: Discovering Neuron-Level Domain-Specific Interpretation in Multimodal Large Language Model](https://arxiv.org/abs/2406.11193)

Jiahao Huo, **<u>Yibo Yan</u>**, Boren Hu, Yutao Yue, Xuming Hu†

- Investigation of the distribution of domain-specific neurons and the mechanism of how MLLMs process features from diverse domains.

Conference on Empirical Methods in Natural Language Processing 2024, Florida, USA (**EMNLP'24**)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/cafes_emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CAFES: A Collaborative Multi-Agent Framework for Multi-Granular Multimodal Essay Scoring](https://arxiv.org/pdf/2505.13965?)

Jiamin Su, **<u>Yibo Yan</u>**, Zhuoran Gao, Han Zhang, Xiang Liu, Xuming Hu†

- First collaborative multi-agent framework specifically designed for Automated Essay Scoring.

Under Review

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/memvr_iclr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Look Twice Before You Answer: Memory-Space Visual Retracing for Hallucination Mitigation in Multimodal Large Language Models](https://arxiv.org/abs/2410.03577)

Xin Zou\*, Yizhou Wang\*, **<u>Yibo Yan</u>**, Sirui Huang, Kening Zheng, Junkai Chen, Chang Tang, Xuming Hu†

- A novel hallucination mitigation paradigm that without the need for external knowledge retrieval or additional fine-tuning.

42nd International Conference on Machine Learning, Vancouver, Canada (**ICML'25**)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL Finding 2025</div><img src='images/reefknot_aaai25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reefknot: A Comprehensive Benchmark for Relation Hallucination Evaluation, Analysis and Mitigation in Multimodal Large Language Models](https://arxiv.org/abs/2408.09429)

Kening Zheng\*, Junkai Chen\*, **<u>Yibo Yan</u>**, Xin Zou, Xuming Hu†

- A comprehensive benchmark specifically targeting relation hallucinations, consisting of over 20k samples derived from real-world scenarios.

63rd Annual Meeting of the Association for Computational Linguistics, Vienna, Austria (**ACL'25 Findings**)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/sparcom_emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unveiling Instruction-Specific Neurons & Experts: An Analytical Framework for LLM's Instruction-Following Capabilities](https://arxiv.org/pdf/2505.21191)

Junyan Zhang\*, Yubo Gao\*, **<u>Yibo Yan</u>**, Jungang Li, Zhaorui Hou, Sicheng Tao, Shuliang Liu, Song Dai, Yonghua Hei, Junzhuo Li, Xuming Hu†

- A novel analytical framework for identification of instruction-specific sparse components of LLMs, and evaluation of their functional generality and uniqueness.

Under Review

</div>
</div>





<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/urbanvlp_kdd24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UrbanVLP: A Multi-Granularity Vision-Language Pre-Trained Model for Urban Indicator Prediction](https://arxiv.org/abs/2403.16831)

Xixuan Hao\*, Wei Chen\*, **<u>Yibo Yan</u>**, Siru Zhong, Kun Wang, Qingsong Wen, Yuxuan Liang†

- First urban region representation learning framework that explores multi-granularity cross-modal alignment.

39th Annual AAAI Conference on Artificial Intelligence, Philadelphia, USA (**AAAI'25**)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/urbancross_mm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UrbanCross: Enhancing Satellite Image-Text Retrieval with Cross-Domain Adaptation](https://arxiv.org/abs/2404.14241)

Siru Zhong, Xixuan Hao, **<u>Yibo Yan</u>**, Ying Zhang, Yangqiu Song, Yuxuan Liang†

- First cross-domain framework that integrates the power of LMM and SAM into satellite image-text retrieval.

32nd ACM Multimedia Conference, Melbourne, Australia (**ACM MM'24**)

</div>
</div> -->






# 💻 Work Experience
- *Jun 2025 - Now*, ***Alibaba***, Hangzhou, China. <img src='./images/alibaba.png' style='height: 1.3em;'>
  - **Focus**: Multimodal Retrieval and Search of LLMs
  - **Supervisors**: [Mr.Guangwei XU](https://openreview.net/profile?id=~Guangwei_Xu2) (Senior Algorithm Researcher) and [Mr.Shaomin XING](https://www.alibabacloud.com/blog/key-technologies-for-optimization-of-enterprise-level-rag_601723) (Head of AI Search, Alibaba Cloud)
  - **Achievement**: On-going projects

- *Jun 2024 - Apr 2025*, ***AI Research, Squirrel AI***, Remote. <img src='./images/squirrel.png' style='height: 1.3em;'>
  - **Focus**: Multimodal LLM for Education
  - **Supervisors**: [Dr.Shen WANG](https://www.deep-mining.com/) (Staff Research Scientist) and [Dr.Qingsong WEN](https://sites.google.com/site/qingsongwen8/home) (Head of AI Research & Chief Scientist)
  - **Achievement**: Developed benchmark and algorithms for MLLM-based reasoning in real-life educational scenarios

- *Feb 2024 - May 2024*, ***LLM Group, Institute for Advanced Algorithms Research, Shanghai***, Remote. <img src='./images/IAAR.png' style='height: 1.1em;'>
  - **Focus**: LLM Hallucination Mitigation
  - **Supervisors**: [Dr.Zhiyu LI](https://openreview.net/profile?id=~Zhiyu_li2) (Principal Researcher of LLM Team) and [Dr.Feiyu XIONG](https://scholar.google.com/citations?user=GOKgLdQAAAAJ&hl=en) (Director of LLM Group)
  - **Achievement**: Mitigated the entity-level hallucination in real-life news corpora from Xinhua News Agency

- *Nov 2022 - Jul 2023*, ***AI Lab, ByteDance***, Singapore. <img src='./images/tiktok.png' style='width: 6em;'>
  - **Focus**: NLP (esp. user intent recognition and conversation modelling) and Recommendation Systems
  - **Supervisors**: Mr.Yang WANG (Leader of Conversation Team) and [Dr.Hang LI](https://www.linkedin.com/in/hang-li-84aa6314/?originalSubdomain=cn) (Director of ByteDance Research, Fellow of ACM/ACL/IEEE)
  - **Achievement**: Successfully designed and deployed multiple models in real-life applications such as Tiktok Intelligence Customer Service and Douyin E-commerce Platform

- *May 2022 - Sep 2022*, ***Reefknot Investment***, Singapore. <img src='./images/reefknot.png' style='height: 1.5em;'>
  - A joint venture between ***Temasek*** <img src='./images/temasek.png' style='height: 1.5em;'> and ***Kuehne+Nagel*** <img src='./images/kuehne_nagel.png' style='height: 1.5em;'>
  - **Focus**: Graph Analytics, NLP (esp. entity resolution), Federated Learning
  - **Supervisors**: [Mr.Marc DRAGON](https://reefknotinvestments.com/team/marc-dragon/) (Managing Director of Reefknot) and [Prof.Wei Ngan CHIN](https://www.comp.nus.edu.sg/~chinwn/) (Associate Professor and Vice Dean of SoC, NUS)
  - **Achievement**: Comprehensive tech analysis for target deep-tech start-ups

- *Jul 2020 - Sep 2020*, ***UC Berkeley***, Remote. <img src='./images/UCB.png' style='height: 1.5em;'>
  - **Focus**: Casual Modelling for Earth Science
  - **Supervisor**: [Dr.Qing ZHU](https://bids.berkeley.edu/people/qing-zhu) (Research Scientist at Institute for Data Science)
  - **Achievement**: Developed a transfer entropy-based climate diagnostic tool for Pearl River Delta







# 🎖 Honors and Awards
- *2024-2025,* Postgraduate Scholarship, HKUST(GZ)
- *2024,* Best Short Paper Award <img src='./images/star-medal.png' style='height: 1.5em;'>, CIKM 2024
- *2023,* Silver Medal <img src='./images/silver-medal.png' style='height: 1.5em;'>, OTTO - Multi-Objective Recommender System, Kaggle Competition
- *2023,* Silver Medal <img src='./images/silver-medal.png' style='height: 1.5em;'>, Stable Diffusion - Image to Prompts, Kaggle Competition
- *2021,* Best Undergraduate Thesis (Remote Sensing Track) <img src='./images/certificate.png' style='height: 1.5em;'>
- *2019-2020, 2020-2021,* First-class Academic Award <img src='./images/star-medal.png' style='height: 1.5em;'>, HKBU
- *2017-2018, 2018-2019,* Second-class Academic Award <img src='./images/silver-medal.png' style='height: 1.5em;'>, HKBU


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->


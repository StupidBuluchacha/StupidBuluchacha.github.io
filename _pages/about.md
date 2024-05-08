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

Hi~ I obtained my master degree and bachelor degree from ***[School of Computing](https://www.comp.nus.edu.sg/), National University of Singapore (NUS)*** and ***Hong Kong Baptist University (HKBU)***, respectively. I am currently pursuing my PhD degree at ***Hong Kong University of Science and Technology*** under the supervision of [Prof.Xuming HU](https://xuminghu.github.io/). I also coorperate with ***LLM Group, Institute for Advanced Algorithms Research*** (led by [Dr.Feiyu XIONG](https://scholar.google.com/citations?user=GOKgLdQAAAAJ&hl=en) and [Prof.Weinan E](https://web.math.princeton.edu/~weinan/)). I conducted research at CityMind Lab, HKUST(GZ) (led by [Prof.Yuxuan LIANG](https://yuxuanliang.com/)) before.

Previously, I had extensive internship experience in both industry and academia, including ***NLP Team, ByteDance AI Lab*** (supervised by Mr.WANG Yang and [Dr.Hang LI](https://www.linkedin.com/in/hang-li-84aa6314/?originalSubdomain=cn), director of ByteDance Research), ***Reefknot Investment*** (co-supervised by [Mr.Marc DRAGON](https://reefknotinvestments.com/team/marc-dragon/), managing director of Reefknot, and [Prof.Wei Ngan CHIN](https://www.comp.nus.edu.sg/~chinwn/), vice dean of SoC, NUS), and ***University of California, Berkeley*** (supervised by [Dr.Qing ZHU](https://bids.berkeley.edu/people/qing-zhu), research scientist at Lawrence Berkeleey National Laboratory).

My research interests include ***natural language processing <img src='./images/text-mining.png' style='height: 1.5em;'>, multimodal representation learning <img src='./images/multimedia.png' style='height: 1.5em;'>, data mining applications including urban computing <img src='./images/infrastructure.png' style='height: 1.5em;'> and recommendation systems <img src='./images/rating.png' style='height: 1.5em;'>***. Look forward to any academic collaboration.



<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!--
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📖 Education
- *Now*, PhD, ***Hong Kong University of Science and Technology***.
- *Sep 2021 - Jul 2023*, Master, ***National University of Singapore*** <img src='./images/NUS.png' style='height: 1.5em;'>.
- *Sep 2017 - Jun 2021*, Undergraduate, ***Hong Kong Baptist University*** <img src='./images/HKBU.png' style='width: 6em;'> (President's Honour Roll <img src='./images/certificate.png' style='height: 1.5em;'>).

# 📝 Publications
**Note**: \* as Co-first Author; † as Corresponding Author

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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/multimodal_survey_InformationFusion24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Learning for Cross-Domain Data Fusion in Urban Computing: Taxonomy, Advances, and Outlook](https://arxiv.org/abs/2402.19348)

Xingchen Zou\*, **<u>Yibo Yan</u>**\*, Xixuan Hao, Yuehong Hu, Haomin Wen, Erdong Liu, Junbo Zhang, Yong Li, Tianrui Li, Yu Zheng, Yuxuan Liang†

- First comprehensive survey that systematically reviews studies on deep learning-based multimodal and multi-source data fusion models in urban computing.

Under Review

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/urbanvlp_kdd24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UrbanVLP: A Multi-Granularity Vision-Language Pre-Trained Model for Urban Indicator Prediction](https://arxiv.org/abs/2403.16831)

Xixuan Hao, Wei Chen, **<u>Yibo Yan</u>**, Siru Zhong, Kun Wang, Qingsong Wen, Yuxuan Liang†

- First urban region representation learning framework that explores multi-granularity cross-modal alignment.

Under Review

</div>
</div>



# 💻 Work Experience
<!-- - *Feb 2024 - Now*, ***LLM Group, Institute for Advanced Algorithms Research***, Shanghai/Remote. <img src='./images/IAAR.png' style='width: 6em;'>
  - **Focus**: LLM Hallucination Mitigation
  - **Supervisors**: Dr.Zhiyu LI (Mentor of LLM Team) and [Dr.Feiyu XIONG](https://scholar.google.com/citations?user=GOKgLdQAAAAJ&hl=en) (Director of LLM Group)
  - **Achievement**: ongoing project -->

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
- *2023,* Silver Medal <img src='./images/silver-medal.png' style='height: 1.5em;'>, OTTO - Multi-Objective Recommender System, Kaggle Competition.
- *2023,* Silver Medal <img src='./images/silver-medal.png' style='height: 1.5em;'>, Stable Diffusion - Image to Prompts, Kaggle Competition.
- *2021,* Best Undergraduate Thesis (Remote Sensing Track) <img src='./images/certificate.png' style='height: 1.5em;'>
- *2019-2020, 2020-2021,* First-class Academic Award <img src='./images/star-medal.png' style='height: 1.5em;'>, HKBU
- *2017-2018, 2018-2019,* Second-class Academic Award <img src='./images/silver-medal.png' style='height: 1.5em;'>, HKBU


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->


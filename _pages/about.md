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

**Yuqi Zhao** is a lecturer and postdoctoral researcher at the School of Computer Science, Central China Normal University. Zhao received a Ph.D. in Software Engineering from Wuhan University in December 2023, under the supervision of Professor Bing Li, and joined CCNU in March 2024. Zhao's research interests include software engineering, services computing, and edge intelligence. Relevant work has been published in high-quality journals and conferences, such as **TOSEM**, **KBS**, **TNSM**, **ICWS**, **ICSOC**, and **IJCNN**.

Currently, Zhao is leading research projects funded by the **Hubei Provincial Natural Science Foundation**, **China Postdoctoral Science Foundation**, **National Postdoctoral Program**, and the **State Key Laboratory of Networking and Switching Technology**. Zhao has been recognized with several honors, including the **CCF Outstanding Doctoral Dissertation** (2025), **Outstanding Doctoral Dissertation** by the Wuhan Computer Software Engineering Society (2024), the **Distinguished Paper Award** at **ICSOC 2023**, and the **Best Student Paper Award** at **ICWS 2021**. Zhao has also guided students to win multiple national and provincial awards in competitions such as the **Challenge Cup**, **Internet+**, and the **National Computer System Capability Competition**.


Zhao has published more than 30 papers at top-tier international journals and conferences with total <a href='https://scholar.google.com/citations?user=qfstZDsAAAAJ'>google scholar citations <strong><span id='total_cit'>260+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=qfstZDsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Awarded **CCF Outstanding Doctoral Dissertation** by the CCF Service Computing Technical Committee.
- *2025.07*: &nbsp;🎉🎉 Guided students to win the **National First Prize** in the 19th "Challenge Cup" National College Student Extracurricular Academic Science and Technology Works Competition (AI+ Special Track).
- *2025.07*: &nbsp;🎉🎉 Guided students to win the **Provincial Gold Award** and **National Bronze Award** in the China International College Student Innovation Competition (Internet+).
- *2025.06*: &nbsp;🎉🎉 Multiple papers accepted to **TOSEM**, **KBS**, **ICWS**, **IJCNN**, **SMC**, and other top venues in 2025-2026.
- *2025.02*: &nbsp;🎉🎉 Received research grants from the **China Postdoctoral Science Foundation** (General Program) and **National Postdoctoral Program** (Category C).
- *2024.09*: &nbsp;🎉🎉 A paper co-authored with my undergraduate student as the first author is accepted to **ISPA 2024**.
- *2024.06*: &nbsp;🎉🎉 Our conference paper is accepted to **Internetware 2024**.
- *2023.12*: &nbsp;🎉🎉 Our research is accepted to the flagship software engineering conference **SANER 2024**.
- *2023.12*: &nbsp;🎉🎉 Our Low-Code Platform achieves the **Silver Award** in the 9th China International "**Internet Plus**" Innovation and Entrepreneurship Competition for College Students.
- *2023.11*: &nbsp;🎉🎉 Our research achieves the **Distinguished Paper Award** in **ICSOC 2023**.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICSOC 2023</div><img src='images/ICSOC-2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Deep Reinforcement Learning Approach for Online Microservice Deployment in Mobile Edge Computing](https://doi.org/10.1007/978-3-031-48424-7_10)

**Yuqi Zhao**, Jian Wang, Bing Li

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qfstZDsAAAAJ&citation_for_view=qfstZDsAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='qfstZDsAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes DDQN, a deep reinforcement learning approach to online microservice deployment. Specifically, DDQN leverages the Dueling DQN (Deep Q-Network) model to generate real-time microservice deployment plans.
</div>
</div>

- **[TOSEM'26]** A Task-oriented and View-invariant Failure Diagnosis Framework for Microservice-based Systems with Multimodal Data. Shuaiyu Xie, Jian Wang, Hanbin He, Zhihao Wang, Yuqi Zhao, Neng Zhang, Bing Li.

- **[SPE'26]** RGPRec: A RAG-enhanced GNN for Personalized Task Recommendations in Open-source Communities. Shiyu He, Yutao Ma, Yuqi Zhao.

- **[IJCNN'26]** CPGR-Mem: Cross-Platform Graph-based Routing Memory for Multimodal Intelligent Agents. Jiale Kong, Yuqi Zhao*.

- **[ICWS'25]** TDIC: Time-aware Disentanglement of Interest and Conformity in Mobile APP Recommendations. Qibo Li, Yuqi Zhao*, Yutao Ma.

- **[KBS'25]** Empirical Mode Decomposition with Multivariable Time Series Feature Learning for QoS Prediction. Yuqi Zhao, Bing Li, Jian Wang, Xiuqing Chen, Yiming Xiong, Zhen Zhang.

- **[TOSEM'25]** Assessing and Analyzing the Correctness of GitHub Copilot's Code Suggestions. Ran Mo, Dongyu Wang, Wenjing Zhan, Yingjie Jiang, Yepeng Wang, Yuqi Zhao, Zengyang Li, Yutao Ma.

- **[IJCNN'25]** SAMPLE: Spatiotemporal-Aware Microservice Pre-deployment with LLMs for Edge Computing. Zhixuan Wang, Shendong Gao, Yuqi Zhao*, Xiulong Yang, Yatong Wang.

- **[SMC'25]** MMNet: A Multi-Scale Multimodal Model for End-to-End Grouping of Fragmented UI Elements. Liuzhou Zhang, Yuanlei Wang, Yuqi Zhao*, Shuangshuang Tian.

- **[SMC'25]** KGCE: Knowledge-Augmented Dual-Graph Evaluator for Cross-Platform Educational Agent Benchmarking with Multimodal Language Models. Zixian Liu, Sihao Liu, Yuqi Zhao*.

- **[ICSS'25]** DIF-RS: A Graph-Based Diffusion Model for Service Request Scheduling in Edge Computing. Zhiwen Li, Yuqi Zhao*, Shiyu He, Boris Sedlak, Schahram Dustdar.

- **[ICONIP'25]** Enhancing Edge Microservice Deployment Efficiency with an LLM-empowered Multi-Agent Framework. Shendong Gao, Zhixuan Wang, Yuqi Zhao*, Zengyang Li.

- **[ISPA'25]** LMAPOI: An LLMs-Driven Multi-Agent Framework for Next POI Recommendation. Shendong Gao, Zhixuan Wang, Yuqi Zhao*.

- **[ISPA'25]** CoMaTS: a Collaborative Multi-Agent Framework for Edge Task Scheduling. Zhixuan Wang, Shendong Gao, Yuqi Zhao*.

- **[PRICAI'25]** DEIMerge: An Automatic Program Repair Framework Based on Multi-agent Collaboration and Intelligent Patch Merging. Chang Liang, Yuqi Zhao*, Ran Mo.

- **[ISPA'24]** TS-EoH: An Edge Server Task Scheduling Algorithm Based on Evolution of Heuristic. Yatong Wang, Yuchen Pei, Yuqi Zhao*.

- **[JSS'24]** MicroIRC: Instance-level Root Cause Localization for Microservice Systems. Yuhan Zhu, Jian Wang, Bing Li, Yuqi Zhao, Zekun Zhang, Yiming Xiong, Shiping Chen.

- **[Internetware'24]** MobileEdgeSim: A Tool for Simulating Microservice-Oriented Mobile Edge Computing. Yuqi Zhao, Shiyu He, Qibo Li, Yuchen Pei, Yutao Ma.

- **[TNSM'24]** Attention-Based Deep Reinforcement Learning for Edge User Allocation. Jiaxin Chang, Bing Li, Jian Wang, Yuqi Zhao.

- **[SANER'24]** Code Reviewer Recommendation Based on a Hypergraph with Multiplex Relationships. Yu Qiao, Jian Wang, Can Cheng, Wei Tang, Peng Liang, *Yuqi Zhao* and Bing Li.

- **[ICSOC'23]** A Deep Reinforcement Learning Approach for Online Microservice Deployment in Mobile Edge Computing. Yuqi Zhao, Jian Wang and Bing Li. (Distinguished Paper Award)

- **[ICWS'23]** A Deep Reinforcement Learning-Based Pointer Scoring Network for Edge Task Scheduling. Yuqi Zhao, Delun Jiang, Bing Li, Jian Wang, Lei Fu and Duantengchuang Li.

- **[KBS'22]** Integrating Reinforcement Learning with Pointer Network for Service Scheduling in Edge Computing. Yuqi Zhao, Bing Li, Jian Wang, Delun Jiang, Duantengchuan Li.

- **[ICWS'21]** Microservice Pre-Deployment Based on Mobility Prediction and Service Composition in Edge. Jiale Deng, Bing Li, Jian Wang, Yuqi Zhao. (Best Student Paper Award)

- **[ICWS'20]** Integrating EMD with Multivariate LSTM for Time Series QoS Prediction. Xiuqing Chen, Bing Li, Jian Wang, Yuqi Zhao, Yiming Xiong.

- **[JCST'17]** Developer Role Evolution in Open Source Software Ecosystem: An Explanatory Study on GNOME. Can Cheng, Bing Li, Zengyang Li, Yuqi Zhao, Feng-Ling Liao.


# 🎖 Honors and Awards

- *2025*: &nbsp;🎉🎉 **CCF Outstanding Doctoral Dissertation**, CCF Service Computing Technical Committee.
- *2024*: &nbsp;🎉🎉 **Outstanding Doctoral Dissertation**, Wuhan Computer Software Engineering Society.
- *2023*: &nbsp;🎉🎉 **Distinguished Paper Award**, ICSOC 2023.
- *2023*: &nbsp;🎉🎉 **Silver Award**, 9th China International "Internet+" Innovation and Entrepreneurship Competition for College Students (National).
- *2022*: &nbsp;🎉🎉 **3551 Talents** in Optics Valley.
- *2021*: &nbsp;🎉🎉 **Best Student Paper Award**, ICWS 2021.


# 🔬 Research Projects

- **《低资源-高需求时空错配驱动的边缘服务智能供给研究》**, Hubei Provincial Natural Science Foundation (General Program), Principal Investigator.
- **《面向具身智能的物理一致性可交互训练数据生成服务技术》**, State Key Laboratory of Networking and Switching Technology (Open Fund), Principal Investigator.
- **《资源失衡环境下教育情境感知的智能服务供给研究》**, China Postdoctoral Science Foundation (General Program), Principal Investigator.
- **《资源失衡条件下教育情境感知智能化供给机制研究》**, National Postdoctoral Program (Category C), Principal Investigator.
- **《面向不确定性需求的认知服务构造与演化机理》**, National Natural Science Foundation of China (Key Program, 62032016), Participant.
- **《价值驱动的软件服务持续迭代演化机理与关键技术》**, National Natural Science Foundation of China (Key Program, 61832014), Participant.
- **《跨界服务设计方法与关键技术》**, National Key R&D Program of China (2017YFB1400602), Participant.
- **《网络大数据的数据保护与隐私保护》**, National Key R&D Program of China (2016YFB0800401), Participant.


# 🏆 Student Competition Guidance

- *2025*: &nbsp;🎉🎉 **National First Prize**, 19th "Challenge Cup" National College Student Extracurricular Academic Science and Technology Works Competition (AI+ Special Track).
- *2025*: &nbsp;🎉🎉 **Provincial Gold Award** and **National Bronze Award**, China International College Student Innovation Competition (Internet+).
- *2024*: &nbsp;🎉🎉 **Provincial Gold Award** and **National Silver Award**, "Challenge Cup" China College Students' Entrepreneurship Competition.
- *2024*: &nbsp;🎉🎉 **National First Prize**, National Computer System Capability Competition - Intelligent System Innovation Design Competition (Xiaomi Cup).
- *2025*: &nbsp;🎉🎉 **National Second Prize**, Huawei ICT Competition Programming Track.


# 🎓 Teaching
- *2024.09 - 2025.01*, **Operating Systems**, Undergraduate Course, School of Computer Science, Central China Normal University.


# 📖 Educations
- *2018.09 -- 2023.12*, Wuhan University (WHU), *Ph.D student* in Software Engineering (SE). 
- *2015.09 -- 2018.06*, Wuhan University (WHU), *Master student* in Software Engineering (SE). 
- *2011.09 -- 2015.06*, Wuhan University (WHU), *B.S.* in Spatial Information and Digital Technology (SIDT), World Ranking First. 


# 💬 Invited Talks
- *2023.11*, A Deep Reinforcement Learning Approach to Online Microservice Deployment in Mobile Edge Computing. ICSOC 2023, Roma, Italy. 
- *2023.06*, A Deep Reinforcement Learning-Based Pointer Scoring Network for Edge Task Scheduling. ICWS 2023, Chicago, USA  \| [\[video\]](https://github.com/)

# 🏢 Industrialization

- *2018.11 - Current*, [HorseCoder](https://www.horsecoder.com/), Wuhan, China. Founder & CEO. HorseCoder is an AI-driven enterprise-level code generation platform, leveraging large language models to provide intelligent code assistance, automated code generation, and software development acceleration solutions for enterprise clients.
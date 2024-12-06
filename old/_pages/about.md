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

[//]: # (Hello, I'm Yue Huang, currently a fourth-year undergraduate student at [Sichuan University]&#40;https://www.scu.edu.cn/&#41;.)

[//]: # ()
[//]: # (I am currently a visiting student at LAIR LAB, [Lehigh University]&#40;https://www.lehighuniversity.cn/&#41;, under the supervision of [Prof. Lichao Sun]&#40;https://lichao-sun.github.io/&#41;. During this time, I also receive guidance from Prof. [Philip S. Yu]&#40;https://scholar.google.com/citations?user=D0lL1r0AAAAJ&hl=en&#41;. Before this, I received guidance from [Prof. Tang Jie]&#40;https://keg.cs.tsinghua.edu.cn/jietang/&#41; of Tsinghua University and collaborated with [Dr. Xiao Liu]&#40;https://scholar.google.com.hk/citations?user=VKI8EhUAAAAJ&hl=zh-CN&#41;. I was fortunate to collaborate with [Prof. Cheng Huang]&#40;https://chenghuang.org/index.html&#41; at Sichuan University.)

[//]: # ()
[//]: # ()
Yue Huang (黄跃, Yue pronounced similar to "your") is a PhD student in [MINE Lab](https://mine-lab-nd.github.io/) of Computer Science and Engineering (CSE) at the [University of Notre Dame](https://www.nd.edu/) starting Fall 2024, supervised by [Prof. Xiangliang Zhang](https://scholar.google.com/citations?user=BhRJe4wAAAAJ&hl=en). Yue obtained a bachelor's degree from [Sichuan University](https://www.scu.edu.cn/) in 2024. Previously, Yue was a visiting student under the guidance of [Prof. Lichao Sun](https://lichao-sun.github.io/). This experience was enhanced by mentorship from [Prof. Philip S. Yu](https://scholar.google.com/citations?user=D0lL1r0AAAAJ&hl=en). Earlier before, Yue worked under [Prof. Tang Jie](https://keg.cs.tsinghua.edu.cn/jietang/) and [Dr. Xiao Liu](https://scholar.google.com.hk/citations?user=VKI8EhUAAAAJ&hl=zh-CN) at Tsinghua University.

[//]: # (Yue has published papers at several top conferences in computer science, including ICML, ICLR, ACL, NAACL, WWW and others. Additionally, Yue has served as a reviewer for several journals and conferences.)

> I am seeking potential research collaborations and the position of industry research intern. If you are interested, please [contact me](&#40;mailto:howiehwong@gmail.com&#41;).

<!-- > We are hosting [IEEE CS North America Student Challenge 2024](https://www.kaggle.com/competitions/ieee-cs-global-student-challenge-2024) from Sep 30th to Oct 21. Welcome to participate the competition on *Inferring User Latent Preference from Conversations with LLM*, and win the First Prize: 2,500 USD; Second Prize: 1,500 USD; Third Prize: 500 USD. -->

# 💡 Research

My research is centered on three pivotal questions:

1. **How can we deepen our understanding of the trustworthiness of foundational generative models?** This line of inquiry seeks to develop robust frameworks for evaluating trustworthiness and to identify strategies for enhancing the trustworthiness of these models within specific application domains. This includes: [TrustLLM (ICML'24)](https://arxiv.org/abs/2401.05561), [LLM-as-a-Coauthor (NAACL'24)](https://aclanthology.org/2024.findings-naacl.29/), [Attack LLM Judge (ACM CCS'24)](https://arxiv.org/abs/2403.17710), [FakeGPT (WWW'24)](https://dl.acm.org/doi/abs/10.1145/3589335.3651509), [Multilingual Alignment (EMNLP'24)](https://arxiv.org/abs/2406.14721), [HonestLLM (NeurIPS'24)](https://arxiv.org/abs/2406.00380), [TrustNLP@NAACL'24](https://arxiv.org/abs/2407.16686), and [ObscurePrompt](https://arxiv.org/abs/2406.13662).


2. **Is there a superior approach to achieving Artificial General Intelligence (AGI)?** This research emphasizes data-centric methods to enable scalable model alignment and evolution, ensuring that they adhere to human values and ethical paradigms throughout the development process. This includes: [AlignBench (ACL'24)](https://arxiv.org/abs/2311.18743), [Multilingual Alignment (EMNLP'24)](https://arxiv.org/abs/2406.14721), and [UniGen](https://arxiv.org/abs/2406.18966).

3. **To what extent can current AI technologies effectively benefit downstream applications?** This research area critically assesses the practical impact of generative models, with a particular focus on their application and AI4Science, exploring its transformative potential and interdisciplinary contributions in fields such as agentic models, social sciences, and beyond. This includes: [MetaTool (ICLR'24)](https://arxiv.org/abs/2310.03128), [PsychometricBench](https://arxiv.org/abs/2406.17675), [AwareBench](https://arxiv.org/abs/2401.17882) and [GUI-World](https://arxiv.org/abs/2406.10819).

# 🔥 News
- *2024.09*  &nbsp;🎉🎉 [HonestLLM](https://arxiv.org/abs/2406.00380) has been accepted by NeurIPS 2024! Congratulations to [Chujie](https://flossiee.github.io/)! Another paper has been accepted by main conference of EMNLP 2024!
- *2024.08* &nbsp;🎉🎉 [Attack LLM-as-a-Judge](https://arxiv.org/abs/2403.17710) has been accepted by ACM CCS 2024!
- *2024.07* &nbsp;🎉🎉 OpenAI’s Researcher Access Program is Awarded.
- *2024.05* &nbsp;🎉🎉 [TrustLLM](https://trustllmbenchmark.github.io/TrustLLM-Website/) has been accepted by ICML 2024! Thanks to all the collaborators. See you in Vienna! Another paper has been accepted by main conference of ACL 2024!
- *2024.03* &nbsp;🎉🎉 One paper has been accepted by NAACL 2024! Congratulations to [Qihui](https://mask-hui.github.io/), [Chujie](https://flossiee.github.io/) and [Dongping](https://dongping-chen.github.io/)! Another paper has been accepted as a short paper of WWW 2024!
- *2024.02* &nbsp;🎉🎉 Thanks for the invited talk on TrustLLM Project! @ [IBM Research](https://research.ibm.com/)
- *2024.01* &nbsp;🎉🎉 [MetaTool](https://arxiv.org/abs/2310.03128) has been accepted by ICLR 2024! Finish research internship at Tsinghua University KEG & Zhipu Inc.!


# 📝 Selected Publications 

See more publications in my [Google Scholar](https://scholar.google.com/citations?user=HvzvvqQAAAAJ&hl=en)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/metatool_00.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

![ICLR 2024](https://img.shields.io/badge/ICLR-2024-7740bd) [MetaTool Benchmark for Large Language Models: Deciding Whether to Use Tools and Which to Use](https://arxiv.org/abs/2310.03128)

**Yue Huang**, Jiawen Shi, Yuan Li, Chenrui Fan, Siyuan Wu, Qihui Zhang, Yixin Liu, Pan Zhou, Yao Wan, Neil Zhenqiang Gong, Lichao Sun

[**Code**](https://github.com/HowieHwong/MetaTool) [![](https://img.shields.io/github/stars/HowieHwong/MetaTool)](https://github.com/HowieHwong/MetaTool)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/trustllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

![ICML 2024](https://img.shields.io/badge/ICML-2024-A84111) [TrustLLM: Trustworthiness in Large Language Models](https://proceedings.mlr.press/v235/huang24x.html)

**Yue Huang** \*, Lichao Sun \*, Haoran Wang, Siyuan Wu, Qihui Zhang, Chujie Gao, Yixin Huang, Wenhan Lyu, Yixuan Zhang, Xiner Li, Zhengliang Liu, Yixin Liu, Yijue Wang, Zhikun Zhang, Bhavya Kailkhura, Caiming Xiong, et al. (*: co-corresponding authors)


[**Toolkit & Code**](https://github.com/HowieHwong/TrustLLM) [![](https://img.shields.io/github/stars/HowieHwong/TrustLLM)](https://github.com/HowieHwong/TrustLLM)
[![ibm](https://img.shields.io/badge/Invited%20Talk-IBM%20Research-blue)](https://research.ibm.com/)
[![huggingface](https://img.shields.io/badge/huggingface-Daily%20Paper-yellow)]()
[![report](https://img.shields.io/badge/Reported%20By-机器之心-brown)](https://mp.weixin.qq.com/s/iah6Wz0VsMsJx_wCtgirBw) 
[![Website](https://img.shields.io/badge/Website-%F0%9F%8C%8D-blue)](https://trustllmbenchmark.github.io/TrustLLM-Website/)
[![Dataset](https://img.shields.io/badge/Dataset-%F0%9F%92%BE-green)](https://huggingface.co/datasets/TrustLLM/TrustLLM-dataset)
[![Data Map](https://img.shields.io/badge/Data%20Map-%F0%9F%8D%9F-orange)](https://atlas.nomic.ai/map/f64e87d3-c769-4a90-b15d-9dc833acc8ba/8e9d7045-503b-4ba0-bc64-7201cb7aacee?xs=-16.14086&xf=-1.88776&ys=-7.54937&yf=3.88213)
[![Leaderboard](https://img.shields.io/badge/Leaderboard-%F0%9F%9A%80-brightgreen)](https://trustllmbenchmark.github.io/TrustLLM-Website/leaderboard.html)
[![Toolkit Document](https://img.shields.io/badge/Toolkit%20Document-%F0%9F%93%9A-blueviolet)](https://howiehwong.github.io/TrustLLM/)
[![Downloads](https://static.pepy.tech/badge/trustllm)](https://pepy.tech/project/trustllm)
[![Metioned](https://img.shields.io/badge/Metioned%20By-DHS-red)](https://www.hsgac.senate.gov/wp-content/uploads/2024.06.11-Hedge-Fund-Use-of-AI-Report.pdf)

</div>
</div>

- ![CCS 2024](https://img.shields.io/badge/CCS-2024-c821f3) [Optimization-based Prompt Injection Attack to LLM-as-a-Judge](https://arxiv.org/abs/2403.17710) Jiawen Shi, Zenghui Yuan, Yinuo Liu, **Yue Huang**, Pan Zhou, Lichao Sun, Neil Zhenqiang Gong
- ![ACL 2024](https://img.shields.io/badge/ACL-2024-e87213) [AlignBench: Benchmarking Chinese Alignment of Large Language Models](https://arxiv.org/abs/2311.18743) Xiao Liu, Xuanyu Lei, Shengyuan Wang, **Yue Huang**, Zhuoer Feng, et al.
- ![NAACL 2024](https://img.shields.io/badge/NAACL-2024-f24b2e) [LLM-as-a-Coauthor: Can Mixed Human-Written and Machine-Generated Text Be Detected?](https://arxiv.org/abs/2401.05952) Qihui Zhang, Chujie Gao, Dongping Chen, **Yue Huang**, et al.
- ![EMNLP 2024](https://img.shields.io/badge/EMNLP-2024-e87213) [1+1>2: Can Large Language Models Serve as Cross-Lingual Knowledge Aggregators?](https://arxiv.org/abs/2406.14721) **Yue Huang**, Chenrui Fan, Yuan Li, Siyuan Wu, et al.
- ![NeurIPS 2024](https://img.shields.io/badge/NeurIPS-2024-A84111) [The Best of Both Worlds: Toward an Honest and Helpful Large Language Model](https://arxiv.org/abs/2406.00380) Chujie Gao, Qihui Zhang, Dongping Chen, **Yue Huang**\*, Siyuan Wu, et al. (*: corresponding author)
- ![WWW 2024](https://img.shields.io/badge/WWW-2024-c7be87) [From Creation to Clarification: ChatGPT's Journey Through the Fake News Quagmire]() **Yue Huang**, Kai Shu, Philip S. Yu, Lichao Sun
- ![ScureComm 2023](https://img.shields.io/badge/SecureComm-2023-87acc7) [CyberEA: An Efficient Entity Alignment Framework for Cybersecurity Knowledge Graph](https://securecomm.eai-conferences.org/2023/full-program-2/) **Yue Huang**, Yongyan Guo, Cheng Huang



[//]: # (# ⚙️ Project)

[//]: # ()
[//]: # (**TrustLLM: Trustworthiness in Large Language Models**)

[//]: # ()
[//]: # ()
[//]: # ()
[//]: # ()
[//]: # ()
[//]: # ()
[//]: # ()
[//]: # (- We have proposed a set of guidelines based on a comprehensive literature review for evaluating the trustworthiness of LLMs, which is a taxonomy encompassing eight aspects, including *truthfulness, safety, fairness, robustness, privacy, machine ethics, transparency, and accountability*.)

[//]: # (- We have established a benchmark for six of these aspects due to the difficulty of benchmarking transparency and accountability. This is the first comprehensive and integrated benchmark comprising over 18 subcategories, covering more than 30 datasets and 16 LLMs, including proprietary and open-weight ones.)

[//]: # (- We obtain empirical findings from the results of our experiments, which provide valuable insights for future research.)

[//]: # (📣 **Welcome your Contribution**)

[//]: # ()
[//]: # (We welcome your contributions, including but not limited to the following:)

[//]: # ()
[//]: # (- New benchmark datasets of trustworthy dimension)

[//]: # (- Research on trustworthy issues of LLM)

[//]: # (- Improvements to the [trustllm toolkit]&#40;https://github.com/HowieHwong/TrustLLM&#41;)


# 🎤 Talk
- *2024.02* Invited Talk: Trustworthiness in Large Language Models @ [IBM Research](https://research.ibm.com/)
- *2024.07* Invited Talk: Bias of Large Language Models @ TUM

# 🎖 Honors and Awards
- *2024.07* OpenAI’s Researcher Access Program and API
- *2024.01* Microsoft Accelerate Foundation Models Research is awarded (Project: [TrustLLM](https://github.com/HowieHwong/TrustLLM) & Lead PI: [Lichao Sun](https://lichao-sun.github.io/))

# 📖 Educations

- *2024.09 - Present*, Ph.D, <img src='images/Notre_Dame.png' style='width: 1.2em;'> [University of Notre Dame](https://www.nd.edu/) 
- *2020.09 - 2024.06*, BEng., <img src='images/scu.png' style='width: 1.2em;'> [Sichuan University](https://www.scu.edu.cn/) 

# 💻 Internships

- *2023.09 - 2024.01*, Research Intern at <img src='images/thu.png' style='width: 1.2em;'> Tsinghua University KEG & Zhipu AI Inc.


[//]: # (<a href='https://mapmyvisitors.com/web/1bw5t'  title='Visit tracker'><img src='https://mapmyvisitors.com/map.png?cl=080808&w=300&t=tt&d=SMKWP8kMQ7_OcRboy6QXkVzuFECqnAdtI6Q_GNsItFk&co=ffffff&ct=808080'/></a>)
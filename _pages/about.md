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
Yue Huang (黄跃, Yue pronounced similar to "your") is an upcoming PhD student in Computer Science and Engineering (CSE) at the [University of Notre Dame](https://www.nd.edu/) starting Fall 2024, supervised by [Prof. Xiangliang Zhang](https://scholar.google.com/citations?user=BhRJe4wAAAAJ&hl=en). Yue obtained a bachelor's degree from [Sichuan University](https://www.scu.edu.cn/) in 2024.

Previously, Yue was a visiting student at the LAIR Lab, [Lehigh University](https://www.lehighuniversity.cn/), under the guidance of [Prof. Lichao Sun](https://lichao-sun.github.io/). This experience was enhanced by mentorship from [Prof. Philip S. Yu](https://scholar.google.com/citations?user=D0lL1r0AAAAJ&hl=en). Earlier before, Yue worked under [Prof. Tang Jie](https://keg.cs.tsinghua.edu.cn/jietang/) and [Dr. Xiao Liu](https://scholar.google.com.hk/citations?user=VKI8EhUAAAAJ&hl=zh-CN) at Tsinghua University.

[//]: # (Yue has published papers at several top conferences in computer science, including ICML, ICLR, ACL, NAACL, WWW and others. Additionally, Yue has served as a reviewer for several journals and conferences.)

> I am seeking potential research collaborations and the position of industry research intern. If you are interested, please [contact me](&#40;mailto:howiehwong@gmail.com&#41;).


# 💡 Research Interest

- Trustworthy AI: safety, truthfulness, fairness, robustness, privacy and machine ethics of AI model.
- Data-Centric and Human-Centered LLMs: Evaluation of LLMs, synthetic data for LLMs, LLM-based agents and LLM alignment.
- XAI: Computational social science, cybersecurity, and human computer interaction.


# 🔥 News
- *2024.08.19*: &nbsp;🎉🎉 [Attack LLM-as-a-Judge](https://arxiv.org/abs/2403.17710) has been accepted by ACM CCS 2024!
- *2024.07.28*: &nbsp;🎉🎉 OpenAI’s Researcher Access Program is Awarded.
- *2024.05.16*: &nbsp;🎉🎉 One paper has been accepted by main conference of ACL 2024!
- *2024.05.02*: &nbsp;🎉🎉 [TrustLLM](https://trustllmbenchmark.github.io/TrustLLM-Website/) has been accepted by ICML 2024! Thanks to all the collaborators. See you in Vienna!
- *2024.03.14*: &nbsp;🎉🎉 One paper has been accepted by NAACL 2024! Congratulations to [Qihui](https://mask-hui.github.io/), [Chujie](https://flossiee.github.io/) and [Dongping](https://dongping-chen.github.io/)!
- *2024.03.05*: &nbsp;🎉🎉 One paper has been accepted as a short paper of WWW 2024!
- *2024.02.08*: &nbsp;🎉🎉 Thanks for the invited talk on TrustLLM Project! @ [IBM Research](https://research.ibm.com/)
- *2024.01.15*: &nbsp;🎉🎉 [MetaTool](https://arxiv.org/abs/2310.03128) has been accepted by ICLR 2024!
- *2024.01.13*: &nbsp;🎉🎉 Finish research internship at Tsinghua University KEG & Zhipu Inc.!


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

![ICML 2024](https://img.shields.io/badge/ICML-2024-A84111) [TrustLLM: Trustworthiness in Large Language Models](https://arxiv.org/abs/2401.05561)

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

</div>
</div>


- ![ACL 2024](https://img.shields.io/badge/ACL-2024-e87213) [AlignBench: Benchmarking Chinese Alignment of Large Language Models](https://arxiv.org/abs/2311.18743) Xiao Liu, Xuanyu Lei, Shengyuan Wang, **Yue Huang**, Zhuoer Feng, et al.
- ![NAACL 2024](https://img.shields.io/badge/NAACL-2024-f24b2e) [LLM-as-a-Coauthor: Can Mixed Human-Written and Machine-Generated Text Be Detected?](https://arxiv.org/abs/2401.05952) Qihui Zhang, Chujie Gao, Dongping Chen, **Yue Huang**, et al.
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

- *2024.09 - 2029.06 (Expected)*, Ph.D, <img src='images/Notre_Dame.png' style='width: 1.2em;'> [University of Notre Dame](https://www.nd.edu/) 
- *2020.09 - now*, BEng., <img src='images/scu.png' style='width: 1.2em;'> [Sichuan University](https://www.scu.edu.cn/) 

# 💻 Internships

- *2023.09 - 2024.01*, Research Intern at <img src='images/thu.png' style='width: 1.2em;'> Tsinghua University KEG & Zhipu AI Inc.


<a href='https://mapmyvisitors.com/web/1bw5t'  title='Visit tracker'><img src='https://mapmyvisitors.com/map.png?cl=080808&w=300&t=tt&d=SMKWP8kMQ7_OcRboy6QXkVzuFECqnAdtI6Q_GNsItFk&co=ffffff&ct=808080'/></a>
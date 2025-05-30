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

I am a third-year PhD student at the Language Computing and Machine Learning Group ([Lanco](https://lancopku.github.io/)), Institute of Computational Linguistics (National Key Laboratory for Multimedia Information Processing), School of Computer Science, Peking University. I am supervised by Prof. [Xu Sun](https://xusun26.github.io/). 

I received the degree of Master of Science in Engineering from the University of Chinese Academy of Sciences (UCAS), supervised by Prof. [Zheng Lin](https://teacher.ucas.ac.cn/~0023257).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# Research Interests
* Multimodal Large Language Models
* Video Understanding
* Natural Language Processing
* Pre-trained Language Model Compression


# 📝 Selected Publications ([Full List](https://scholar.google.com/citations?user=pLOm4rYAAAAJ&hl=en)<a href='https://scholar.google.com/citations?user=pLOm4rYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>) 

## Vision and Language

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/t3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Temporal Reasoning Transfer from Text to Video](https://arxiv.org/pdf/2410.06166)

Lei Li*, **Yuanxin Liu**\*, Linli Yao, Peiyuan Zhang, Chenxin An, Lean Wang, Xu Sun, Lingpeng Kong, Qi Liu

[**Project**](https://video-t3.github.io/) | [**Paper**](https://arxiv.org/abs/2410.06166) | [**Code**](https://github.com/llyx97/video-t3)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024 Findings</div><img src='images/tempcompass.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TempCompass: Do Video LLMs Really Understand Videos?](https://arxiv.org/pdf/2403.00476.pdf)

**Yuanxin Liu**\*, Shicheng Li*, Yi Liu, Yuxiang Wang, Shuhuai Ren, Lei Li, Sishuo Chen, Xu Sun, Lu Hou

[**Project**](https://llyx97.github.io/tempcompass/) | [**Paper**](https://arxiv.org/abs/2403.00476) | [**Code**](https://github.com/llyx97/TempCompass)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023 Track Datasets and Benchmarks</div><img src='images/fetv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FETV: A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation](https://arxiv.org/abs/2311.01813)

**Yuanxin Liu**, Lei Li, Shuhuai Ren, Rundong Gao, Shicheng Li, Sishuo Chen, Xu Sun and Lu Hou

[**Paper**](https://arxiv.org/abs/2311.01813) | [**Code**](https://github.com/llyx97/FETV)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/videoreasonbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VIDEOREASONBENCH: Can MLLMs Perform Vision-Centric Complex Video Reasoning?](https://arxiv.org/pdf/2505.23359)

**Yuanxin Liu**, Kun Ouyang, Haoning Wu, Yi Liu, Lin Sui, Xinhao Li, Yan Zhong, Y. Charles, Xinyu Zhou, Xu Sun

[**Project**](https://llyx97.github.io/video_reason_bench/) | [**Paper**](https://arxiv.org/pdf/2505.23359) | [**Code**](https://github.com/llyx97/video_reason_bench)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/spacer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpaceR: Reinforcing MLLMs in Video Spatial Reasoning](https://arxiv.org/pdf/2504.01805v2)

Kun Ouyang, **Yuanxin Liu**, Haoning Wu, Yi Liu, Hao Zhou, Jie Zhou, Fandong Meng, Xu Sun

[**Paper**](https://arxiv.org/pdf/2504.01805) | [**Code**](https://github.com/OuyangKun10/SpaceR)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/mia.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Aligning visual regions and textual concepts for semantic-grounded image representations](https://papers.nips.cc/paper/2019/hash/9fe77ac7060e716f2d42631d156825c0-Abstract.html)

Fenglin Liu\*, **Yuanxin Liu**\*, Xuancheng Ren\*, Xiaodong He, Xu Sun

[**Paper**](https://papers.nips.cc/paper/2019/hash/9fe77ac7060e716f2d42631d156825c0-Abstract.html)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='images/kimivl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KIMI-VL TECHNICAL REPORT](https://arxiv.org/pdf/2504.07491)

Kimi Team

[**Paper**](https://arxiv.org/pdf/2504.07491) | [**Code**](https://github.com/MoonshotAI/Kimi-VL)
</div>
</div>

## Pre-trained Language Model Compression

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/srnet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Win-win Deal: Towards Sparse and Robust Pre-trained Language Models](https://arxiv.org/abs/2210.05211)

**Yuanxin Liu**, Fandong Meng, Zheng Lin, Jiangnan Li, Peng Fu, Yanan Cao, Weiping Wang and Jie Zhou

[**Paper**](https://arxiv.org/abs/2210.05211) | [**Code**](https://github.com/llyx97/sparse-and-robust-PLM)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2022</div><img src='images/tamt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning to Win Lottery Tickets in BERT Transfer via Task-agnostic Mask Training](https://aclanthology.org/2022.naacl-main.428/)

**Yuanxin Liu**, Fandong Meng, Zheng Lin, Peng Fu, Yanan Cao, Weipinng Wang and Jie Zhou

[**Paper**](https://aclanthology.org/2022.naacl-main.428/) | [**Code**](https://github.com/llyx97/TAMT) | [**Blog**](https://mp.weixin.qq.com/s/Wd_IWHqJnaonilyVI3pPGA)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2021</div><img src='images/mud.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Marginal Utility Diminishes: Exploring the Minimum Knowledge for BERT Knowledge Distillation](https://aclanthology.org/2021.acl-long.228/)

**Yuanxin Liu**, Fandong Meng, Zheng Lin, Weiping Wang and Jie Zhou

[**Paper**](https://aclanthology.org/2021.acl-long.228/) | [**Code**](https://github.com/llyx97/Marginal-Utility-Diminishes)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2021</div><img src='images/ROSITA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ROSITA: Refined BERT cOmpreSsion with InTegrAted techniques](https://arxiv.org/abs/2103.11367)

**Yuanxin Liu**, Zheng Lin, Fengcheng Yuan

[**Paper**](https://arxiv.org/abs/2103.11367) | [**Code**](https://github.com/llyx97/Rosita)
</div>
</div>


# 🎖 Honors and Awards
* **Outstanding Graduates of Beijing & UCAS**, 2022
* **CAS Presidential Excellent Scholarship**, CAS, 2022
* **National Scholarship for Master Students**, Ministry of Education of P.R. China, 2021
* **Merit Student**, UCAS, 2021
* **IIE Presidential Special Award**, IIE, CAS, 2020
* **Outstanding Graduates of Beijing**, Beijing Municipal Education Commission, 2019 

# 📖 Educations
* **Sept. 2022 - Now**: PhD student, majoring in Computer Software and Theory, Peking University.
* **Sept. 2019 - Jun. 2022**: Master Student, majoring in Computer Applied Technology, Institute of Information Engineering (IIE), CAS & UCAS.
* **Sept. 2015 - Jun. 2019**: Bachelor of Communication Engineering, Beijing University of Posts and Telecommunications.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
* Research Intern at Moonshot AI, Mar. 2025 - Now. Mentor: [Haoning Wu](https://teowu.github.io/)
* Research Intern at ByteDance Seed, July. 2024 - Mar. 2025. Mentor: Haoyuan Guo and [Lu Jiang](http://www.lujiang.info/)
* Research Intern at WeChat AI, Tencent Inc., Oct. 2020 - Jun. 2022. Mentor: [Fandong Meng](https://fandongmeng.github.io/)

# Academic Service
* **Area Chair/Action Editor**: ACL ARR
* **Reviewer**: NeurIPS (2022, 2023, 2024), ICML (2022, 2023, 2024), ICLR (2024, 2025), EMNLP (2023), ACL (2023), CVPR (2024, 2025), Computational Linguistics
* **Teaching assistant**: Introduction to Natural Language processing (PKU, 2022 Fall), Natural Language processing (PKU, 2023 Fall)

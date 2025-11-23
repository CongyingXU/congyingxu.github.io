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

I am Congying (Alex) XU, a final year PhD student at HKUST, supervised by [Chair Prof. Shing-Chi CHEUNG](https://cse.hkust.edu.hk/~scc/) (IEEE Fellow), 
and a visiting scholar at CMU (Carnegie Mellon University), collaborating with [Prof. Christian Kästner](https://www.cs.cmu.edu/~ckaestne/index.html).

I am exploring research topics about **LLM-Empowered Software Engineering** and  **Trustworthy AI Systems**.
<!-- I am exploring research topics about **LLM-empowered metamorphic testing** ([ASE'24](https://arxiv.org/pdf/2408.15815), [TOSEM'24](https://dl.acm.org/doi/abs/10.1145/3656340)) and  **AI system engineering**. -->

Prior to this, I completed my Master's degree at Fudan University, supervised by [Prof. Bihuan CHEN](https://chenbihuan.github.io/) and [Prof. Xin PENG](https://cspengxin.github.io/) (College Deputy Dean). I completed my Bachelor's degree at Yangzhou University, where I was supervised by [Prof. Xiaobing SUN](https://risame.github.io/sun/index.html) (College Dean). <!-- During that time,  -->I explored topics about **software supply-chain** ([FSE'22](https://dl.acm.org/doi/abs/10.1145/3540250.3549125), [EMSE'22](https://link.springer.com/article/10.1007/s10664-022-10131-8), [FSE'20](https://dl.acm.org/doi/abs/10.1145/3368089.3409689), [ICSME'20 🏆](https://ieeexplore.ieee.org/abstract/document/9240619)), and **software analytics** ([ICSE'19-tool](https://www.sciencedirect.com/science/article/abs/pii/S0164121218300840), [JSS'18](https://www.sciencedirect.com/science/article/abs/pii/S0164121218300840) ).




# 🔥 News
- *2025.10*: &nbsp;✨ **I am officially on the job market (2026)**, seeking positions of **Research Scientist (Industry)** or **PostDoc Researcher(Academia)**. <br>
Here is my [[CV](../docs/CV_CongyingXU_PhD_HKUST.pdf)].
If you know of a postion that might be a match, or would like to hear more about my work, please feel free to reach out (📧: congying.xu@connect.ust.hk)!

# 📖 Educations
- *2022.09 - now*, PhD Student, **The Hong Kong University of Science and Technology**.
  * Thesis: [Automated and Effective Metamorphic Testing: Relation Discovery, Deduction, and Generation](../docs/Thesis.pdf)
- *2025.01 - 2025.06*, Visiting Scholar, **Carnegie Mellon University**.
- *2019.09 - 2022.06*, Master Degree, **Fudan University**.
- *2015.09 - 2019.06*, Bachelor Degree, **Yangzhou University**.


# 📝 Projects and Publications 

<!-- TODO: 
John's paper
 -->


### LLM Agent Safety

<!-- - ``To Appear`` *Discovering Silent Failures in LLM Agents via Metamorphic Testing* -->
- ``To Appear`` *Safe Tool Use for LLM Agents*



### LLM-Empowered Software Testing

- ``To Appear`` *Automated Metamorphic Test Generation* <br>
**Congying Xu**, Songqiang Chen, Hengcheng Zhu, Jiarong Wu, Valerio Terragni, Shing-Chi Cheung 

- ``ASE 2024`` *MR-Adopt: Automatic Deduction of Input Transformation Function for Metamorphic Testing* [[Paper](https://dl.acm.org/doi/abs/10.1145/3691620.3696020)] <br>
**Congying Xu**, Songqiang Chen, Jiarong Wu, Shing-Chi Cheung, Valerio Terragni, Hengcheng Zhu, Jialun Cao 

- ``TOSEM 2024`` *MR-Scout: Automated Synthesis of Metamorphic Relations from Existing Test Cases* [[Paper](https://dl.acm.org/doi/abs/10.1145/3656340)] <br>
**Congying Xu**, Valerio Terragni, Hengcheng Zhu, Jiarong Wu, Shing-Chi Cheung

### LLM-Empowered Code Translation and Generation

- ``To Appear`` *On Effective Semantic Translation for Code: A Study Based on Pseudocode* [[Paper](https://arxiv.org/pdf/2510.00920)] <br>
Songqiang Chen, **Congying Xu**, Jingyi Chen, Jialun Cao, Jiarong Wu, Shing-Chi Cheung

- ``TSE 2025`` *Question Selection for Multi-Modal Code Search Synthesis using Probabilistic Version Spaces* [[Paper](https://ieeexplore.ieee.org/abstract/document/10979773)] <br>
Jiarong Wu, Yanyan Jiang, Lili Wei, **Congying Xu**, Shing-Chi Cheung, Chang Xu


### Software Supply Chain Security

- ``FSE 2022`` *Tracking Patches for Open Source Software Vulnerabilities* [[Paper](https://dl.acm.org/doi/abs/10.1145/3540250.3549125)] <br>
**Congying Xu**, Bihuan Chen, Chenhao Lu, Kaifeng Huang, Xin Peng, Yang Liu

- ``EMSE 2022`` *Characterizing usages, updates and risks of third-party libraries in Java projects* [[Paper](https://link.springer.com/article/10.1007/s10664-022-10131-8)] <br>
Kaifeng Huang, Bihuan Chen, **Congying Xu**, Ying Wang, Bowen Shi, Xin Peng, Yijian Wu, Yang Liu

- 🏆 ``ICSME 2020`` *An Empirical Study of Usages, Updates and Risks of Third-Party Libraries in Java Projects.* [[Paper](https://ieeexplore.ieee.org/abstract/document/9240619)] <br>
Ying Wang, Bihuan Chen, Kaifeng Huang, Bowen Shi, **Congying Xu**, Xin Peng, Yijian Wu, Yang Liu

- ``FSE 2020`` *Interactive, Effort-aware Library Version Harmonization* [[Paper](https://dl.acm.org/doi/abs/10.1145/3368089.3409689)] <br>
Kaifeng Huang, Bihuan Chen, Bowen Shi, Ying Wang, **Congying Xu**, Xin Peng

### Recommendation System

- ``ICSE 2019`` *MULAPI: A Tool for API Method and Usage Location Recommendation* [[Paper](https://ieeexplore.ieee.org/abstract/document/8802650)] <br>
**Congying Xu**, Bosen Min, Xiaobing Sun, Jiajun Hu, Bin Li, Yucong Duan

- ``JSS 2018`` *MULAPI: Improving API method recommendation with API usage location* [[Paper](https://www.sciencedirect.com/science/article/pii/S0164121218300840)] <br>
**Congying Xu**, Xiaobing Sun, Bin Li, Xintong Lu, Hongjing Guo, 




# 🎖 Honors and Awards
- *2025*, Overseas Research Award, HKUST. 
- *2022.09 - now*, Postgraduate Studentship (PGS), HKUST. 
- *2019*, National Scholarship, Ministry of Education of China. 
- *2019*, Outstanding Graduates of Yangzhou University. 
- *2018*, First Prize·Blue Bridge Cup National Programming Competition, Jiangsu (Java).
- *2014*, First Prize·Chemistry Olympiad Contest, Jiangsu Province. 

# 🤝 Service
- Reviewer: TOSEM 2025, ASEJ 2025, AE@ISSRE 2024, AE@ISSRE 2023
- Co-Reviewer: FSE 2025, ASE 2025, ISSTA 2025
- Volunteer: FSE 2025, ASE 2021

# 🧑‍🏫 Teaching Experience
- COMP4633 Competitive Programming in Cybersecurity (Fall 2025–26)
- COMP3021 Java Programming (Fall 2024–25)
- COMP1021 Introduction to Computer Science (Python Programming) (Fall 2023-24)


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
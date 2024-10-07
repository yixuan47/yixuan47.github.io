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

I am a master student majoring in Control Engineering at Shanghai Jiao Tong University, with an anticipated graduation in March 2025.

I am now researching data-driven model predictive control for uncertain systems and working on developing various industrial control software.

I won the Outstanding Student Award(Top 3%) and First Prize Academic Scholarship in 2023 at SJTU and received the Outstanding Poster Paper Award from the Chinese Process Paper Congress in 2024(Top 3%).

My research interest includes data-driven techniques, robust control, model predictive control, distributed optimization, machine learning, and decision-making.

📧Please feel free to contact me for collaborations or inquiries: [niyixuan@sjtu.edu.com](mailto:niyixuan@sjtu.edu.com).


# 🔥 News
- *2022.02*: &nbsp; I have a paper accepted by CAC!🎉 
- *2022.02*: &nbsp; I receive the "Outstanding Poster Paper Award" from CPCC!😆
- *2022.06*: &nbsp; I graduate from BIT and will begin study at SJTU!🎓

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAC 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

The improvement of data selection method in data-driven model predictive control of uncertain systems
<!--(https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)-->

**Yixuan Ni**, Aoyun Ma, Dewei Li

- A novel data selection method is specifically designed for data-driven model predictive control of uncertain systems. A controller performance evaluation approach is introduced to enable the controller to select a set of informative data elements that enhance its performance. Additionally, a sliding window mechanism is implemented to compare current data against historical data, preventing the loss of significant patterns or trends. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Input-mapping based data-driven distributed model predictive control for unknown linear systems with unknown state coupling (work in progress)
<!--(https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)-->

**Yixuan Ni**, Aoyun Ma, Dewei Li

- An input-mapping based data-driven distributed MPC approach is designed for unknown linear systems, where each subsystem is coupled with the states of other subsystems, and the coupling matrices are unknown but bounded. By using a linear combination of the historical data of the subsystem and its neighbor at past moments, the future input and state can be predicted. The input-mapping data-driven scheme is combined with distributed MPC approach to stabilize the linear system with unknown state coupling.
</div>
</div>

# 💻 Projects
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.


# 🎖 Honors and Awards
- *2024.07* Outstanding Poster Paper Award.(Top3%) 
- *2023.12* Engineering Award. 
- *2023.11* Outstanding Student Award.(Top3%)
- *2023.09* First Prize Academic Scholarship.
- *2020.12* Chinese National College Computer Competition.(Third Prize) 

# 📖 Educations
- *2022.09 - 2025.03 (now)*, Master, Control Engineering, Shanghai Jiao Tong University, Shanghai.
- *2018.09 - 2022.06*, Undergraduate, Automation, Beijing Institute of Technology, Beijing. 

# 💬 Experiences
- *2024.02 - 2024.06*, **teaching assistant** for the course 'Model Predictive Control', Shanghai Jiao Tong University, Shanghai.

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

I graduated from the Department of Automation, Beijing Institute of Technology with a bachelor’s degree. I am now pursuing a master’s degree in the Department of Electrical engineering and technology at Shanghai Jiao Tong University, advised by [Dewei Li](https://automation.sjtu.edu.cn/De-Wei).

I am now researching data-driven model predictive control for uncertain systems and working on developing various industrial control software.

I won the Outstanding Student Award(Top 3%) and First Prize Academic Scholarship in 2023 at SJTU and received the Outstanding Poster Paper Award from the Chinese Process Paper Congress in 2024(Top 3%).

My research interest includes data-driven techniques, robust control, model predictive control, distributed optimization, machine learning, and decision-making.

📧Please feel free to contact me for any inquiries or further information: [niyixuan@sjtu.edu.com](mailto:niyixuan@sjtu.edu.com).


# 🔥 News
- *2024.09*: &nbsp; I have a paper accepted by CAC!🎉 
- *2024.08*: &nbsp; I receive the "Outstanding Poster Paper Award" from CPCC!😆
- *2022.06*: &nbsp; I graduate from BIT and will begin study at SJTU!🎓

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAC 2024</div><img src='images/publication1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

The improvement of data selection method in data-driven model predictive control of uncertain systems

**Yixuan Ni**, Aoyun Ma, Dewei Li

- For unknown constrained systems with bounded disturbances, an input-mapping-based data-driven MPC with a data selection method is proposed. Based on multi-step data-driven MPC, a fully data-driven controller performance metric is designed. By incorporating a sliding window mechanism, the method selects data that effectively represents the system's characteristics, thereby improving system control performance. The recursive feasibility and asymptotic stability are proven and a simulation result demonstrates the superior control performance of the proposed algorithm compared to existing approaches. Moreover, the algorithm uses online historical input and state data to design control input sequences and predict future states, without the need for system parameter identification.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/publication2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
Implementation Algorithms And Software Design Of Data-driven Model Predictive Control (master's thesis)
<!--(https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)-->

**Yixuan Ni**, under the supervision of Dewei Li

- An input-mapping based data-driven distributed MPC approach is designed for unknown linear systems, where each subsystem is coupled with the states of other subsystems, and the coupling matrices are unknown but bounded. By using a linear combination of the historical data of the subsystem and its neighbor at past moments, the future input and state can be predicted. The input-mapping data-driven scheme is combined with distributed MPC approach to stabilize the linear system with unknown state coupling.
</div>
</div>

# 💻 Projects
- *2024.04 - 2024.08*, Distributed Process Control Software Development
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/project1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Tools: Qt, C++, Python
- Developed a configuration interface, allowing the setup of model parameters, system constraints, and coupling relationships for large-scale systems.
- Implemented drag-and-drop functionality to configure subsystems, enhancing the software's usability for managing interconnected processes.
</div>
</div>


# 🎖 Honors and Awards
- *2024.07* Outstanding Poster Paper Award.(Top 3%) 
- *2023.12* Engineering Award. 
- *2023.11* Outstanding Student Award.(Top 3%)
- *2023.09* First Prize Academic Scholarship.
- *2020.12* Chinese National College Computer Competition.(Third Prize) 

# 📖 Educations
- *2022.09 - 2025.03 (now)*, Master, Control Engineering, Shanghai Jiao Tong University, Shanghai.
- *2018.09 - 2022.06*, Undergraduate, Automation, Beijing Institute of Technology, Beijing. 

# 💬 Experiences
- *2024.02 - 2024.06*, **teaching assistant** for the course 'Model Predictive Control', Shanghai Jiao Tong University, Shanghai.

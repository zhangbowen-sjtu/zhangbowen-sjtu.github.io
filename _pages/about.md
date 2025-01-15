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

I am a fourth-year PhD student at Shanghai Jiao Tong University, advised by Prof. Hong Mei and Prof. Linpeng Huang. I received my bachelor’s degree with Zhiyuan honors from Shanghai Jiao Tong University in 2021.

My research interests focus on designing storage systems (e.g., database systems, key-value stores, and file systems) for modern hardware (e.g., RDMA, CXL, SmartNIC, Persistent Memory) and architecture (e.g., resource disaggregation).

# 🔥 News

- *2024.03*: &nbsp;🎉 One paper is accepted by TPDS.
- *2023.12*: &nbsp;🎉 One paper is accepted by ICDE 24.
- *2022.01*: &nbsp;🎉 One paper is accepted by VLDB 22.

# 📝 Publications

* **[ICDE]** Exploiting Persistent CPU Cache for Scalable Persistent Hash Index. **Bowen Zhang**, Shengan Zheng, Liangxu Nie, Zhenlin Qi, Linpeng Huang, Hong Mei.  The 40th IEEE International Conference on Data Engineering (ICDE'24), 2024
* **[TPDS]** Revisiting PM-based B+-Tree with Persistent CPU Cache. **Bowen Zhang**, Shengan Zheng, Liangxu Nie, Zhenlin Qi, Hongyi Chen, Linpeng Huang, Hong Mei. IEEE Transactions on Parallel and Distributed Systems (TPDS), 2024
* **[VLDB]** NBTree: a Lock-free PM-friendly Persistent B+-Tree for eADR-enabled PM Systems. **Bowen Zhang**, Shengan Zheng, Zhenlin Qi, Linpeng Huang. The 48th International Conference on Very Large Data Bases (VLDB'22), 2022
* **[ICPP]** Conflux: Exploiting Persistent Memory and RDMA Bandwidth via Adaptive I/O Mode Selection. Zhenlin Qi, Shengan Zheng, Yifeng Hui, **Bowen Zhang**, Linpeng Huang. The 52nd International Conference on Parallel Processing (ICPP'23), 2023
* **[ICCD]** Heart: A Scalable, High-performance ART for Persistent Memory. Liangxu Nie, Shengan Zheng, **Bowen Zhang**, Jinyan Xu, Linpeng Huang. The 41st IEEE International Conference on Computer Design (ICCD'23), 2023

# 🎖 Honors and Awards

- *2024* National Scholarship for PhD Graduate Student
- *2021* Zhiyuan Honorary Bachelor’s Degree
- *2021* Outstanding Graduate of Shanghai Jiao Tong University
- *2020, 2019, 2018, 2017* Zhiyuan Honor Scholarship
- *2020, 2019, 2018* Outstanding Scholarship of Shanghai Jiao Tong University
- *2020* Weichai Scholarship

# 📖 Educations

- *2021.09 - now*, Shanghai Jiao Tong University, Department of Computer Science and Engineering. (Advised by Hong Mei)
- *2017.09 - 2021.06*, Shanghai Jiao Tong University, Department of Computer Science and Engineering. (Zhiyuan Honors)

# 👨‍🏫 Teaching

- [2022, 2023, 2024] [Spring] Computer Architecture **Teaching Assistant**

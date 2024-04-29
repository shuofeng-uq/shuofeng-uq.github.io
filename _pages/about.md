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

# About Me

<span class='anchor' id='about-me' style='text-align: justify;'></span>
I am currently a Ph.D. student at the School of Electrical Engineering and Computer Science, the University of Queensland, supervised by A/Prof. <a href="https://baigd.github.io/">Guangdong Bai</a> and Dr. <a href="https://people.csiro.au/x/j/jason-xue">Jason Xue</a>. My research focuses on tackling real-world security & privacy issues, especially on building trustworthy AI and designing privacy-preserving systems. 

# Research Interests

<ul>
  <li>Trustworthy AI</li>
  <li>Safety of Multimodal Models and Large Language Models</li>
  <li>NSFW Content Generation and Mitigation</li>
  <li>Privacy-Preserving on Purpose Limitation Principle</li>
</ul>

# News
- [Feb. 2024] Our paper on algorithmic purpose limitation is accepted by USENIX Security’24!
- [Aug. 2023] Our paper on formalizing neural network perturbation is accepted by ICFEM’23!
- [Apr. 2023] I become a Ph.D. student at UQ supervised by A/Prof. Guangdong Bai and Dr. Jason Xue!
- [Dec. 2022] I am successful in applying for CSIRO's Data61 full scholarship with top-up!
- [Jan. 2021] Our paper on the LSTM-based hybrid water level prediction method is accepted by JASSE!
  
# Publications 

<span style="color:#000080;">**Being Transparent is Merely the Beginning: Enforcing Purpose Limitation with Polynomial Approximation**</span>  
**Shuofeng Liu**, Zihan Wang, Minhui Xue, Long Wang, Yuanchao Zhang, Guangdong Bai. *USENIX Security 2024*  

<span style="color:#000080;">**Formalizing Robustness Against Character-Level Perturbations for Neural Network Language Models**</span>  
Zhongkui Ma, Xinguo Feng, Zihan Wang, **Shuofeng Liu**, Mengyao Ma, Hao Guan, Mark Huasong Meng. *ICFEM 2023*

<span style="color:#000080;">**LSTM Based Hybrid Method for Basin Water Level Prediction by Using Precipitation Data**</span>  
**Shuofeng Liu**, Puwen Lei, Koji Koyamada. *JASSE 2021*


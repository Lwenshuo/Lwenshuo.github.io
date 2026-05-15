---
layout: default
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about'></span>

你好，我是李文朔。2024 年毕业于哈尔滨工业大学（深圳）机械工程专业，获博士学位，目前在香港大学（HKU）从事博士后研究。

当前研究主要围绕面向工业场景的机器人算法与控制，包括：
- 高自由度机械臂的运动学与动力学建模
- 力位融合控制与接触感知操作
- 面向运动与力精度的标定和补偿方法
- 从仿真到实机部署的系统级验证

<a href='https://scholar.google.com/citations?user=lQhUQnUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。

我长期关注先进机器人与控制系统设计，具体兴趣包括：
- 冗余与超冗余机械臂的运动学、动力学与控制
- 双臂协同操作与复杂交互任务
- 机器人系统设计及特殊环境应用
- 机器人中的数据驱动建模与智能方法

<span class='anchor' id='education'></span>
{% include_relative includes/intro-zh.md %}

{% include_relative includes/news-zh.md %}

<span class='anchor' id='publications'></span>
{% include_relative includes/pub-zh.md %}

<span class='anchor' id='awards'></span>
{% include_relative includes/honor-zh.md %}

{% include_relative includes/others-zh.md %}

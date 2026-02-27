---
layout: default
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

<span class='anchor' id='about'></span>

Hi, I'm Wenshuo Li. I received my Ph.D. in Mechanical Engineering from Harbin Institute of Technology (Shenzhen) in 2024, and I am currently a Postdoctoral Fellow at The University of Hong Kong (HKU).

My current work focuses on robotic algorithm and control development for industrial scenarios, including:
- Kinematic and dynamic modeling of high-DOF manipulators
- Integrated force-position control and contact-aware manipulation
- Calibration and compensation methods for motion and force accuracy
- System-level validation from simulation to real hardware deployment

 <a href='https://scholar.google.com/citations?user=lQhUQnUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。

Advanced Robotics and Control Systems Design, including:
- Kinematics and dynamics, especially in redundant manipulators
- Dual-arm manipulation
- Control systems
- AI-driven in Robotics
- Robotic design, particularly for specialized environments
- Soft manipulators

<span class='anchor' id='education'></span>
{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

<span class='anchor' id='publications'></span>
{% include_relative includes/pub.md %}

<span class='anchor' id='awards'></span>
{% include_relative includes/honor.md %}

{% include_relative includes/others.md %}


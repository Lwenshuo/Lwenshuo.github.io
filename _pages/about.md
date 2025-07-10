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

Hi, I'm Wenshuo Li. I recently earned my Ph.D. in Mechanical Engineering from Harbin Institute of Technology. Currently, I’m working at BYD as a Senior Algorithm Engineer.

 <a href='https://scholar.google.com/citations?user=lQhUQnUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。

Advanced Robotics and Control Systems Design, including:
- Kinematics and dynamics, especially in redundant manipulators
- Dual-arm manipulation
- Control systems
- AI-driven in Robotics
- Robotic design, particularly for specialized environments
- Soft manipulators

{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

{% include_relative includes/pub.md %}

{% include_relative includes/honor.md %}

{% include_relative includes/others.md %}

<span class='anchor' id='-xl'></span>

<span class='anchor' id='-lwzl'></span>

<span class='anchor' id='-gzsx'></span>



---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: # redirect_from 是 Jekyll 中用于设置页面重定向的配置参数。在您的 about.md 文件中，它用于将旧的网址（如 /about/ 和 /about.html）自动重定向到新的页面（即当前页面）。
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

Hi, I'm Wenshuo Li, a PH.D student at Harbin Institute of Technology. <a href='https://scholar.google.com/citations?user=lQhUQnUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>

{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

{% include_relative includes/pub.md %}

{% include_relative includes/honor.md %}

{% include_relative includes/others.md %}

<span class='anchor' id='-xl'></span>

<span class='anchor' id='-lwzl'></span>

<span class='anchor' id='-gzsx'></span>



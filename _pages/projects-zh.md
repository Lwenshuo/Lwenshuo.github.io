---
layout: default
title: "项目"
permalink: /zh/projects/
author_profile: true
---

<div class="lang-switch" style="display:flex;justify-content:flex-start;margin:0 0 1rem 0;font-size:0.95rem;">
  <a href="{{ '/projects/' | relative_url }}" id="lang-en">EN</a>
  <span style="margin:0 0.5rem;">|</span>
  <a href="{{ '/zh/projects/' | relative_url }}" id="lang-zh" style="font-weight:700;text-decoration:underline;">中文</a>
</div>

<script>
  (function () {
    var enPath = "{{ '/projects/' | relative_url }}";
    var zhPath = "{{ '/zh/projects/' | relative_url }}";
    var currentPath = window.location.pathname;
    var preferred = localStorage.getItem("preferredLang");

    function normalize(path) {
      return path.endsWith("/") ? path : path + "/";
    }

    if (preferred === "en" && normalize(currentPath) === normalize(zhPath)) {
      window.location.replace(enPath);
      return;
    }

    var enLink = document.getElementById("lang-en");
    var zhLink = document.getElementById("lang-zh");
    if (enLink) enLink.addEventListener("click", function () { localStorage.setItem("preferredLang", "en"); });
    if (zhLink) zhLink.addEventListener("click", function () { localStorage.setItem("preferredLang", "zh"); });
  })();
</script>

## 项目列表

这里展示若干代表性的科研与工程项目。每个项目都链接到独立页面，包含简要介绍与项目图片。

<div style="border:1px solid #d9dee7;border-radius:18px;overflow:hidden;background:#fbfcfe;box-shadow:0 10px 30px rgba(15, 23, 42, 0.06);margin:1.25rem 0 1.75rem 0;">
  <a href="{{ '/zh/projects/hypa-dt/' | relative_url }}" style="display:block;">
    <img src="/images/screen_DT.png" alt="香港大学 hybrid Pose Adjustment hypa 项目的数字孪生系统" style="display:block;width:100%;height:auto;">
  </a>
  <div style="padding:1.2rem 1.2rem 1.35rem 1.2rem;">
    <div style="font-size:0.9rem;color:#5b6575;margin-bottom:0.45rem;">香港大学 · 博士后研究员 · 2025.09 - 至今</div>
    <h3 style="margin:0 0 0.6rem 0;">Hybrid Pose Adjustment（<code>hypa</code>）数字孪生</h3>
    <p style="margin:0 0 0.9rem 0;">面向 hybrid Pose Adjustment 系统构建数字孪生框架，用于连接物理设备与仿真模型，支持状态同步观测与验证。</p>
    <a href="{{ '/zh/projects/hypa-dt/' | relative_url }}" style="display:inline-block;padding:0.45rem 0.8rem;border:1px solid #1f4b99;border-radius:999px;text-decoration:none;font-weight:600;">查看项目详情</a>
  </div>
</div>

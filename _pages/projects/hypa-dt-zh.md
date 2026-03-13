---
layout: default
title: "Hybrid Pose Adjustment (hypa) 数字孪生"
permalink: /zh/projects/hypa-dt/
author_profile: true
---

<div class="lang-switch" style="display:flex;justify-content:flex-start;margin:0 0 1rem 0;font-size:0.95rem;">
  <a href="{{ '/projects/hypa-dt/' | relative_url }}" id="lang-en">EN</a>
  <span style="margin:0 0.5rem;">|</span>
  <a href="{{ '/zh/projects/hypa-dt/' | relative_url }}" id="lang-zh" style="font-weight:700;text-decoration:underline;">中文</a>
</div>

<script>
  (function () {
    var enPath = "{{ '/projects/hypa-dt/' | relative_url }}";
    var zhPath = "{{ '/zh/projects/hypa-dt/' | relative_url }}";
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

<p><a href="{{ '/zh/projects/' | relative_url }}">← 返回 Projects</a></p>

## Hybrid Pose Adjustment（`hypa`）数字孪生

**机构**：香港大学（HKU）  
**角色**：博士后研究员  
**时间**：2025.09 - 至今

该项目聚焦于为 hybrid Pose Adjustment（`hypa`）系统构建数字孪生，用于连接物理实验与虚拟模型，提升系统状态观测、控制策略验证与迭代开发效率。

<img src="/images/screen_DT.png" alt="香港大学 hybrid Pose Adjustment hypa 项目的数字孪生系统" width="100%">

### 项目概述

- 构建 `hypa` 系统的数字化映射，实现关键状态与行为的同步监测。
- 支持位姿调整与控制流程的仿真验证。
- 加强实物测试与虚拟分析之间的联系，加快开发迭代。

### 关键词

- 数字孪生
- 位姿调整
- 机器人系统建模
- 仿真验证

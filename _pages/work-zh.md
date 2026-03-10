---
layout: default
title: "工作与实习"
permalink: /zh/work/
author_profile: true
---

<div class="lang-switch" style="display:flex;justify-content:flex-start;margin:0 0 1rem 0;font-size:0.95rem;">
  <a href="{{ '/work/' | relative_url }}" id="lang-en">EN</a>
  <span style="margin:0 0.5rem;">|</span>
  <a href="{{ '/zh/work/' | relative_url }}" id="lang-zh" style="font-weight:700;text-decoration:underline;">中文</a>
</div>

<script>
  (function () {
    var enPath = "{{ '/work/' | relative_url }}";
    var zhPath = "{{ '/zh/work/' | relative_url }}";
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

## 工作经历

### 香港大学（HKU）博士后研究员（2025.09 - 至今）
- 开展机器人与控制方向的博士后研究工作。
- 聚焦高性能机器人操作系统的建模、规划与控制。
- 推进复杂交互任务中的鲁棒运动/力控制策略。

### 比亚迪高级算法工程师（2025.02 - 2025.07）
- 面向工业操作任务开发并部署机器人算法。
- 构建高自由度机械臂的运动学/动力学模型与接触感知控制流程。
- 通过标定与补偿方法提升运动与力控制精度。
- 支持算法从仿真验证到实机联调落地。

## 实习经历

### 美的（2019.07 - 2019.08）
- 参与运动控制与原型测试相关工程任务。
- 协助算法/系统模块的实现与验证。

### 专利
---
## 中国专利
- 徐文福, 黄曦, `李文朔`, 袁晗, 梁斌. 绳驱柔性机械臂的闭环运动控制方法及系统 (授权号: CN113386124B). [[链接]](https://patents.google.com/patent/CN113386124B/zh)
- 徐文福, `李文朔`, 林博洋, 闫磊, 梁斌. 一种绳驱柔性机械臂的整臂力感知方法、装置和存储介质 (授权号: CN115890673A). [[链接]](https://patents.google.com/patent/CN115890673A/zh)
- 徐文福, 林博洋, `李文朔`, 闫磊, 梁斌. 一种多重空间力位融合的绳驱柔性机械臂闭环控制方法 (授权号: CN116100540A). [[链接]](https://patents.google.com/patent/CN116100540A/zh)
- 徐文福, 林博洋, `李文朔`, 闫磊, 梁斌. 一种绳驱柔性机械臂操作空间柔顺控制方法及装置 (授权号: CN115723139A). [[链接]](https://patents.google.com/patent/CN115723139A/zh)
- 徐文福, 李君祥, `李文朔`, 梁斌. 联动调节结构及绳驱分段联动柔性机械臂 (公开号: CN116834064A). [[链接]](https://patents.google.com/patent/CN116834064A/zh)
- 徐文福, 黄一帆, `李文朔`, 袁晗, 梁斌. 一种高刚度低回隙的闭环绳驱柔性臂驱动电控一体装置 (公开号: CN114670182A). [[链接]](https://patents.google.com/patent/CN114670182A/zh)
- 陈辰, 贺亚衣, 薛景涛, 徐文福, 程洪洋, `李文朔`, 袁晗. 柔性机械臂及其控制方法、计算机装置 (公开号: CN117917308A). [[链接]](https://patents.google.com/patent/CN117917308A/zh)

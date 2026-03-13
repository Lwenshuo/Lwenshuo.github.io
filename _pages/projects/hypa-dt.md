---
layout: default
title: "Digital Twin for Hybrid Pose Adjustment (hypa)"
permalink: /projects/hypa-dt/
author_profile: true
---

<div class="lang-switch" style="display:flex;justify-content:flex-start;margin:0 0 1rem 0;font-size:0.95rem;">
  <a href="{{ '/projects/hypa-dt/' | relative_url }}" id="lang-en" style="font-weight:700;text-decoration:underline;">EN</a>
  <span style="margin:0 0.5rem;">|</span>
  <a href="{{ '/zh/projects/hypa-dt/' | relative_url }}" id="lang-zh">中文</a>
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

    if (preferred === "zh" && normalize(currentPath) === normalize(enPath)) {
      window.location.replace(zhPath);
      return;
    }

    var enLink = document.getElementById("lang-en");
    var zhLink = document.getElementById("lang-zh");
    if (enLink) enLink.addEventListener("click", function () { localStorage.setItem("preferredLang", "en"); });
    if (zhLink) zhLink.addEventListener("click", function () { localStorage.setItem("preferredLang", "zh"); });
  })();
</script>

<p><a href="{{ '/projects/' | relative_url }}">← Back to Projects</a></p>

## Digital Twin for Hybrid Pose Adjustment (`hypa`)

**Institution**: The University of Hong Kong (HKU)  
**Role**: Postdoctoral Fellow  
**Period**: 2025.09 - Present

This project focuses on building a digital twin for the hybrid Pose Adjustment (`hypa`) system. The twin is used to connect physical experiments with virtual models, making it easier to observe system states, validate control strategies, and support iterative development.

<img src="/images/screen_DT.png" alt="Digital twin system for the hybrid Pose Adjustment hypa project at HKU" width="100%">

### Overview

- Built a digital representation of the `hypa` system for synchronized monitoring of key states and behaviors.
- Supported simulation-based validation for pose adjustment and control workflows.
- Improved the connection between physical testing and virtual analysis for faster development cycles.

### Keywords

- Digital twin
- Pose adjustment
- Robotics system modeling
- Simulation validation

---
layout: default
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects/
  - /projects.html
---

<div class="lang-switch" style="display:flex;justify-content:flex-start;margin:0 0 1rem 0;font-size:0.95rem;">
  <a href="{{ '/projects/' | relative_url }}" id="lang-en" style="font-weight:700;text-decoration:underline;">EN</a>
  <span style="margin:0 0.5rem;">|</span>
  <a href="{{ '/zh/projects/' | relative_url }}" id="lang-zh">中文</a>
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

## Selected Projects

This page lists selected research and engineering projects. Each entry links to a dedicated page with a concise summary and project visual.

<div style="border:1px solid #d9dee7;border-radius:18px;overflow:hidden;background:#fbfcfe;box-shadow:0 10px 30px rgba(15, 23, 42, 0.06);margin:1.25rem 0 1.75rem 0;">
  <a href="{{ '/projects/hypa-dt/' | relative_url }}" style="display:block;">
    <img src="/images/screen_DT.png" alt="Digital twin system for the hybrid Pose Adjustment hypa project at HKU" style="display:block;width:100%;height:auto;">
  </a>
  <div style="padding:1.2rem 1.2rem 1.35rem 1.2rem;">
    <div style="font-size:0.9rem;color:#5b6575;margin-bottom:0.45rem;">HKU · Postdoctoral Fellow · 2025.09 - Present</div>
    <h3 style="margin:0 0 0.6rem 0;">Digital Twin for Hybrid Pose Adjustment (<code>hypa</code>)</h3>
    <p style="margin:0 0 0.9rem 0;">A digital twin framework for the hybrid Pose Adjustment system, connecting physical equipment and simulation models for synchronized observation and validation.</p>
    <a href="{{ '/projects/hypa-dt/' | relative_url }}" style="display:inline-block;padding:0.45rem 0.8rem;border:1px solid #1f4b99;border-radius:999px;text-decoration:none;font-weight:600;">View project details</a>
  </div>
</div>

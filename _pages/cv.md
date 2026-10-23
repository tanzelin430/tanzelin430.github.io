---
layout: archive
title: "CV / 简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% assign cv_pdf = "/files/Zelin_Tan_CV.pdf" | relative_url %}
{% assign cv_zh_pdf = "/files/Zelin_Tan_CV_zh.pdf" | relative_url %}

<p class="cv-intro">View or download my CV in English or Chinese.</p>

## English CV

<div class="cv-actions" aria-label="English CV">
  <a class="btn btn--primary" href="{{ cv_pdf }}" target="_blank" rel="noopener noreferrer">View PDF</a>
  <a class="btn" href="{{ cv_pdf }}" download>Download PDF</a>
</div>

<h2 lang="zh-CN">中文简历</h2>

<div class="cv-actions" lang="zh-CN" aria-label="中文简历">
  <a class="btn btn--primary" href="{{ cv_zh_pdf }}" target="_blank" rel="noopener noreferrer">在线查看</a>
  <a class="btn" href="{{ cv_zh_pdf }}" download>下载 PDF</a>
</div>

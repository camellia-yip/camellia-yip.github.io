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

# About

<!-- Biography written by GPT (Codex), approved by the site owner, 2026-11-14. -->
I am interested in **representation learning and world action models (WAMs)**: how agents learn internal representations of the world, predict the consequences of their actions, and use those predictions to plan. My current work explores JEPA-based models, with a focus on learning through interaction and understanding what makes learned representations useful for action.

My path into machine learning grew out of research in neuroscience, where I used brain imaging to study brain organization, cognition, and behavior. That experience sparked my curiosity about how intelligent systems organize experience into internal representations. It also shaped how I approach research: using measurements, probes, and interventions to investigate mechanisms that we cannot directly observe.

What excites me most is the opportunity to **build intelligent capabilities and study how they emerge**. I want to understand what information a model retains, how its representations change through learning, and how those representations support behavior. Neuroscience continues to inform the questions I ask as I explore these problems in artificial systems.

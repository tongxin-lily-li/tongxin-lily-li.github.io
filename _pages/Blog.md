---
title: Blog
permalink: /blog/
layout: page
excerpt: ""
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json " %}
{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

<span class='anchor' id='blog'></span>

Excited to share that I’m going to Japan for #CHI2025 @acm_chi this month! It’ll be my first CHI, and I’m looking forward to connecting with HCI professionals. Although I don’t have a publication this year, eager to learn and be inspired by the amazing work in the community!

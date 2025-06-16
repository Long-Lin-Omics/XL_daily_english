---
layout: default
title: 英语学习日记
permalink: /XL_daily_english/
---

# 我的英语学习日记

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
  </li>
  {% endfor %}
</ul>

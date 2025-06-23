---
layout: default
title: Blog
---

<link rel="stylesheet" href="/assets/style.css">

# 📝 Blog

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endfor %}
</ul>

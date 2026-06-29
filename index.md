---
layout: home
title: Home
permalink: /
---

# Heeyeon Kim's Blog

Welcome! This is where I post notes on research, reading, and projects.

Use the sidebar to browse, and the **sun/moon button at the top right** to switch
between light and dark mode.

## Recent posts

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url | relative_url }}) — <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  {% endfor %}

---
layout: home
title: Home
permalink: /
---

# Heeyeon Kim's Blog

Welcome! Browse posts by category in the sidebar. Use the **"A" button at the
top right** to switch between light, sepia, and dark (Night) mode.

## Research

{% for post in site.research %}

- [{{ post.title }}]({{ post.url | relative_url }}) — <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  {% endfor %}

## Notes

{% for post in site.notes %}

- [{{ post.title }}]({{ post.url | relative_url }}) — <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  {% endfor %}

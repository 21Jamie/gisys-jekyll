---
layout: default
title: Home
---

# GISYS

Obsidian Notes Published with Jekyll + Netlify

## Recent Posts

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} → [{{ post.title }}]({{ post.url }})
{% endfor %}

---

## About

This site contains research reviews and notes published from Obsidian.

## Categories

- [Reviews](/categories/reviews)

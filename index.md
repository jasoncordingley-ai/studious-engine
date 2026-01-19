---
layout: default
title: Home
---

# Welcome to Studious Engine

This is a scaffolded Jekyll site created on 2026-01-19. Browse the posts to see short write-ups inspired by today's news.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

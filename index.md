---
layout: default
title: Home
---

# Welcome

This is my daily blog where I share technical ideas, DevOps tips, and things I’m learning. Stay curious and keep building!

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}

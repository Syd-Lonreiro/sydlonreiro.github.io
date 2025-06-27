---
layout: default
title: Home
---

# Syd Lonreiro

*Thoughts on cryonics, life extension, and the distant future.*

---

Welcome to my personal archive of notes and reflections.

## Latest posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

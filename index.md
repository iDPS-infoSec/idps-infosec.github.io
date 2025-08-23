---
layout: home
title: Home
---

# {{ site.title }}

<p>{{ site.description }}</p>

---

## Welcome

Welcome to my InfoSec blog! Here I document my **red team learnings, penetration testing experiments, and security insights**.  
Feel free to browse the posts, learn with me, and explore the content.

---

## Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

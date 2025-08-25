---
layout: home
title: Home
---

Exploring offensive security, penetration testing, and red teaming.  
This blog documents notes, lessons, and experiments from my red team activities.

---

## Welcome

Here I share my journey in InfoSec — from **penetration testing techniques** and **red team exercises** to insights learned in real-world scenarios.  
I focus on getting as much practical, hands-on learning as I can.

---

## Latest Posts

{% if site.posts.size > 0 %}
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
{% else %}
_No posts yet._
{% endif %}

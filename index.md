---
layout: home
title: Home
---

# iDPS InfoSec

Exploring offensive security, penetration testing, and red teaming.  

---

## Welcome

This is where I share my journey in InfoSec — from penetration testing techniques and red team experiments to lessons learned in the field.  

---

## Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

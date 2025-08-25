---
layout: home
title: Home
---

<<<<<<< HEAD
# iDPS InfoSec

Exploring offensive security, penetration testing, and red teaming.  
=======
{{ site.description }}
>>>>>>> 99c5732 (Updated intro post, study plan, and homepage content)

---

## Welcome

This is where I share my journey in InfoSec — from penetration testing techniques and red team experiments to lessons learned in the field.  
<<<<<<< HEAD
=======
Whether you’re just getting started or already experienced, I hope you’ll find practical insights and thought-provoking content here.
>>>>>>> 99c5732 (Updated intro post, study plan, and homepage content)

---

## Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}

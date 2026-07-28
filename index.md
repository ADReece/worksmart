---
layout: default
title: worksMart - Home Office Setup Guides
---

# worksMart

Practical guides for building a productive home office. We focus on ergonomic equipment that actually matters: standing desks, chairs, monitor arms, and organization solutions that help you work better and healthier.

**Current guides:**

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

**Note:** Product recommendations are updated as new options become available. Some links may be affiliate links — at no extra cost to you, we earn a commission if you purchase through them.

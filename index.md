---
layout: default
title: List of all blogs
---

{% for post in site.posts %}
  * {{ post.date | date: '%Y %b %d'}} >> [{{ post.title }}]({{ post.url }})
{% endfor %}
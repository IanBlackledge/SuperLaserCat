---
layout: default
title: Index
---

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}

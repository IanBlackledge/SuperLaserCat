---
layout: grid
title: News
---

{% assign news_posts = site.posts | where: "category", "news" %}
{% for post in news_posts %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}

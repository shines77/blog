---
layout: index 
title: shines77's blog
---

{% for post in site.posts %}
  - ### [{{ post.title }}](/blog{{ post.url }}) <time>{{ post.date | date: '%Y-%m-%d' }}</time>

  {{ post.summary }}

  [全文阅读 &raquo;](/blog{{ post.url }})
{% endfor %}

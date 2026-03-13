---
layout: page
title: Blog
permalink: /blog/
---

# Stonework Investments Blog

Welcome to our blog! Here you'll find articles about bookkeeping, financial management, and investment strategies.

## Latest Posts

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
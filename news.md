---
layout: default
title: News
permalink: /news/
---

# 📰 News

{% for post in site.news reversed %}
- [{{ post.title }}]({{ post.url }}) – {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}

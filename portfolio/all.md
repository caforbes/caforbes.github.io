---
layout: default
title: All projects
---

## All projects

{% for post in site.categories["portfolio"] %}

* [{{ post.title }}]({{ post.url }}) -- {{ post.excerpt | strip_html }}

{% endfor %}

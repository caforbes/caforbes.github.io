---
layout: default
title: All projects
hidden: true
---

## All projects

{% assign public_posts = site.categories["portfolio"] | hidden: true %}
{% for post in public_posts %}

* [{{ post.title }}]({{ post.url }}) -- {{ post.excerpt | strip_html }}

{% endfor %}

[View projects by topic](/portfolio/tags)

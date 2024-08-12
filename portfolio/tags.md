---
layout: default
title: Projects by topic
---

## Projects by topic

{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}

### {{ tag[0] }}

{% for post in tag[1] %}
{% if post.categories contains "portfolio" %}
  * [{{ post.title }}]({{ post.url }}) -- {{ post.excerpt | strip_html }}
{% endif %}
{% endfor %}

{% endfor %}

[View all projects](/portfolio/all)
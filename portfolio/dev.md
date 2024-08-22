---
layout: default
title: Software engineering | Portfolio
---
## Software engineering projects

{% assign this_tag = site.tags["dev"] %}

{% for post in this_tag %}
{% if post.categories contains "portfolio" %}

* [{{ post.title }}]({{ post.url }}) -- {{ post.excerpt | strip_html }}

{% endif %}
{% endfor %}

---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Scottley's blog
---

Welcome to my nonsense!

{% for post in site.posts %}
- {{ post.date | date_to_string }} >> [{{ post.title  }}]({{ post.url }})
{% endfor %}

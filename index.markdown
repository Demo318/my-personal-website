---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: base
title: home
comments: false
---

## Blog Posts



<ul>

{%- assign date_format = site.date_format | default: "%b %-d, %Y" -%}
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> on {{ post.date | date: date_format }}</li>
{% endfor %}

</ul>
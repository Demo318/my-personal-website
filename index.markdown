---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: base
title: home
comments: false
---
# The Personal Homepage of Devin Mork

## Blog Posts



<ul class="blog-posts-list">

{%- assign date_format = site.date_format | default: "%b %-d, %Y" -%}
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-list-publish-date">{{ post.date | date: date_format }}</span>
  </li>
{% endfor %}

</ul>
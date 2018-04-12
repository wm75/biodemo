---
title: Welcome
layout: default
---

This is the biodemo site.

## List of posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{site.base-url}}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

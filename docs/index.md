---
title: Welcome
layout: default
---

This is the biodemo site.

## Problem of the month

Try to solve [our current Problem of the Month]({{ "problem_of_the_month.md" | relative_url }})

or browse the previous problems.

## List of posts

for debugging {{site.url}} {{site.base_url}}


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

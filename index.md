---
layout: none
title: Computing Blog
---

## Gaminax Computing Blog

[2019-10-11-initial-post](https://gaminax.github.io/computingBlog/2019-10-11-initial-post.html)

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

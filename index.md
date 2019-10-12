---
layout: default
title: Computing Blog
---

## Gaminax Computing Blog

[2019-10-11-initial-post](https://gaminax.github.io/computingBlog/2019-10-11-initial-post.html)

site.baseurl = {{ site.baseurl }}

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---
title: Blog
date: 2019-12-01 12:53:00 Z
permalink: "/blog/"
layout: page
---

## Tulisan dan Catatan

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
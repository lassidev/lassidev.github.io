---
layout: page
title: All posts
subtitle: testing
---

<ul>
  {% for post in site.posts %}
    <li>
      {{ page.date | date: "%Y-%m-%d" }}
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

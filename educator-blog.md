---
title: Educator Blog
layout: default
---

# Educator Blog

Welcome to the **Educator Blog** — a space where teachers reflect on integrating technology and AI into their English classrooms.

All posts are moderated before publication. Click a title below to read more.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <br>
      <small><em>{{ post.date | date: "%B %d, %Y" }}</em></small>
    </li>
  {% endfor %}
</ul>


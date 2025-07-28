---
title: Educator Blog
layout: default
---

# Educator Blog

Welcome to the Educator Blog — a space where teachers reflect on integrating technology and AI into their English classrooms.

All posts are moderated before publication. Click a title below to read more.

---

{% assign posts = site.posts | where_exp: "post", "post.path contains '_posts/educators/'" %}
<ul>
  {% for post in posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br><small>Posted on {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

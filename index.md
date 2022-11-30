---
title: About plamo.social
layout: home
nav_order: 1
---
# About plamo.social

Like the name would indicate, the primary user group of this instance are those who are enthusiasts of "[plamo](https://en.wikipedia.org/wiki/Plamo)", or plastic modeling.

This encapsulates any and all hobby modeling done in plastic or resins, including fantasy, sci-fi, & military modeling; construction of pre-molded kits, kit bashing, scratch building, miniature painting, and the collection of pre-assembled, fully finished models (toys, figures, sofubi, etc).

Also included (but not limited to) are any of the adjacent topics such as gaming, anime, film, literature, history, art, 3D design & printing, etc.

Welcome to the instance, and happy posting!

---
# Blog
{% for post in site.posts %}
  <p class="blog-item"><b><a href="{{ post.url }}">{{ post.title }}</a></b><br>
  <span class="post-description">{{ post.description }}</span><br>
  <span class="post-meta">📅 {{ post.date | date_to_string }}</span></p>
{% endfor %}

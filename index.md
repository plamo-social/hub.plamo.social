---
title: About plamo.social
layout: home
nav_order: 1
---
# About plamo.social

Plamo Social is a community focused on plastic modeling, miniatures, kit bashing, sculptures, dioramas, and all topics adjacent. This server exists as a Mastodon instance as part of the [Fediverse](https://en.wikipedia.org/wiki/Fediverse) all across the internet. This means you will not only be able to interact with those on this server, but other Mastodon servers, and other platforms using the ActivityPub protocol.

Like the name would indicate, the primary user group of this instance are those who are enthusiasts of "[plamo](https://en.wikipedia.org/wiki/Plamo)", or plastic modeling.

This encapsulates any and all hobby modeling done in plastic or resins, including fantasy, sci-fi, & military modeling; construction of pre-molded kits, kit bashing, scratch building, miniature painting, and the collection of pre-assembled, fully finished models (toys, figures, sofubi, etc). The list is far from exhaustive.

Also included (but not limited to) are any of the adjacent topics such as gaming, anime, film, literature, history, art, 3D design & printing, etc.

{: .important }
> Sign ups currently require manual approval, please ensure to write something about why you think plamo.social is the right instance for you. If you just want a Mastodon account, you should probably sign up at one of the larger instances instead; check out [instances.social](https://instances.social/) or [joinmastodon](https://joinmastodon.org/) to find a better fit.
>
> Don't worry, you'll still be able to interact with any public accounts on plamo.social.

---
## Blog

{% for post in site.posts %}
  <p class="blog-item"><b><a href="{{ post.url }}">{{ post.title }}</a></b><br>
  <span class="post-description">{{ post.description }}</span><br>
  <span class="post-meta">📅 {{ post.date | date_to_string }}</span></p>
{% endfor %}

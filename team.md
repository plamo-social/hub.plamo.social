---
title: Meet the Team
description: Plamo.social moderation team.
layout: default
last_modified_date: 2022-11-28
nav_order: 3
---

# Meet The Team

{% for member in site.data.team %}
<div class="team-banner">
    <p class="team-title"><a target="blank" href="{{ member.link }}">{{ member.name }}</a></p>
    <img class="team-avatar" src="{{ member.avatar }}" />
    <p><b>Role:</b> {{ member.role }}</p>
    <p>{{ member.description }}</p>
  </div>
{% endfor %}

<div style="clear: both;"></div>
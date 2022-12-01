---
title: Meet the Team
description: Plamo.social moderation team.
layout: default
last_modified_date: 2022-11-28
nav_order: 2
---

# Meet The Team

plamo.social is administered, moderated, and maintained 100% by a group of volunteers.

{% for member in site.data.team %}
## [{{ member.name }}]({{ member.link }})

**Role:** {{ member.role }}

{{ member.description }}
{% endfor %}
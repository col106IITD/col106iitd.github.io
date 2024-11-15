---
layout: page
title: Lectures
nav_exclude: false
description: The weekly event schedule.
---

# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

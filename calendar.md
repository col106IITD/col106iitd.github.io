---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

<iframe src="https://calendar.google.com/calendar/embed?src=19c09ed703dc5d2c35c7a811b85613dfce075e189863bdc353b3ef3e455d8f69%40group.calendar.google.com&ctz=Asia%2FKolkata" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>


{% for module in site.modules %}
{{ module }}
{% endfor %}

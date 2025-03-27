---
layout: page
title: Visions
permalink: /visions/
---

{% for vision in site.visions %}
- [{{ vision.title }}]({{ vision.url }})
{% endfor %} 
---
layout: page
title: Stories
permalink: /stories/
---

{% for story in site.stories %}
- [{{ story.title }}]({{ story.url }})
{% endfor %} 
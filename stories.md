---
layout: page
title: Stories
permalink: /stories/
---

<div class="collection-grid">
{% for story in site.stories %}
    <div class="collection-item">
        {% if story.image %}
            <img src="{{ story.image }}" alt="{{ story.title }}">
        {% endif %}
        <div class="item-content">
            <h2>{{ story.title }}</h2>
            {% if story.description %}
                <p>{{ story.description }}</p>
            {% endif %}
            <a href="{{ story.url }}" class="post-link">Read Story →</a>
        </div>
    </div>
{% endfor %}
</div> 
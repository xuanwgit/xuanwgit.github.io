---
layout: page
title: Visions
permalink: /visions/
---

<div class="collection-grid">
{% for vision in site.visions %}
    <div class="collection-item">
        {% if vision.image %}
            <img src="{{ vision.image }}" alt="{{ vision.title }}">
        {% endif %}
        <div class="item-content">
            <h2>{{ vision.title }}</h2>
            {% if vision.description %}
                <p>{{ vision.description }}</p>
            {% endif %}
            <a href="{{ vision.url }}" class="post-link">View Vision →</a>
        </div>
    </div>
{% endfor %}
</div> 
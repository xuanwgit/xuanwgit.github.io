---
layout: page
title: Codes
permalink: /codes/
---

<div class="collection-grid">
{% for project in site.codes %}
    <div class="collection-item">
        {% if project.image %}
            <img src="{{ project.image }}" alt="{{ project.title }}">
        {% endif %}
        <div class="item-content">
            <h2>{{ project.title }}</h2>
            {% if project.description %}
                <p>{{ project.description }}</p>
            {% endif %}
            <a href="{{ project.url }}" class="post-link">View Project →</a>
        </div>
    </div>
{% endfor %}
</div> 
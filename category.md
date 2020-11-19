---
layout: page
title: Category
---
{% assign pages_list = site.pages | sort:"url" %}
  {% for node in pages_list %}
    {% if node.title != null %}
      {% if node.layout == "category" %}
        <p>{{node.title}}</p>
     {% endif %}
    {% endif %}
  {% endfor %}
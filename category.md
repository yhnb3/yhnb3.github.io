---
layout: page
title: Category
---
<div class="categories">
  {% for category in categories %}
  <div class="category">
    <h1 class="category-title">
        {{ category.title }}
    </h1>
  </div>
  {% endfor %}
</div>

<!-- <div class="pagination">
  {% if paginator.next_page %}
  <a class="pagination-item older" href="{{ paginator.next_page_path | absolute_url }}">Older</a>
  {% else %}
  <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
  {% if paginator.page == 2 %}
  <a class="pagination-item newer" href="{{ '/' | absolute_url }}">Newer</a>
  {% else %}
  <a class="pagination-item newer" href="{{ paginator.previous_page_path | absolute_url }}">Newer</a>
  {% endif %}
  {% else %}
  <span class="pagination-item newer">Newer</span>
  {% endif %}
</div> -->
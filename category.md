---
layout: page
title: Category
---
{% for post in paginator.categories %}
  <p>{{post.title}}<p>
{% endfor %}
<p>되긴해 근데?????</p>
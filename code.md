---
layout: default
title: Code
permalink: /code/
---

<div class="home">

  <h1 class="page-heading">Code</h1>

  <ul class="post-list">
    {% for post in site.categories.code %}
      {% include page-item.html %}
    {% endfor %}
  </ul>

</div>
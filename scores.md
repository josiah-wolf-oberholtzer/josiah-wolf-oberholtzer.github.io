---
layout: default
title: Scores
permalink: /scores/
---

<div class="home">

  <h1 class="page-heading">Scores</h1>

  <ul class="post-list">
    {% for post in site.categories.scores %}
      {% include page-item.html %}
    {% endfor %}
  </ul>

</div>
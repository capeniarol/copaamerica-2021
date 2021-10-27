---
layout: eldorado
title: Full Matches
description: Full list of available football matches in this site
name: full-matches.md
---

  {% include space-top.html %}

<section>
  <div class="section-banner container">
    <div class="row">
      {% for post in site.posts %}
        <a href="{{ post.url }}">
          {{ post.title }}<br>
        </a>
        <hr>
      {% endfor %}
    </div>
  </div>
</section>

  {% include space.html %}

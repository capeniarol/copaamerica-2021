---
layout: default
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
          {{ post.title }}
        </a>
        post id: {{ post.id }}<br>
        page id: {{ page.id }}
        <hr>
      {% endfor %}
    </div>
  </div>
</section>

  {% include space.html %}

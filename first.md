---
layout: default
title: "First Exercise"
---

<div class="toc">
  <h2>First Exercise</h2>
  <ul>

  {% for page in site.first %}
  <h2>{{ page.title }}</h2>
  <p><a href="{{ item.url }}">{{ page.title }}</a></p>
  {% endfor %}

  </ul>
</div>
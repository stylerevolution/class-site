---
layout: default
title: "First Exercise"
---

<div class="toc">
  <h2>First Exercise</h2>
  <ul>

  {% for page in site.first %}
  <h2>{{ page.author }}</h2>
  <p><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></p>
  {% endfor %}

  </ul>
</div>
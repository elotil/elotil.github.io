---
layout: default
title: Portfolio
permalink: portfolio
---

Welcome to my development portfolio! I'm still adding old projects and it will be awhile before I consider this up-to-date, but please feel free to take a look around anyway.

<ul>
{% for entry in site.categories.portfolio %}
<li>
  <a href="{{ entry.url }}">{{ entry.title }} ({{ entry.date | date: "%Y" }})</a>
  {{ entry.excerpt }}
</li>
{% endfor %}
</ul>
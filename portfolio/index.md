---
layout: default
title: Portfolio
permalink: portfolio
---

Most of my recent professional work has been on proprietary software, so it isn't represented in this portfolio. The projects below include academic work as well as newer projects I'm building independently.

<ul>
{% for entry in site.categories.portfolio %}
<li>
  <a href="{{ entry.url }}">{{ entry.title }} ({{ entry.date | date: "%Y" }})</a>
  {{ entry.excerpt }}
</li>
{% endfor %}
</ul>
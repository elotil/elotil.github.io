---
layout: default
title: Portfolio
permalink: portfolio
---

Welcome to my development portfolio! Projects and other nonsense coming soon.

<ul>
{% for entry in site.categories.portfolio %}
<li>
  <a href="{{ entry.url }}">{{ entry.title }}</a>
</li>
{% endfor %}
</ul>
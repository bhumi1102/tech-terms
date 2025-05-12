---
layout: default
title: Home
---

# Tech Terms Dictionary

Welcome! Here's a list of technical terms:

<ul>
  {% for term in site.terms %}
    <li><a href="{{ term.url }}">{{ term.title }}</a></li>
  {% endfor %}
</ul>

---
title: Morning Show
date: 2016-03-25 15:24:00 -06:00
---

{% for episode in site.morningshow %}
  <h2>{{ morningshow.title }}</h2>
  <p><em>{{ morningshow.date }}</em></p>
  
{% endfor %}
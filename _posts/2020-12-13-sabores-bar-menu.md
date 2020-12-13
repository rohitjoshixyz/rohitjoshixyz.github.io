---
layout: page
title: Sabores European Bistro | Bar
permalink: sabores/bar
logo: /assets/images/sabores/sabores-logo.png
---
{% assign array = "01,02,03,04,05,06,07" | split: ','%}
{% for item in array %}
  <img src="/assets/images/sabores/bar/{{ item }}.webp" alt="bar-menu-{{ item }}" class="food-menu"/>
{% endfor %}
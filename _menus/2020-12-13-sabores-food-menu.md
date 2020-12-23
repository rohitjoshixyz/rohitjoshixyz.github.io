---
layout: page
title: Sabores European Bistro | Food
permalink: sabores/food
logo: /assets/images/sabores/sabores-logo.png
hotel_name: sabores
---
{% assign array = "01,02,03,04,05,06,07,08,09,10,11" | split: ','%}
{% for item in array %}
  <img src="/assets/images/sabores/food/{{ item }}.webp" alt="food-menu-{{ item }}" class="food-menu"/>
{% endfor %}
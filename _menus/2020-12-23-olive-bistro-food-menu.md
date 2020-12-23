---
layout: page
title: Olive Bistro Mumbai | Food
permalink: olive-bistro/food
logo: /assets/images/olive-bistro/olive-bistro-logo.png
hotel_name: olive-bistro
---
{% assign array = "01,02,03,04,05,06" | split: ','%}
{% for item in array %}
  <img src="/assets/images/olive-bistro/food/{{ item }}-food.webp" alt="food-menu-{{ item }}" class="food-menu"/>
{% endfor %}
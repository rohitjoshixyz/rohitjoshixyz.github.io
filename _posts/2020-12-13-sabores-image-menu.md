---
layout: page
title: Sabores European Bistro
permalink: sabores
---
<style>
  .food-menu {
    width: 100%;
    text-align: center;
  }

  .post-title {
    text-align: center;
  }
</style>
{% assign array = "01,02,03,04,05,06,07,08,09,10,11" | split: ','%}
{% for item in array %}
  <img src="/assets/images/sabores/{{ item }}.webp" alt="food-menu-{{ item }}" class="food-menu"/>
{% endfor %}
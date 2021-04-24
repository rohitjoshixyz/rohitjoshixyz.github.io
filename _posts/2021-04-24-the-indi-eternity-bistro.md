---
layout: hotel_index
title: The Indi Eternity Bistro
permalink: tieb
logo: /assets/images/tieb/tieb-logo.jpg
hotel_name: the-indi-eternity-bistro
---

<ul>
<li> 
<p>To order food, please send a whatsapp of the following format:</p>
<b>Your Order Details:</b> <br>

<tt>1 Crispy Chicken Burger<br>
1 Peri peri chicken mayo sandwich<br></tt>
<br>
<b>Your Full Address: </b><br>
Shop No. 5, Rajgad Society, Rambaug colony, MIT college road, Kothrud
<br><br>
Share your details on - <a href="tel:+919834618102">9834618102</a> ( Whatsapp No. Only for orders )
<br><br>
<h4><a href="upi://pay?pa=virajgophan@okicici&amp;pn=Viraj Gophan&amp;cu=INR" class="upi-pay1">Pay using UPI</a> (UPI ID: virajgophan@okicici)
</h4>
</li>
  {% assign array = "01,02" | split: ','%}
{% for item in array %}
  <img src="/assets/images/tieb/food/{{ item }}-food.jpg" alt="food-menu-{{ item }}" class="food-menu"/>
{% endfor %}
</ul>

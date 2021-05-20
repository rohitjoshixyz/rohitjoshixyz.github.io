---
layout: hotel_index
title: The Indi Eternity Bistro
permalink: tieb
logo: /assets/images/tieb/tieb-logo.jpg
hotel_name: the-indi-eternity-bistro
---
<img src="/assets/images/tieb/tieb-logo.jpg" height="50%" width="50%">
<ul>
<h2>
<a href="https://api.whatsapp.com/send?phone=+919834618102&text=https%3A%2F%2Fapi.whatsapp.com%2Fsend%3Fphone%3D%20919834618102%26text%3DWelcome%20to%20%F0%9F%8D%94%F0%9F%8D%9F*The%20Indi%20Eternity%20Bistro*%F0%9F%8D%9F%F0%9F%8D%94%0ATo%20order%20delicious%20food%20from%20us%20please%20fill%20the%20below%20information%20and%20hit%20send%F0%9F%98%8A%0A%0AMy%20name%3A%E2%80%A8%0A%0AMy%20order%20details%3A%0A%0A%E2%80%A8%E2%80%A8My%20full%20address%3A%0A%0APay%20using%20UPI%3A%20virajgophan%40okicici">Order on Whatsapp</a>
</h2>
<br>
<h2><a href="upi://pay?pa=8554801616@paytm&amp;pn=Rohit Joshi&amp;cu=INR&amp;mc=&amp;tr=1234&amp;tn=Paying+The+Indi+Eternity+Bistro" class="upi-pay1">Pay using UPI</a>
</h2>
<h4>Free delivery within 3 kms. Extra delivery charges will be applicable only if distance is more than 3kms. Please pay using above link after confirmation of amount (food + delivery charges) from us.</h4>
  {% assign array = "01,02" | split: ','%}
{% for item in array %}
  <img src="/assets/images/tieb/food/{{ item }}-food.jpg" alt="food-menu-{{ item }}" class="food-menu"/>
{% endfor %}
</ul>

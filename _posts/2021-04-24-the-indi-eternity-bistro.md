---
layout: hotel_index
title: The Indi Eternity Bistro
permalink: tieb
logo: /assets/images/tieb/tieb-logo.jpg
hotel_name: the-indi-eternity-bistro
---
<img src="/assets/images/tieb/tieb-logo.jpg" height="50%" width="50%">
<ul>
<li> 
<h2>
<a href="https://api.whatsapp.com/send?phone=+919834618102&text=Welcome+to+%F0%9F%8D%94%F0%9F%8D%9F%2AThe+Indi+Eternity+Bistro%2A%F0%9F%8D%9F%F0%9F%8D%94%0D%0ATo+order+delicious+food+from+us+please+fill+the+below+information+and+hit+send%F0%9F%98%8A%0D%0A%0D%0AMy+name%3A%E2%80%A8%0D%0A%0D%0AMy+order+details%3A+%0D%0A%0D%0A%E2%80%A8%E2%80%A8My+full+address%3A%0D%0A%0D%0APay+using+UPI%3A+virajgophan%40okicici">Order on Whatsapp</a>
</h2>
<br>
<h2><a href="upi://pay?pa=virajgophan@okicici&amp;pn=Viraj Gophan&amp;cu=INR&amp;mc=&amp;tr=1234&amp;tn=Paying+The+Indi+Eternity+Bistro" class="upi-pay1">Pay using UPI</a>
</h2>
<h4>Free delivery within 3 kms. Extra delivery charges will be applicable only if distance is more than 3kms. Please pay using above link after confirmation of amount (food + delivery charges) from us.</h4>
</li>
  {% assign array = "01,02" | split: ','%}
{% for item in array %}
  <img src="/assets/images/tieb/food/{{ item }}-food.jpg" alt="food-menu-{{ item }}" class="food-menu"/>
{% endfor %}
</ul>

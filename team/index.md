---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our lab!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/Screen Shot 2024-09-13 at 9.34.05 AM.png" dark=false %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/birthday_1.jpg" %}
{% include figure.html image="images/birthday_2.jpg" %}
{% include figure.html image="images/birthday_4.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

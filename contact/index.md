---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please connect with us if you're interested in joining us or collaborating! 

{%
  include button.html
  type="email"
  text="mcmarchetto@ucsd.edu"
  link="mcmarchetto@ucsd.edu"
%}
{%
  include button.html
  type="email"
  text="marchetto@salk.edu"
  link="marchetto@salk.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Social+Science+Research+Building/@32.8810707,-117.2405672,288m/data=!3m2!1e3!5s0x80dc06c1108ee56d:0xe4d745b5c56276f2!4m14!1m7!3m6!1s0x80dc06c4414caf4f:0xefb6aafc89913ea7!2sUniversity+of+California+San+Diego!8m2!3d32.881168!4d-117.2343605!16zL20vMDd2am0!3m5!1s0x80dc06c111311fd1:0xde91c40ce5892283!8m2!3d32.8807041!4d-117.2400766!16s%2Fg%2F12hll8_y_?entry=ttu&g_ep=EgoyMDI0MDkxMS4wIKXMDSoASAFQAw%3D%3D)"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/beatles"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/birthday_3"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

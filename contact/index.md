---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="alexander.mcgrath@sydney.edu.au"
  link="alexander.mcgrath@sydney.edu.au"
%}
{%
  include button.html
  type="phone"
  text="+61 0450241421"
  link="+61 0450241421"
%}
{%
  include button.html
  type="F22 Life, Earth and Environmental Sciences (LEES) Building"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/F22+Life,+Earth+and+Environmental+Sciences+(LEES)+Building/@-33.8887645,151.1904589,15z/data=!4m2!3m1!1s0x0:0x49c3efa3ba9cd14f?sa=X&ved=2ahUKEwjxh6nWmrX_AhV-m1YBHfVHDfwQ_BJ6BAhdEAg"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
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

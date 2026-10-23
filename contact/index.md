---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the [Institute of Mathematics](https://www.uni-osnabrueck.de/fb6/mathematik), at the school of [Mathematics/Computer Science/Physics](https://www.uni-osnabrueck.de/fb6).
We are located in building 66 [IUSF](https://www.usf.uni-osnabrueck.de) on the Westerberg campus.

{%
  include button.html
  type="email"
  text="frank.hilker@uni-osnabrueck.de"
  link="frank.hilker@uni-osnabrueck.de"
%}
{%
  include button.html
  type="phone"
  text="+49 541/969-3441"
  link="+49 541/969-3441"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/nDkoG3HwB1Ne3pou7"
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

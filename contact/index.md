---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

### We are affiliated with the Centre of Computational Biology, in Duke-NUS Medical School. Please don't hesitate to reach out to us for collaborations, questions, or if you are interested to work with us. 

{%
  include button.html
  type="email"
  text="huanchern_chia@duke-nus.edu.sg"
  link="huanchern_chia@duke-nus.edu.sg"
%}
{%
  include button.html
  type="email"
  text="elisabeth.tan@duke-nus.edu.sg"
  link="elisabeth.tan@duke-nus.edu.sg"
%}
{%
  include button.html
  type="phone"
  text="+65 6516 5240"
  link="+65 6516 5240"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/RWcE7spkDEUKSpU69"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/duke-nus.jpg"
  caption="Duke-NUS Medical School"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/duke-nus-2.jpg"
  caption="Main Lobby"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


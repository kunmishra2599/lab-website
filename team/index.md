---
title: Team
nav:
  order: 3
  tooltip: About our team
---
# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, alumni:false" %}
{% include list.html data="members" component="portrait" filters="role: phd, alumni:false" %}
{% include list.html data="members" component="portrait" filters="role: research-assistant,alumni:false" %}
<br>
{% include list.html data="members" component="portrait" filters="role: staff" %}

## Alumni
{% include list.html data="members" component="portrait" filters="alumni:true" %}

{% capture content %}

{% include figure.html image="images/lab-pic-1.jpg" %}
{% include figure.html image="images/lab-pic-2.jpg" %}
{% include figure.html image="images/ccb.jpg" %}
{% endcapture %}

{% include grid.html style="square" content=content %}

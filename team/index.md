---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the members of the team! All with a passion for the environment.

{% include section.html background="images/background.jpg" dark=true %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}

## Alumni

Gone but not forgotten!

{% include list.html data="alumni" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/IMG_0786.JPG" %}
{% include figure.html image="images/IMG_2322.JPG" %}
{% include figure.html image="images/IMG_1666.JPG" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

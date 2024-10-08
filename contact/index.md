---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our group is based at Imperial College London, at the Silwood Park Campus in Berkshire, UK.

{%
  include figure.html
  image="images/silwood.png"
  width="50" 
  height="25"
%}

{%
  include button.html
  type="email"
  text="e.cavan@imperial.ac.uk"
  link="mailto:e.cavan@imperial.ac.uk"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Imperial+College+London+Silwood+Park/@51.4091266,-0.6392096,15z/data=!4m2!3m1!1s0x0:0x8edfe0a7d58c9480?sa=X&ved=1t:2428&ictx=111"
%}

{% include section.html dark=true %}

{% capture col1 %}

{%
  include figure.html
  image="images/EFS.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/bbb_day.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


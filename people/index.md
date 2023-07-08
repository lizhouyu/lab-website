---
title: People
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}People

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.


{% include list.html data="members" component="portrait" filters="role: ap" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}

{% include section.html background="images/background.jpg" dark=true %}

{%
  include button.html
  text="Join us"
  link="join"
%}

{% include section.html %}


# {% include icon.html icon="fa-solid fa-users" %}Alumni



{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

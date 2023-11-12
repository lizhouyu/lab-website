---
title: People
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}People

## Director

{% include list.html data="members" component="portrait" filters="role: ap" %}

## Ph.D. Students

{% include list.html data="members" component="portrait" filters="role: phd, group: active" %}

## Master Students

{% include list.html data="members" component="portrait" filters="role: ms, group: active" %}

## Undergraduate Students

{% include list.html data="members" component="portrait" filters="role: undergrad, group: active" %}

## High School Students

{% include list.html data="members" component="portrait" filters="role: highschool, group: active" %}



{% include section.html background="images/background.jpg" dark=true %}

{%
  include button.html
  text="Join us"
  link="join"
%}

{% include section.html %}


# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include list.html data="members" component="portrait" filters="group: inactive" %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}

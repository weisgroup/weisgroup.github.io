---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Team Description

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: Postdoc" %}
{% include list.html data="members" component="portrait" filters="role: PhD" %}

{% include section.html background="images/background.jpg" dark=true %}

Alumni

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filters="role: Alumni" %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

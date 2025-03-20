---
title: selected publications 
nav:
  order: 1
  tooltip: Published works
---


# {% include icon.html icon="fa-solid fa-microscope" %}Publication

###### (underlined authors are students in our lab)
{% include section.html %}


## Highlighted


{% include citation.html lookup="PassiveBLE" style="rich" %}
{% include citation.html lookup="GPSense" style="rich" %}
{% include citation.html lookup="GPSMirror" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include publication-type.html type="journal" %}
{% include publication-type.html type="conference" %}

{% include search-info.html %}
{% include list.html data="citations" component="citation" style="rich" %}

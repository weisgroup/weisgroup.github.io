---
title: Join us
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Looking For Students/PostDocs
======
We are currently looking for highly motivated graduate (Ph.D. and master) and undergraduate students to work on research projects in wireless networking and mobile computing.
Candidates are expected to have solid background in network/mobile systems, and strong motivation towards academic excellence.
Hands-on system implementation and/or strong mathematical background is a big plus.

If interested and have the right background, please email me at weiwangw (AT) hust (DOT) edu (DOT) cn.

{%
  include button.html
  type="email"
  text="weiwang@hust(dot)edu(dot)cn"
  link="weiwangw@hust.edu.cn"
%}
{%
  include button.html
  type="phone"
  text="(852) 2719-0402 "
  link="(852) 2719-0402 "
%}
{%
  include button.html
  type="address"
  tooltip="华中科技大学东17楼F区"
  link="https://www.google.com/maps"
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

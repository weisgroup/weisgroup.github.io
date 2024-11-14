---
---

# MetaIoT Lab
[MetaIoT Lab](https://github.com/greenelab/lab-website-template) is a XXXX lab lead by Prof. Wei Wang [labs](https://www.greenelab.com/).
Our mission is to tackle significant real-world problems by identifying key challenges and developing groundbreaking solutions. We adopt a holistic research approach, blending rigorous theoretical exploration with practical implementations. Through this integrated process, we create, test, and refine prototypes, ensuring that our innovations are not only pioneering but also practical and ready for real-world application. Our cycle of continuous improvement drives us to adapt and evolve our solutions to meet changing needs effectively.

{% include carousel.html %}

## Research Overview
Our research group is at the forefront of developing innovative sensing, communication, and networking technologies to transform robotics, autonomous systems, and everyday devices. We tackle the full spectrum of challenges, from building an initial system prototype to understanding real problems, then developing a theoretical model, coming up with theoretical breakthroughs to practical prototype development for breakthroughs, and finally, deployment in the real world.
## Key Research Areas

{% capture text %}

- LowPower,LongRange Backscatter 
- BLE，WiFi,RFID 
- Universalwireless,batteryless, flexiblesticker-likesensing platorm

{%
  include button.html
  link="publication"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/areas/iot.jpg"
  link="publication"
  title="Ubiquitous loT"
  text=text
%}

{% capture text %}

- MultipleTechnologies:WiFi UWB,BLE,LTE,
- 5GNR PrivacypreservingSensing
- CM-accurateLocalization 

{%
  include button.html
  link="publication"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/areas/sensing.jpg"
  link="publication"
  title="Wireless Sensing"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

- Multi-sensorfusion:Radar, Camera,Lidar,GPS,IMU 
- Autonomous navigation,path  planning,
- Indoormapping Low-power reflective tags for smart infrastructure

{%
  include button.html
  link="team"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/areas/CAV.jpg"
  link="publication"
  title="Autonomous Vehicles"
  text=text
%}

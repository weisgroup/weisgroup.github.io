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

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: PhD" %}
{% include list.html data="members" component="portrait" filters="role: Ms" %}

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filters="role: Alumni" %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

PG Alumni
====
Mengnian Xu (Master student, 2018; Previously@WUT, 2014; now with ByteDance, Beijing)

Chao Liu (Master student, 2019; Previously@HUST, 2015; now a math teacher in a middle school in Shenzhen)

Hang Yang (Master student, 2018; Previously@Advanced Class, 2014; now a information science teach in a middle school in Shenzhen)

Yiyuan Wang (Master student, 2018; Previously@EIC, 2014; now with TP-link)

Yuheng Dan (Master student, 2019; Previously@WUT, 2015; now with Alibaba, Hangzhou)

Jun Qu (Master student, 2017-2020; now with Xiaomi, Beijing)

Sen Huang (Master student, 2017-2020; now with Huawei, Wuhan)

Ning Zhang (Master student, 2018-2020; Previously@Advanced Class, 2014; now with Xiaomi, Beijing)

Pan Wang ((Master student, 2018-2020; Previously@EIC, 2014; now an Officer)

Taobin Chen (Master student, 2017-2019; Excellent Engineer Program; now with Tencent, Shenzhen)

Ziliang Hu (Master student, 2017-2019; now with Netease, Guangzhou)

Xiaojie Yue (Master student, 2016-2019; Outstanding Graduate; now with Huawei, Shenzhen)

Bingjiang Cai (Master student, 2016-2018; Outstanding Graduate; now with China Railway Siyuan Survey and Design Group)

UG Alumni
====
Borui Wan (Outstanding Undergraduates; EIC, 2018; now PhD, Hong Kong University of Science and Technology)

Yifang Zhang (Outstanding Undergraduates; EIC, 2017; Now at NJU)

Kexin Tang (Outstanding Undergraduates; EIC, 2018；Now MS at UIUC)

Xiang Li (EEE, 2016; Now MS at CMU, under my reccomendation; visited Duke University under my recommendation)

Qian Du (Undergraduate, OEI, 2016; Now MS in ECE Department, UCLA under my recommendation)

Yuxuan Zhou (Outstanding Undergraduates; EIC, 2016; now PhD in CS Department, Hong Kong University of Science and Technology under my recommendation)

Zhenyu Lei (Outstanding Undergraduates; OEI, Excellent Engineer Program, 2016; now PhD in CS Department, UMass (Deepak Ganesan), under my recommendation; visited Cornell University as an intern under my recommendation)

Jinyang Liu (now M.S. at Northwestern University, U.S.)

Wei Huo (Outstanding Undergraduates; EIC, 2016; now PhD in ECE Department, Hong Kong University of Science and Technology)

Sheyang Tang (Excellent Engineer Program, 2015; now PhD at University of Waterloo under my recommendation)

Jianben He (Outstanding Undergraduates; Excellent Engineer Program, 2015; now PhD in CS Department, Hong Kong University of Science and Technology under my recommendation)

Xueyang Tang (Outstanding Undergraduate; Excellent Engineer Program, 2014; now PhD in CS Department, Hong Kong University of Science and Technology)

Minjie Tang (EIC, 2014; Now PhD in ECE Department, Hong Kong University of Science and Technology)

Yifan Hou (Advanced Class, 2014; PhD, ETH Zurich, Mphil in CS Department, Chinese University of Hong Kong)
Zhuoran Xiao (Advanced Class, 2014; now PhD in CS Department, Zhejiang University)



{% include grid.html style="square" content=content %}

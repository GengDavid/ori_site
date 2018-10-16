---
permalink: /
title: "Gengwei Zhang （张耕维）"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Senior Student  
School of Data & Computer Science  
Sun Yat-Sen university

## About Me ##
I am a senior student in [School of Data and Computer Science](http://sdcs.sysu.edu.cn/) at [Sun Yat-Sen university](http://www.sysu.edu.cn/2012/en/index.htm). Currently I'm working with Prof. [Zhuo Su](https://suzhuoi.github.io). My research interests lie in the field of Computer Vision and Deep Learning. I'm now researching on the area of Human Recognition, including multi-person pose estimation, human parsing etc.  


## Research Interest
* Computer Vsion
* Multimedia Computing
* Deep Learning
* Human Recognition


## Publications ##
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

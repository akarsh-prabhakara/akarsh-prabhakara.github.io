---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

 ![image-center](/images/research_themes.jpg){: .align-right width="329px"} My research builds fundamental principles and practical systems that define the next generation wireless perception and communication landscape. My research takes a full-stack approach building novel embedded hardware, machine learning and signal processing techniques, compute accelerators, and architecting end-end systems that manage constraints on communication, real-time latency and reliability. I am interested in pushing the limits with wireless to uncover new capabilities in robotics, automotive, and health. Finally, for such critical use-cases, I employ cyber-physical systems principles to create stable interaction loops of wireless-powered machines with the world.


{: .text-justify}

---

## Machine Learning Driven RF Systems

{% include base_path %}

{% assign my_research = "DART, RadarHD, cdhc" | split: ", " %}

{% for post in site.projects%}
  {% if my_research contains post.title %}
  	{% include archive-single.html %}
  {% endif %}
{% endfor %}


## New paradigms for RF communication systems

{% include base_path %}

{% assign my_research = "Hydra, Millimetro, Quasar, cdhc" | split: ", " %}

{% for post in site.projects%}
  {% if my_research contains post.title %}
  	{% include archive-single.html %}
  {% endif %}
{% endfor %}

## Wireless + Robotics

{% include base_path %}

{% assign my_research = "Metamorph, Avatars, Metamoran, cdhc" | split: ", " %}

{% for post in site.projects%}
  {% if my_research contains post.title %}
  	{% include archive-single.html %}
  {% endif %}
{% endfor %}

## Embedded applications of wireless signals

{% include base_path %}

{% assign my_research = "Osprey, TagFi, Platypus, cdhc" | split: ", " %}

{% for post in site.projects%}
  {% if my_research contains post.title %}
  	{% include archive-single.html %}
  {% endif %}
{% endfor %}
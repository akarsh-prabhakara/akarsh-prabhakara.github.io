---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

 ![image-center](/images/research_themes.jpg){: .align-right width="329px"} My research builds practical systems to address core problems spanning embedded, cyber-physical systems, wireless systems and robotics. I am interested in pushing the limits of radio frequency sensing capabilities on embedded scale platforms. With *high resolution, see-through imaging* from such tiny compute platforms: 
 {: .text-justify}
 - my work enables reliable perception in transportation, critical infrastructure monitoring and robotics in harsh conditions. I want to build on top of this perception and close the loop to create practical, full fledged autonomous systems.
 {: .text-justify} 
 - my work augments next generation communication devices to be ultra-aware of their environment. I have built communication systems that learn from their environment in new ways to schedule resources efficiently, manifesting in large improvements in signal strength and throughput.
{: .text-justify}
 - we can envision radio frequency sensing to be deployed on emerging portable, handheld and wearable devices. This opens up new possibilities to look through new types of occlusions in new scenarios, enabling new applications.
{: .text-justify}

My research takes a full-stack approach building novel embedded hardware, machine learning and signal processing techniques, compute accelerators, and architecting end-end system to manage constraints on communication, real-time latency and reliability.
{: .text-justify}

---

## Selected Research Projects

{% include base_path %}

{% assign my_research = "Osprey, Millimetro, Metamoran, RadarHD, cdhc" | split: ", " %}

{% for post in site.projects%}
  {% if my_research contains post.title %}
  	{% include archive-single.html %}
  {% endif %}
{% endfor %}
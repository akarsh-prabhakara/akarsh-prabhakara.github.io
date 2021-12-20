---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

 ![image-center](/images/research.png){: .align-right width="329px"} Visual sensors such as cameras are ubiquitous today in almost all our devices. Lidars can perceive even in the absence of ambient light. However, for perceiving objects in non line of sight conditions, through thick smoke or fog or debris, visible and infrared light doesn't penetrate all the way. Radio frequency is known to pass through buildings and walls and reach your cell phones from towers far away. The field of **wireless sensing** uses radio frequency signals to perceive the world in conditions challenging to other wavelengths. 
{: .text-justify}

 As can be seen from the figure, today's state-of-the-art RF sensors are inferior in many aspects compared to lidars and cameras. For example, while camera and lidar offer angular resolutions of about 0.01&deg; and 0.1&deg; respectively, the best radars are atleast 10 times worser. In my research, I build **application-specific RF sensing** systems that address some of these challenges using signal processing, hardware design, machine learning and sensor fusion techniques. 
 {: .text-justify}

---

{% include base_path %}
{% for post in site.projects reversed %}
      {% include archive-single.html %}
{% endfor %}
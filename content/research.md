+++
title = "Research"
menu = "main"
weight = 10
+++

---

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:20px;">

  <!-- Image column -->
  <div style="flex:0 0 300px; text-align:center;">
  <br>
  <br>
    <img src="/images/research_themes.jpg" alt="Description" style="width:100%; max-width:300px; border-radius:8px;">
  </div>

  <!-- Text column -->
  <div style="flex:1; min-width:250px;">
    <p>
    My research builds fundamental principles and practical systems that define the next generation wireless perception and communication landscape. My research takes a full-stack approach building novel embedded hardware, machine learning and signal processing techniques, compute accelerators, and architecting end-end systems that manage constraints on communication, real-time latency and reliability. I am interested in pushing the limits with wireless to uncover new capabilities in robotics, automotive, and health. For critical use-cases, I employ cyber-physical systems principles to create stable interaction loops of wireless-powered machines with the world.
    </p>
    <p>
  </div>

</div>

---

## Machine Learning Driven RF Systems

<h3 id="dart">DART</h3>

<img src="/images/dart_sq.jpg" alt="DART" style="float:right; width:300px; margin:10px 10px 10px 10px;">

Realistic radar simulation requires careful 3D modeling of a virtual world with accurate material properties and modeling all types of EM wave interactions with it. Previously we have seen *explicit* approaches for direct modeling or radar imaging followed by simulated view rendering. These explicit approaches are hard to design for practical, crowded scenes with heterogenous material composition and challenging multipath interaction. We propose an *implicit* neural rendering approach to produce accurate simulation of radar measurements from novel view points. As a by-product of our approach, we are also able to produce high quality radar images of scenes, akin to synthetic aperture imaging, but without any explicit modeling.

[Full Paper](/files/dart-cvpr24.pdf) &#124;
[Code](https://github.com/WiseLabCMU/dart) &#124;
[Dataset](https://github.com/WiseLabCMU/rover) &#124;
[Video](https://www.youtube.com/watch?v=CYIFjJp-IOM) <br>
<span style="color: red;">*CVPR Oral*</span> <br>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h3 id="radarhd">RadarHD</h3>

<img src="/images/radarhd-2.jpg" alt="RadarHD" style="float:left; width:300px; margin:10px 10px 10px 10px;">

How can we enable high quality perception for robots navigating in harsh environments with smoke or fog? Camera or lidar based perception would suffer in these conditions. We explore a millimeter wave radar based perception for seeing past these occlusions. We combat the poor spatial resolution of these radars by training an end-to-end deep learning super-resolution network that outputs *lidar-like* point clouds from just a cheap, single-chip radar!  We also show RadarHD's robustness in smoke by testing with smoke bombs in a smoke chamber.

[ICRA Paper](/files/radarhd-icra23.pdf) &#124;
[Extended Paper](https://arxiv.org/abs/2206.09273) &#124;
[Demo Link](https://www.youtube.com/watch?v=me8ozpgyy0M) &#124; 
[Slides](https://docs.google.com/presentation/d/10PZ3w1gmvSjGArqaNUhJiEY29zo8bQZU/edit?usp=sharing&ouid=111709944551033943094&rtpof=true&sd=true) &#124;
[Talk](https://drive.google.com/file/d/1YJ_7sYA-DEketsJbUBbzHp7P4u8hBVye/view?usp=sharing) &#124;
[Poster](https://drive.google.com/file/d/1z9V4iFjsPxpxJtv44QEKEYUcshxA5qDV/view?usp=sharing) &#124;
[Code and Dataset](https://github.com/akarsh-prabhakara/RadarHD)<br>
<span style="color: red;">*Top-5 Demos (MobiCom 2023)*</span> <br>

---

## New paradigms for RF communication systems

<h3 id="hydra">Hydra</h3>

<img src="/images/hydra_sq.jpg" alt="Hydra" style="float:right; width:300px; margin:10px 10px 10px 10px;">

Conventional radar processing only allows estimating the spatial locations of objects in the incident field of view. But, in practice, the radio waves bounce off objects in the field of view and illuminate hidden objects. Can we leverage this multi-bouce effect and image scenes beyond the field of view of a typical mmWave radar? We propose algorithms that can tackle double and triple bounces to expand the field of view to even diametrically opposite to the incident beam!  

[Full Paper](/files/hydra-mobicom24.pdf)

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h3 id="millimetro">Millimetro</h3>

<img src="/images/millimetro.png" alt="Millimetro" style="float:left; width:300px; margin:10px 10px 10px 10px;">

How can cars perceive critical roadside infrastructure even when weather conditions are not favorable for visual sensors? Millimetro tackles this by designing low power radio frequency tags that can be mounted on such infrastructure and builds decoding algorithms that run on radars in cars to decode, identify and accurately localize tags. 

[Full Paper](/files/millimetro-mobicom21.pdf) &#124;
[Demo Paper](/files/millimetro-demo-mobicom21.pdf) &#124;
[Talk](https://www.youtube.com/watch?v=tJGNltixOXA)<br>
*Press*: [UIUC](https://cs.illinois.edu/news/soltanaghais-millimetro-delivers-a-low-power-high-accuracy-tag-that-can-improve-applications-ranging-from-autonomous-driving-to-the-metaverse) &#124;
  [Pioneering Minds](https://www.pioneeringminds.com/low-power-high-accuracy-tag-improve-autonomous-driving/)<br>
<span style="color: red;"> *Best Demo Runner Up (MobiCom 2021)*</span> <br>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h3 id="quasar">Quasar</h3> 

<img src="/images/quasar_sq.jpg" alt="Quasar" style="float:right; width:300px; margin:10px 10px 10px 10px;">

Low Earth Orbit cubesats and nanosats satellites have paved the way for missions with cheaper launch costs. But, ground infrastructure for communication remains bulky and expensive. Quasar proposes to alleviate this problem by democratizing access to satellite transmissions at the cost of a few RTL-SDRs. The key idea behind Quasar is to leverage a network of cheap radios to mimic one single expensive radio. Quasar achieves this by tackling challenges with respect to synchronizing the cheap radios, dealing with high doppler spread and central aggregation of high bandwidth raw radio streams.

[Full Paper](/files/quasar-mobicom21.pdf) &#124;
[Video](https://www.youtube.com/watch?v=R8Q8ap6fN4k)<br>
<span style="color: red;">*ACM GetMobile Research Highlight*</span>

--- 

## Wireless + Robotics

<h3 id="metamorph">Metamorph</h3>

<img src="/images/metamorph.png" alt="Metamorph" style="float:left; width:300px; margin:10px 10px 10px 10px;">

Can inflatable robots enhance wireless communication? We show that by placing an array of shape-morphing inflatable robots near an antenna we can boost the signal quality received at the antenna. Our methodology is best suited for base stations that need to adapt to slow moving changes --- such as seasonal effects. For a Low-Power Wide Area Network link, we show that deploying this at the gateway can have significant improvements to signal quality and yields huge battery savings.
<br> 

[Full Paper](/files/metamorph-icra25.pdf) &#124;
[Code](https://github.com/yawenliu-ece/MetaMorph)

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h3 id="avatars">Avatars</h3> 

<img src="/images/avatars.jpg" alt="Avatars" style="float:right; width:300px; margin:10px 10px 10px 10px;">

How can we maximize rendezvous opportunities for autonomous robots with sperm whales? We propose an autonomy and sensing module to this end. The sensing module on a drone performs a VHF synthetic aperture radar based whale positioning when the whale surfaces and uses underwater acoustic sensors to track whales under water. Using the sensing module's data, we build a reinforcement learning algorithm that plans where autonomous robots should be dispatched to maximize chances of whale rendezvous.  

[Full Paper](/files/avatars-scirobotics24.pdf)

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h3 id="metamoran">Metamoran</h3> 

<img src="/images/metamoran.jpg" alt="Metamoran" style="float:left; width:300px; margin:10px 10px 10px 10px;">

How can we enable single vantage point depth imaging that works at long ranges to build simple-to-deploy but high quality survelliance systems? Metamoran proposes a monocular camera-radar fusion solution that leverages the pros of each sensor to combat the cons and provides an accurate depth image of various objects even at long ranges.

[Full Paper](/files/metamoran-iros22.pdf) &#124;
[Slides](https://docs.google.com/presentation/d/1-sennGYCLc8R9F7-4osnNiQKeEnRyXY0/edit?usp=sharing&ouid=111709944551033943094&rtpof=true&sd=true) &#124;
[Talk](https://drive.google.com/file/d/1-2UJ0AMo6xg-Fy3Djt43waVCD1JnJpyy/view?usp=sharing)

---

## Embedded applications of wireless signals

<h3 id="osprey">Osprey</h3>

<img src="/images/osprey.jpg" alt="Metamorph" style="float:right; width:300px; margin:10px 10px 10px 10px;">

Tire wear affects safety and performance of automobiles. Past solutions are either inaccurate, require sensors embedded in tires or are prone to road debris. Osprey proposes a radio frequency tire wear sensing system design, based on automotive millimeter wave radars, to overcome challenges related to road debris. We design super resolution algorithms to measure millimeter-level changes due to wear and tear. In addition, the principles used also open up solutions for detecting and localizing harmful metallic foreign objects in the tire.
<br> 

 [Full Paper](/files/osprey-mobisys20.pdf) &#124;
 [Demo Paper](/files/osprey-demo-mobisys20.pdf) &#124;
 [Magazine](/files/osprey-getmobile21.pdf) &#124;
 [Slides](https://drive.google.com/file/d/1IhwnS1KSGDmiKOGz1JiVGAjnr-BQlAB6/view?usp=sharing) &#124; [Talk](https://www.youtube.com/watch?v=y-haR7Vc01o) &#124;
 [Video-1min](https://www.youtube.com/embed/tGFg0Vhi2uY?start=66&end=127) &#124; [Video-3min](https://www.youtube.com/watch?v=jhasOfGaS5w) <br>

 *Press*: [CMU](https://www.ece.cmu.edu/news-and-events/story/2020/07/sensing-tire-wear.html) &#124; [Gizmodo](https://gizmodo.com/researchers-find-that-radar-can-be-used-to-detect-a-nai-1844635816) &#124; [Hackster.io](https://www.hackster.io/news/researchers-develop-system-that-monitors-tire-wear-in-real-time-4ff4d9c738f3) &#124; [That's Cool News - Podcast](https://thatscoolnews.com/episode/21-osprey-mmwaves-sense-tire-wear-akarsh/)&#124; 
 [Weibold](https://weibold.com/radar-to-monitor-tire-wear-developed-by-american-engineers) &#124;
 [Interesting Engineering](https://interestingengineering.com/innovation/radar-can-be-used-to-detect-tire-wear-and-tear-nail-punctures) &#124;
 [Wonderful Engineering](https://wonderfulengineering.com/this-radar-based-device-can-detect-tire-punctures-along-with-wear-and-tear/) &#124;
 [Tyrepress.com](https://www.tyrepress.com/2020/08/measuring-tyre-wear-with-on-car-radar/)

<span style="color: red;">*Best Paper Honorable Mention (MobiSys 2020)*</span><br>
<span style="color: red;">*Best Demo (MobiSys 2020)*</span> <br>
<span style="color: red;">*ACM GetMobile Research Highlight*</span>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h3 id="tagfi">TagFi</h3> 

<img src="/images/tagfi_sq.jpg" alt="Avatars" style="float:left; width:300px; margin:10px 10px 10px 10px;">

How can we locate important and often misplaced objects-of-interest like keys, wallets, tools? Prior works that involve buildings tags for objects either need supporting custom infrastructure or the tags are power hungry for multi-year timescales. We turn to already existing and widely deployed WiFi networks for infrastructure support and build custom extremely low power tags. The user can simply forget about the tag for years. Our algorithms can locate tags (objects) with fine-grained accuracy and provide seamless context awareness with just unmodified WiFi. 

[Full Paper](/files/tagfi-ubicomp21.pdf) &#124;
[Talk](https://www.youtube.com/watch?v=w5HQwYWjbg8) &#124;
[Demo Video](https://www.youtube.com/watch?v=gnSSzYrRU6o)

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h3 id="platypus">Platypus</h3> 

<img src="/images/platypus_sq.jpg" alt="Metamoran" style="float:right; width:300px; margin:10px 10px 10px 10px;">

How can we continuously monitor the development of miniature cracks in today's aging public infrastructure like bridges? This would inform decisions on safety and maintenance of these critical structures well in advance. Past work has looked at coarse grained structure health monitoring. Platypus builds novel signal processing and low power hardware tags to mount on bridges. We enable a new operating point that can measure micro-displacements of structures over years and in extreme weather conditions. 

[Full Paper](/files/platypus-ipsn23.pdf) &#124;
[Demo Paper](/files/platypus-demo-ipsn23.pdf) &#124;
[Video](https://www.youtube.com/watch?v=M8HkvFgZx9I)<br>

<span style="color: red;">*Best Demo Runner Up (IPSN 2023)*</span>
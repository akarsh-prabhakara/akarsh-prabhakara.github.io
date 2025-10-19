+++
title = "Research"
menu = "main"
weight = 10
+++

---

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <!-- Text column -->
  <div style="flex:1; min-width:250px;">
    <p>
    My research builds fundamental principles and practical systems that define the next generation wireless perception and communication landscape. My research takes a full-stack approach building novel embedded hardware, machine learning and signal processing techniques, compute accelerators, and architecting end-end systems that manage constraints on communication, real-time latency and reliability. I am interested in pushing the limits with wireless to uncover new capabilities in robotics, automotive, and health. For critical use-cases, I employ cyber-physical systems principles to create stable interaction loops of wireless-powered machines with the world.
    </p>
  </div>
  <!-- Image column -->
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/research_themes.jpg" alt="Description" style="width:100%; max-width:300px; border-radius:8px;">
  </div>

</div>

---

<h3 id="ML">Learning driven RF perception</h3>

<h4 id="grt">GRT</h4>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
      GPT for radars? GRT! mmWave radars have great potential for robotic perception. Learning approaches (such as <a href="/research/#radarhd">RadarHD</a>) that address fundamental limits of mmWave radars have demonstrated initial hope for high fidelity perception. But, such efforts have largely been on small datasets that are task-specific and trained from scratch. This paper takes learning on radar data to new levels. We present the largest (publicly available) raw radar dataset, an open-source data collection tool chain, a foundational model-esque training that scales to several perception tasks and a scaling law that answers how much more data is needed to fully exploit the power of a foundational model.
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/grt.jpg" alt="GRT" style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
    <a href="/files/grt-iccv25.pdf">Full Paper</a>, <a href="https://www.youtube.com/watch?v=AIWhM32jx0o">Video</a><br>
    <span style="color: red;"><em>ICCV Oral</em></span> <br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="dart">DART</h4>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
      Realistic radar simulation requires careful 3D modeling of a virtual world with accurate material properties and modeling all types of EM wave interactions with it. Previously we have seen explicit approaches for direct modeling or radar imaging followed by simulated view rendering. These explicit approaches are hard to design for practical, crowded scenes with heterogenous material composition and challenging multipath interaction. We propose an implicit neural rendering approach to produce accurate simulation of radar measurements from novel view points. As a by-product of our approach, we are also able to produce high quality radar images of scenes, akin to synthetic aperture imaging, but without any explicit modeling.
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/dart_sq.jpg" alt="DART" style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
    <a href="/files/dart-cvpr24.pdf">Full Paper</a>,
    <a href="https://github.com/WiseLabCMU/dart">Code</a>,
    <a href="https://github.com/WiseLabCMU/rover">Dataset</a>,
    <a href="https://www.youtube.com/watch?v=CYIFjJp-IOM">Video</a><br>
    <span style="color: red;"><em>CVPR Oral</em></span> <br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="radarhd">RadarHD</h4>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
    How can we enable high quality perception for robots navigating in harsh environments with smoke or fog? Camera or lidar based perception would suffer in these conditions. We explore a millimeter wave radar based perception for seeing past these occlusions. We combat the poor spatial resolution of these radars by training an end-to-end deep learning super-resolution network that outputs lidar-like point clouds from just a cheap, single-chip radar!  We also show RadarHD's robustness in smoke by testing with smoke bombs in a smoke chamber.
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/radarhd-2.jpg" alt="RadarHD"  style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
    <a href="/files/radarhd-icra23.pdf">ICRA Paper</a>,
    <a href="https://arxiv.org/abs/2206.09273">Extended Paper</a>,
    <a href="https://www.youtube.com/watch?v=me8ozpgyy0M">Demo Link</a>,
    <a href="https://docs.google.com/presentation/d/10PZ3w1gmvSjGArqaNUhJiEY29zo8bQZU/edit?usp=sharing&ouid=111709944551033943094&rtpof=true&sd=true">Slides</a>,
    <a href="https://drive.google.com/file/d/1YJ_7sYA-DEketsJbUBbzHp7P4u8hBVye/view?usp=sharing">Talk</a>,
    <a href="https://drive.google.com/file/d/1z9V4iFjsPxpxJtv44QEKEYUcshxA5qDV/view?usp=sharing">Poster</a>,
    <a href="https://github.com/akarsh-prabhakara/RadarHD">Code and Dataset</a><br>
    <span style="color: red;"><em>Top-5 Demos (MobiCom 2023)</em></span> <br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="metamoran">Metamoran</h4> 

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  How can we enable single vantage point depth imaging at long ranges to build simple-to-deploy but high quality survelliance systems? Metamoran proposes a monocular camera-radar fusion solution that leverages the pros of each sensor to combat the cons and provides an accurate depth image of various objects even at long ranges.
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/metamoran.jpg" alt="Metamoran" style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
  <a href="/files/metamoran-iros22.pdf">Full Paper</a>,
  <a href="https://docs.google.com/presentation/d/1-sennGYCLc8R9F7-4osnNiQKeEnRyXY0/edit?usp=sharing&ouid=111709944551033943094&rtpof=true&sd=true">Slides</a>,
  <a href="https://drive.google.com/file/d/1-2UJ0AMo6xg-Fy3Djt43waVCD1JnJpyy/view?usp=sharing">Talk</a><br>
  </p>
  </div>
</div>

--- 

<h3 id="robotics">Wireless + robotics</h3>

<h4 id="metamorph">Metamorph</h4>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  Can inflatable robots enhance wireless communication? We show that by placing an array of shape-morphing inflatable robots near an antenna we can boost the signal quality received at the antenna. Our methodology is best suited for base stations that need to adapt to slow moving changes --- such as seasonal effects. For a Low-Power Wide Area Network link, we show that deploying this at the gateway can have significant improvements to signal quality and yields huge battery savings.
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/metamorph.png" alt="Metamorph"  style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
  <a href="/files/metamorph-icra25.pdf">Full Paper</a>,
  <a href="https://github.com/yawenliu-ece/MetaMorph">Code</a><br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="avatars">Avatars</h4> 


<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  How can we maximize rendezvous opportunities for autonomous robots with sperm whales? We propose an autonomy and sensing module to this end. The sensing module on a drone performs a VHF synthetic aperture radar based whale positioning when the whale surfaces and uses acoustic sensors to track whales under water. Using the sensing module's data, we build a reinforcement learning algorithm that plans where autonomous robots should be dispatched to maximize chances of whale rendezvous.  
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/avatars.jpg" alt="Avatars" style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
  <a href="/files/avatars-scirobotics24.pdf">Full Paper</a><br>
  </p>
  </div>
</div>

---

<h3 id="comms">New wireless communication paradigms</h3>

<h4 id="hydra">Hydra</h4>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  Conventional radar processing only allows estimating the spatial locations of objects in the incident field of view. But, in practice, the radio waves bounce off objects in the field of view and illuminate hidden objects. Can we leverage this multi-bouce effect and image scenes beyond the field of view of a typical mmWave radar? We propose algorithms that can tackle double and triple bounces to expand the field of view to even diametrically opposite to the incident beam! 
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/hydra_sq.jpg" alt="Hydra"  style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
    <a href="/files/hydra-mobicom24.pdf">Full Paper</a><br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="millimetro">Millimetro</h4>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  How can cars perceive critical roadside infrastructure even when weather conditions are not favorable for visual sensors? Millimetro tackles this by designing low power radio frequency tags that can be mounted on such infrastructure and builds decoding algorithms that run on radars in cars to decode, identify and accurately localize tags, and thus perceive critical infrastructure.
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/millimetro.png" alt="Millimetro"  style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
  <a href="/files/millimetro-mobicom21.pdf">Full Paper</a>,
  <a href="/files/millimetro-demo-mobicom21.pdf">Demo Paper</a>,
  <a href="https://www.youtube.com/watch?v=tJGNltixOXA">Talk</a><br>
  <em>Press</em>: <a href="https://cs.illinois.edu/news/soltanaghais-millimetro-delivers-a-low-power-high-accuracy-tag-that-can-improve-applications-ranging-from-autonomous-driving-to-the-metaverse">UIUC</a>,
    <a href="https://www.pioneeringminds.com/low-power-high-accuracy-tag-improve-autonomous-driving/">Pioneering Minds</a><br>
  <span style="color: red;"> <em>Best Demo Runner Up (MobiCom 2021)</em></span> <br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="quasar">Quasar</h4> 

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  Low Earth Orbit cubesats and nanosats satellites have paved the way for missions with cheaper launch costs. But, ground infrastructure for communication remains bulky and expensive. Quasar proposes to alleviate this problem by democratizing access to satellite transmissions at the cost of a few RTL-SDRs. The key idea behind Quasar is to leverage a network of cheap radios to mimic one single expensive radio. Quasar achieves this by tackling challenges with respect to synchronizing the cheap radios, dealing with high doppler spread and central aggregation of high bandwidth raw radio streams.
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/quasar_sq.jpg" alt="Quasar"  style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
  <a href="/files/quasar-mobicom21.pdf">Full Paper</a>,
  <a href="https://www.youtube.com/watch?v=R8Q8ap6fN4k">Video</a><br>
  <span style="color: red;"><em>ACM GetMobile Research Highlight</em></span>
  </p>
  </div>
</div>

---

<h3 id="ubi">Ubiquitous wireless sensing </h3>

<h4 id="osprey">Osprey</h4>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  Tire wear affects safety and performance of automobiles. Past solutions are either inaccurate, require sensors embedded in tires or are prone to road debris. Osprey proposes a radio frequency tire wear sensing system design, based on automotive millimeter wave radars, to overcome challenges related to road debris. We design super resolution algorithms to measure millimeter-level changes due to wear and tear. In addition, the principles used also open up solutions for detecting and localizing harmful metallic foreign objects in the tire.  
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/osprey.jpg" alt="Osprey" style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:100%;">
  <p>
  <a href="/files/osprey-mobisys20.pdf">Full Paper</a>,
  <a href="/files/osprey-demo-mobisys20.pdf">Demo Paper</a>,
  <a href="/files/osprey-getmobile21.pdf">Magazine</a>,
  <a href="https://www.youtube.com/watch?v=y-haR7Vc01o">Talk</a>,
  <a href="https://drive.google.com/file/d/1IhwnS1KSGDmiKOGz1JiVGAjnr-BQlAB6/view?usp=sharing">Slides</a>,
  <a href="https://www.youtube.com/embed/tGFg0Vhi2uY?start=66&end=127">Video-1min</a>,
  <a href="https://www.youtube.com/watch?v=jhasOfGaS5w">Video-3min</a><br>
  <em>Press</em>: <a href="https://www.ece.cmu.edu/news-and-events/story/2020/07/sensing-tire-wear.html">CMU</a>,
    <a href="https://gizmodo.com/researchers-find-that-radar-can-be-used-to-detect-a-nai-1844635816">Gizmodo</a>,
    <a href="https://www.hackster.io/news/researchers-develop-system-that-monitors-tire-wear-in-real-time-4ff4d9c738f3">Hackster.io</a>,
    <a href="https://thatscoolnews.com/episode/21-osprey-mmwaves-sense-tire-wear-akarsh/">That's Cool News Podcast</a>,
    <a href="https://weibold.com/radar-to-monitor-tire-wear-developed-by-american-engineers">Weibold</a>,
    <a href="https://interestingengineering.com/innovation/radar-can-be-used-to-detect-tire-wear-and-tear-nail-punctures">Interesting Engineering</a>,
    <a href="https://wonderfulengineering.com/this-radar-based-device-can-detect-tire-punctures-along-with-wear-and-tear/">Wonderful Engineering</a>,
    <a href="https://www.tyrepress.com/2020/08/measuring-tyre-wear-with-on-car-radar/">Tyrepress.com</a><br>
  <span style="color: red;"> <em>Best Paper Honorable Mention (MobiSys 2020)</em></span> <br>
  <span style="color: red;"> <em>Best Demo (MobiSys 2020)</em></span> <br>
  <span style="color: red;"> <em>ACM GetMobile Research Highlight</em></span> <br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="tagfi">TagFi</h4> 

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  How can we locate important and often misplaced objects-of-interest like keys, wallets, tools? Prior works either need power hungry tags attached to these objects or custom supporting infrastructure to manage tags. We turn to already existing and widely deployed WiFi networks for infrastructure support and build custom extremely low power tags. The user can simply forget about the tag for years. Our algorithms can locate objects with fine-grained accuracy and provide seamless context awareness with just unmodified WiFi. 
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/tagfi_sq.jpg" alt="Avatars" style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
  <a href="/files/tagfi-ubicomp21.pdf">Full Paper</a>,
  <a href="https://www.youtube.com/watch?v=w5HQwYWjbg8">Talk</a>,
  <a href="https://www.youtube.com/watch?v=gnSSzYrRU6o">Demo Video</a><br>
  </p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #ccc; margin:20px 0;">

<h4 id="platypus">Platypus</h4> 

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:10px;">

  <div style="flex:1; min-width:250px;">
  <p>
  How can we continuously monitor the development of miniature cracks in today's aging public infrastructure like bridges? This would inform decisions on safety and maintenance of these critical structures well in advance. Past work has looked at coarse grained structure health monitoring. Platypus builds novel signal processing and low power hardware tags to mount on bridges. We enable a new operating point that can measure micro-displacements of structures over years and in extreme weather conditions. 
  </p>
  </div>
  <div style="flex:0 0 30%; text-align:center;">
  <br>
  <br>
    <img src="/images/platypus_sq.jpg" alt="Metamoran" style="width:100%; max-width:300px; border-radius:8px;">
  </div>
  <div style="flex:1; min-width:250px;">
  <p>
  <a href="/files/platypus-ipsn23.pdf">Full Paper</a>,
  <a href="/files/platypus-demo-ipsn23.pdf">Demo Paper</a>,
  <a href="https://www.youtube.com/watch?v=M8HkvFgZx9I">Video</a><br>
  <span style="color: red;"><em>Best Demo Runner Up (IPSN 2023)</em></span><br>
  </p>
  </div>
</div>

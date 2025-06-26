---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}
<p><span class="anchor" id="about-me"></span></p>
<p>
👋 Hi there! My name is <a class="red-label">Chuyang Xiao</a>. I am a senior undergraduate student majoring in computer science at **ShanghaiTech University**. Currently, I have joined the 4DV Lab, under the mentorship of <a href="http://yuexinma.me/">Prof. Yuexin Ma</a>. During 2023-2024 academic year, I was an exchange student at **University of California Berkeley**.
I will be joining the **MSR(Master of Science in Robotics)** program at **Carnegie Mellon University** in Fall 2025. 🌻
</p>
<p>
  
</p>
<p>
  
</p>
<p>
  
</p>


<h1 id="-publications">📝 Publications</h1>
<p style="color: #3f446a; margin: 0%; font-weight: 350;">* Indicates Equal Contribution † Indicates Corresponding Author</p>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge-coming"><b>Under review</b></div>
      <img src="images/Freqpolicy.png" alt="sym" width="100%" />
    </div>
  </div>
  <div class="paper-box-text">
    <p>
      <a style="text-decoration: underline;" href="https://freq-policy.github.io/">FreqPolicy: Frequency Autoregressive Visuomotor Policy with Continuous Tokens</a>
    </p>
    <p>
      <b>Yiming Zhong, Yumeng Liu, <b>Chuyang Xiao</b>, Zemin Yang, Youzhuo Wang, Yufei Zhu, Yujing Sun, Xinge Zhu, Yuexin Ma†
    </p>
    <p>This paper proposes FreqPolicy, a frequency-domain autoregressive visuomotor policy that progressively models hierarchical frequency components with continuous latent representations, achieving superior accuracy and efficiency in robotic manipulation tasks.</p>
    <a href="https://arxiv.org/pdf/2506.01583" class="pdf-link" target="_blank">PDF</a>
    <a href="https://freq-policy.github.io/" class="paper-box-link" target="_blank">
    Page <i class="fas fa-external-link-alt"></i></a>
    <a href="https://freq-policy.github.io/" class="paper-box-link" target="_blank">Github <i class="fab fa-github"></i> </a>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge-coming"><b>ICCV 2025</b></div>
      <img src="images/DexH2R.png" alt="sym" width="100%" />
    </div>
  </div>
  <div class="paper-box-text">
    <p>
      <a style="text-decoration: underline;" href="">DexH2R: A Benchmark for Dynamic Dexterous Grasping in Human-to-Robot Handover</a>
    </p>
    <p>
      Youzhuo Wang*, Jiayi Ye*, <b>Chuyang Xiao</b>, Yiming Zhong, Heng Tao, Hang Yu, Yumeng Liu, Jingyi Yu, Yuexin Ma†
    </p>
    <p>This paper introduces DexH2R, a real-world dataset for human-to-robot handovers featuring dexterous motions, diverse objects, and rich annotations. Using teleoperation, it captures natural human-like behaviors for robotic learning. We also propose DynamicGrasp, a handover solution, and benchmark state-of-the-art methods, providing key insights for future work. </p>
    <a href="" class="pdf-link" target="_blank">PDF</a>
    <a href="" class="paper-box-link" target="_blank">
    Page <i class="fas fa-external-link-alt"></i></a>
    <a href="" class="paper-box-link" target="_blank">Github <i class="fab fa-github"></i> </a>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge-IMWUT"><b>ICRA 2025</b></div>
      <img src="images/T2V.png" alt="sym" width="100%" />
    </div>
  </div>
  <div class="paper-box-text">
    <p>
      <a style="text-decoration: underline;" href="https://sites.google.com/view/mixedtrafficplus">Optimizing Efficiency of Mixed Traffic through Reinforcement Learning: A Topology-Independent Approach and Benchmark</a>
    </p>
    <p>
      <b>Chuyang Xiao*</b>, Daiwei Wang*, Xinzheng Tang, Jia Pan, Yuexin Ma†
    </p>
    <p>This paper presents three main contributions to mixed traffic control: (1) the first large-scale real-world benchmark with 444 scenarios from 20 countries; (2) a model-free RL method using Robot Vehicles to optimize traffic flow; (3) superior performance demonstrated in intersections and roundabouts. The benchmark enables realistic policy evaluation in diverse environments.</p>
    <a href="https://arxiv.org/abs/2501.16728" class="pdf-link" target="_blank">PDF</a>
    <a href="https://sites.google.com/view/mixedtrafficplus" class="paper-box-link" target="_blank">
    Page <i class="fas fa-external-link-alt"></i></a>
    <a href="https://github.com/xiaochy/MixedTraffic-Benchmark" class="paper-box-link" target="_blank">Github <i
        class="fab fa-github"></i> </a>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge-IMWUT"><b>CVPRW 2024</b></div>
      <img src="images/dexgraspanyting.png" alt="sym" width="100%" />
    </div>
  </div>
  <div class="paper-box-text">
    <p>
      <a style="text-decoration: underline;" href="https://openaccess.thecvf.com/content/CVPR2024W/EvGenFM/papers/Ji_T2VBench_Benchmarking_Temporal_Dynamics_for_Text-to-Video_Generation_CVPRW_2024_paper.pdf">T2VBench: Benchmarking Temporal Dynamics for Text-to-Video Generation</a>
    </p>
    <p>
      Pengliang Ji*, <b>Chuyang Xiao*</b>, Huilin Tai, Mingxiao Huo
    </p>
    <p>This work introduces T2VBench, the first comprehensive benchmark for evaluating text-to-video models' temporal dynamics. Key contributions include: (1) a hierarchical framework with 1,600+ temporal prompts and 5,000 human-rated videos across 16 dimensions; (2) systematic evaluation of leading models (ZeroScope, Pika) revealing their temporal capabilities and limitations; (3) insights for improving future T2V metrics. The benchmark enables rigorous temporal analysis in video generation.</p>
    <a href="https://openaccess.thecvf.com/content/CVPR2024W/EvGenFM/papers/Ji_T2VBench_Benchmarking_Temporal_Dynamics_for_Text-to-Video_Generation_CVPRW_2024_paper.pdf" class="pdf-link" target="_blank">PDF</a>
    <a href="https://openaccess.thecvf.com/content/CVPR2024W/EvGenFM/papers/Ji_T2VBench_Benchmarking_Temporal_Dynamics_for_Text-to-Video_Generation_CVPRW_2024_paper.pdf" class="paper-box-link" target="_blank">
    Page <i class="fas fa-external-link-alt"></i></a>
  </div>
</div>



<h1 id="-honors-and-awards">🎖 Honors and Awards</h1>
<ul>

  <li>
    <a class="red-label">06/2025</a> Outstanding Graduate of ShanghaiTech University
  </li>

  <li>
    <a class="red-label">12/2024</a> Triple Excellence Student 2023-2024 of ShanghaiTech Unversity <b>(TOP 2%)</b>
  </li>

  <li>
    <a class="red-label">10/2024</a> National Scholarship for the 2023-2024 Academic Year<b>(TOP 0.4% Student in China)</b>
  </li>

  <li>
    <a class="red-label">06/2024</a> ShanghaiTech International Exchange Program Scholarship <b>100,000 RMB (≈13,700 USD)</b>
  </li>

  <li>
    <a class="red-label">12/2023</a> Merit Student 2022-2023 of ShanghaiTech Unversity  <b>(Top 10%)</b>
  </li>

</ul>

# 📖 Educations

<div class='paper-box'><div class='paper-box-image'><div><img src='images/cmu.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="font-size:18px;">**Carnegie Mellon University**</span>

August 2025 - August 2027 (Expected)

  Major: Master of Science in Robotics

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/skd.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="font-size:18px;">**ShanghaiTech University**</span>

September 2021 - June 2025

  Major: B.E. in Computer Science

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/ucb.png' alt="sym" width="95%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="font-size:18px;">**University of California, Berkeley**</span>

August 2023 - May 2024

Major: Computer Science (Exchange student in EECS Department)

</div>
</div>

<!-- # 💻 Experience -->
<!-- - *2022.07 - 2022.08 *, Outstanding Member in <a href="https://www.innoxsz.com/">Shenzhen InnoX Academy</a>. 
- *2020.11 - 2023.09 *, Robocon Team in HUST.  -->

<h1 id="-hobbies">🎨 Hobbies</h1>
<p style="color: black; margin: 0%; font-weight: 350;">
  
I enjoy a variety of activities, including dancing💃, swimming🏊, playing the piano🎹, playing the flute🪈, and staying active through exercising🏋️.

In my spare time, I also love to travel🌍 and explore new places!

By the way, I’m also a fan of discovering different desserts🍰 and cozy cafes☕️!
  
</p>



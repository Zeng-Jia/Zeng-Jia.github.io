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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a researcher at [Shanghai AI Labotory](https://www.shlab.org.cn/). My research interests include **Embodied AI, Computer Vision, Robotic Manipulation and Autonomous Driving**. 

 I received my PhD degree from Robotics Institute, Shanghai Jiao Tong University, supervised by Prof. [Honghai Liu](https://scholar.google.com/citations?user=bsabUhgAAAAJ&hl=zh-CN), and obtained my bachelor's degree from Central South University. Over the preceding period, I have worked with Prof. [Hongyang Li](https://lihongyang.info) and Prof. [Yu Qiao](https://scholar.google.com/citations?user=gFtI-8QAAAAJ&hl=zh-CN) at Shanghai AI Labotory.

 I am an interdisciplinary lifelong learner, with an academic journey that has evolved from bio-mechatronics, computer vision, and autonomous driving to embodied AI. I am currently dedicated to advancing embodied AGI, with an emphasis on generalizable robotic manipulation.

# 📝 Selected Publications

## 🤖 Embodied AI <span style="font-size: small; float: right; color: gray;"> * indicates equal contribution </span> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/publications/clover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Closed-Loop Visuomotor Control with Generative Expectation for Robotic Manipulation**](https://arxiv.org/abs/2409.09016)

 Qingwen Bu$^\ast$, **Jia Zeng$^\ast$**, Chen Li$^\ast$, Yanchao Yang, Guyue Zhou, Junchi Yan, Ping Luo, Heming Cui, D.Hu, Yi Ma, Hongyang Li

- *We propose ​**CLOVER**, which employs a text-conditioned video diffusion model for generating visual plans as reference inputs, then  leverages these sub-goals to guide the feedback-driven policy to generate actions with an error measurement strategy.* 
- [NeurIPS 2024](https://arxiv.org/abs/2409.09016) \| [Code](https://github.com/OpenDriveLab/CLOVER) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2024</div><img src='images/publications/rss2024-mpi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Learning Manipulation by Predicting Interaction**](https://arxiv.org/abs/2406.00439)

**Jia Zeng$^\ast$**, Qingwen Bu$^\ast$, Bangjun Wang$^\ast$, Wenke Xia$^\ast$, Li Chen, Hao Dong, H.Song, D.Wang, D.Hu, P.Luo, H.Cui, B.Zhao, X.Li, Y.Qiao, Hongyang Li 

- *We propose a representation learning framework towards robotic manipulation that learns **Manipulation by Predicting Interaction (MPI)**.* <a href="https://github.com/OpenDriveLab/MPI">
- [RSS 2024](https://arxiv.org/abs/2406.00439) \| [Project Page](https://opendrivelab.com/MPI/) \| [Code](https://github.com/OpenDriveLab/MPI)

</div>
</div>
## 🚗 Autonomous Driving
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/publications/cvpr2023-focaldistiller.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Distilling Focal Knowledge From Imperfect Expert for 3D Object Detection**](https://openaccess.thecvf.com/content/CVPR2023/html/Zeng_Distilling_Focal_Knowledge_From_Imperfect_Expert_for_3D_Object_Detection_CVPR_2023_paper.html)

**Jia Zeng**, Li Chen, Hanming Deng, Lewei Lu, Junchi Yan, Yu Qiao, Hongyang Li

- We apply knowledge distillation to camera-only 3D object detection, investigate how to distill focal knowledge when confronted with
an imperfect 3D object detector teacher.
- [CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/html/Zeng_Distilling_Focal_Knowledge_From_Imperfect_Expert_for_3D_Object_Detection_CVPR_2023_paper.html)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/publications/gapretrain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Geometric-aware Pretraining for Vision-centric 3D Object Detection**](https://arxiv.org/abs/2304.03105)

Linyan Huang, Huijie Wang, **Jia Zeng**, et al.

- *We propose a geometric-aware pretraining method called **GAPretrain**, which distills geometric-rich information from LiDAR modality into camera-based 3D object detectors.*
- [arXiv](https://arxiv.org/abs/2304.03105)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE T-PAMI 2023</div><img src='images/publications/tpami2023-bev_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Delving Into the Devils of Bird’s-Eye-View Perception: A Review, Evaluation and Recipe**](https://ieeexplore.ieee.org/abstract/document/10321736)

Hongyang Li$^\ast$, Chonghao Sima$^\ast$, Jifeng Dai$^\ast$, Wenhai Wang$^\ast$, Lewei Lu$^\ast$, Huijie Wang$^\ast$, **Jia Zeng$^\ast$**, Zhiqi Li$^\ast$, et al.

- *we conduct a thorough review on Bird’s-Eye-View (BEV) perception in recent years and provide a practical recipe according to our analysis in BEV design pipeline.*
- [IEEE T-PAMI](https://ieeexplore.ieee.org/abstract/document/10321736) \| [Github](https://github.com/OpenDriveLab/Birds-eye-view-Perception)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCIENTIA SINICA Informationis</div><img src='images/publications/data-ecosystem.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Open-sourced data ecosystem in autonomous driving: the present and future**](https://arxiv.org/abs/2312.03408)

Hongyang Li$^\ast$, Yang Li$^\ast$, Huijie Wang$^\ast$, **Jia Zeng$^\ast$**, Huilin Xu, et al.

- *We undertakes an exhaustive analysis and discourse regarding the characteristics and data scales that future third-generation autonomous driving datasets should possess.*
- [SCIENTIA SINICA Informationis](https://www.sciengine.com/SSI/doi/10.1360/SSI-2023-0313) \| [arXiv](https://arxiv.org/abs/2312.03408)
</div>
</div>

## 💪🏻 Bio-Mechatronics & Human-Machine Interaction
- **Jia Zeng**, Yu Zhou, et al. [Fatigue-sensitivity comparison of sEMG and A-Mode ultrasound based hand gesture recognition](https://ieeexplore.ieee.org/abstract/document/9585400), IEEE Journal of Biomedical and Health Informatics (JBHI), 2021.
- **Jia Zeng**, Yu Zhou, et al. [Cross modality knowledge distillation between A-mode ultrasound and surface electromyography](https://ieeexplore.ieee.org/abstract/document/9845471), IEEE Transactions on Instrumentation and Measurement (TIM), 2022.
- **Jia Zeng**, Yixuan Sheng, et al. [Adaptive learning against muscle fatigue for A-mode ultrasound based gesture recognition](https://ieeexplore.ieee.org/abstract/document/10208224), IEEE Transactions on Instrumentation and Measurement (TIM), 2023.
- Yu Zhou, **Jia Zeng**, et al. [Voluntary and FES-induced finger movement estimation using muscle deformation features](https://ieeexplore.ieee.org/abstract/document/8733202), IEEE Transactions on Industrial Electronics (TIE), 2019.

# 🧑‍💻 Career Experience
<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://www.shlab.org.cn/"><img src='images/institutions/shailab.png' alt="sym" width="150px" style="padding: 5px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## Shanghai AI Labotory, Researcher

*2023.09 - (present)*.
- **Embodied foundation model and generalizable robotic manipulation.**

</div>
</div>

<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://www.shlab.org.cn/"><img src='images/institutions/shailab.png' alt="sym" width="150px" style="padding: 5px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## Shanghai AI Labotory, Research intern

*2022.04 - 2023.06*, Supervisor: Prof. [Hongyang Li](https://lihongyang.info).
- **Birds-Eye-View perception and Knowledge distillation for 3D object detection.**

</div>
</div>

# 🎓 Education
<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://en.sjtu.edu.cn/"><img src='images/institutions/sjtu-logo.png' alt="sym" width="120px" style="padding: 5px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## Robotics Institute, Shanghai Jiao Tong University

*2017.09 - 2023.8*, Supervisor: Prof. [Honghai Liu](https://scholar.google.com/citations?user=bsabUhgAAAAJ&hl=zh-CN).
- **Bio-signal based human motion recognition and human-machine interaction.**

</div>
</div>

<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://en.csu.edu.cn/"><img src='images/institutions/csu-logo.png' alt="sym" width="120px" style="padding: 5px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## Central South University

*2013.09 - 2017.06*.
- **Mechatronics engineering**
- **Image processing**

</div>
</div>


# 💼 Service
- Reviewer for `CVPR 2024`, `ECCV 2024`, `NeurIPS 2024`, etc.
- Member of CAAI-Embodied AI Committee.

  

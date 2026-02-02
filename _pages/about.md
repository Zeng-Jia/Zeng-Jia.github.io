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

I am currently a research scientist at [Shanghai AI Laboratory](https://www.shlab.org.cn/). My research interests include **Embodied AI, Robotic Manipulation and Vision-Language-Action (VLA) model**.  

 I received my PhD degree from Robotics Institute, Shanghai Jiao Tong University, supervised by Prof. [Honghai Liu](https://scholar.google.com/citations?user=bsabUhgAAAAJ&hl=zh-CN), and obtained my bachelor's degree from Central South University. I am currently working with [Jiangmiao Pang](https://oceanpang.github.io/) on Embodied AI. Over the preceding period, I have worked with Prof. [Hongyang Li](https://lihongyang.info) and Prof. [Yu Qiao](https://scholar.google.com/citations?user=gFtI-8QAAAAJ&hl=zh-CN).


# 📝 Selected Publications

## 🤖 Embodied AI <span style="font-size: small; float: right; color: gray;"> * indicates equal contribution, ✉️ indicates corresponding author </span> 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/publications/InternVLA-A1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**InternVLA-A1: Unifying Understanding, Generation, and Action for Robotic Manipulation**](https://arxiv.org/pdf/2601.02456)

InternVLA-A1 Team (**Jia Zeng**: project lead & core contributor)

- *We present **InternVLA-A1**, which unifies scene <u>understanding</u>, visual foresight <u>generation</u>, and <u>action</u> execution into a single framework.*

- 🔮 *The Core: Synergizes MLLM's semantic understanding with world-model-style dynamic prediction, to "imagine" the future and guide adaptive actions.*
- 🚀 *The Fuel: Enables joint training on heterogeneous data sources over real-world robot data, synthetic simulation data, and egocentric human videos.*
- ⚡ The Output: A VLA model that tackles highly dynamic scenarios with effortless mastery.
- [arXiv](https://arxiv.org/pdf/2601.02456) \| [Code](https://github.com/InternRobotics/InternVLA-A1)  \| [Model](https://huggingface.co/InternRobotics/InternVLA-A1-3B)    \| [Project Page](https://internrobotics.github.io/internvla-a1.github.io/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/publications/InternData-A1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**InternData-A1: Pioneering High-Fidelity Synthetic Data
for Pre-training Generalist Policy**](https://arxiv.org/abs/2511.16651)

Yang Tian$^\ast$, Yuyin Yang$^\ast$, Yiman Xie$^\ast$, Zetao Cai$^\ast$, Xu Shi$^\ast$, Ning Gao, Hangxu Liu, Xuekun Jiang, Zherui Qiu, Feng Yuan, Yaping Li, Ping Wang, Junhao Cai, 

**Jia Zeng**✉️, Hao Dong✉️, Jiangmiao Pang✉️

- *We propose a high-fidelity synthetic data **InternData-A1**, which contains over **630k trajectories** and **7,433 hours**
.*

- *This work provides the first evidence that synthetic data alone can match the performance of the strongest 𝜋-dataset in pre-training a VLA model, revealing the substantial
value of large-scale simulation.*
- [arXiv](https://arxiv.org/abs/2511.16651) \| [Dataset](https://huggingface.co/datasets/InternRobotics/InternData-A1)  \|  [Project Page](https://internrobotics.github.io/interndata-a1.github.io/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/publications/F1-VLA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**F1: A vision-language-action model bridging understanding and generation to actions**](https://arxiv.org/abs/2509.06951)

Qi Lv$^\ast$, Weijie Kong$^\ast$, Hao Li$^\ast$, **Jia Zeng**✉️, Zherui Qiu, et al.

- *We introduce F1, a novel paradigm by integrating visual foresight generation into the decision-making pipeline. Our model employs a Mixture-of-Transformer architecture with dedicated modules for perception, foresight generation, and control, thereby bridging **understanding**, **generation**, and **actions** through predictive inverse dynamics modeling.*

- [arXiv](https://arxiv.org/abs/2509.06951) \| [Code](https://github.com/InternRobotics/F1-VLA)  \|  [Model](https://huggingface.co/InternRobotics/F1-VLA)

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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/publications/clover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Closed-Loop Visuomotor Control with Generative Expectation for Robotic Manipulation**](https://arxiv.org/abs/2409.09016)

 Qingwen Bu$^\ast$, **Jia Zeng$^\ast$**, Chen Li$^\ast$, Yanchao Yang, Guyue Zhou, Junchi Yan, Ping Luo, Heming Cui, D.Hu, Yi Ma, Hongyang Li

- *We propose ​**CLOVER**, which employs a text-conditioned video diffusion model for generating visual plans as reference inputs, then  leverages these sub-goals to guide the feedback-driven policy to generate actions with an error measurement strategy.* 
- [NeurIPS 2024](https://arxiv.org/abs/2409.09016) \| [Code](https://github.com/OpenDriveLab/CLOVER) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/publications/iclr2025-seer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](https://arxiv.org/abs/2412.15109)

 Yang Tian$^\ast$, Sizhe Yang$^\ast$, **Jia Zeng**, Ping Wang, Dahua Lin, Hao Dong, Jiangmiao Pang

- *We propose an end-to-end model, **Seer**, which employs an inverse dynamics model based on the robot’s predicted visual states to forecast actions. We term such architectural framework the **Predictive Inverse Dynamics Model (PIDM)**.*

- [ICLR 2025](https://arxiv.org/abs/2412.15109) \| [Project Page](https://nimolty.github.io/Seer/) \| [Code](https://github.com/OpenRobotLab/Seer) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/publications/RSS2025-Homie.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit**](https://arxiv.org/abs/2502.13013)

 Qingwei Ben$^\ast$, Feiyu Jia$^\ast$, **Jia Zeng**, Junting Dong, Dahua Lin, Jiangmiao Pang

- *we propose **HOMIE**, a novel humanoid teleoperation cockpit integrates a humanoid loco-manipulation policy and a low-cost exoskeleton-based hardware system.*

- [RSS 2025](https://arxiv.org/abs/2502.13013) \| [Project Page](https://homietele.github.io/) \| [Code](https://github.com/OpenRobotLab/OpenHomie) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/publications/RSS2025-RoboSplat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation**](https://arxiv.org/abs/2504.13175)

 Sizhe Yang$^\ast$, Wenye Yu$^\ast$, **Jia Zeng**, Jun Lv, Kerui Ren, Cewu Lu, Dahua Lin, Jiangmiao Pang

- ***RoboSplat** is framework that leverages 3D Gaussian Splatting (3DGS) to generate novel demonstrations for RGB-based policy learning. RoboSplat can generate diverse and visually realistic data across six types of generalization (object poses, object types, camera views, scene appearance, lighting conditions, and embodiments).*

- [RSS 2025](https://arxiv.org/abs/2504.13175) \| [Project Page](https://yangsizhe.github.io/robosplat/) \| [Code](https://github.com/OpenRobotLab/robosplat) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/publications/RSS2025-PPI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Gripper Keypose and Object Pointflow as Interfaces for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2504.17784)

Yuyin Yang$^\ast$, Zetao Cai$^\ast$, Yang Tian, **Jia Zeng**, Jiangmiao Pang

- ***PPI** integrates the prediction of target gripper poses and object pointflow with the continuous actions estimation, providing enhanced spatial localization and satisfying flexibility in handling movement restrictions.*

- [RSS 2025](https://arxiv.org/abs/2504.17784) \| [Project Page](https://yuyinyang3y.github.io/PPI/) \| [Code](https://github.com/OpenRobotLab/PPI) 
</div>
</div>


## 🚗 Autonomous Driving
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/publications/cvpr2023-focaldistiller.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Distilling Focal Knowledge From Imperfect Expert for 3D Object Detection**](https://openaccess.thecvf.com/content/CVPR2023/html/Zeng_Distilling_Focal_Knowledge_From_Imperfect_Expert_for_3D_Object_Detection_CVPR_2023_paper.html)

**Jia Zeng**, Li Chen, Hanming Deng, Lewei Lu, Junchi Yan, Yu Qiao, Hongyang Li

- *We apply knowledge distillation to camera-only 3D object detection, investigate how to distill focal knowledge when confronted with an imperfect 3D object detector teacher.*
- [CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/html/Zeng_Distilling_Focal_Knowledge_From_Imperfect_Expert_for_3D_Object_Detection_CVPR_2023_paper.html)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE T-PAMI 2023</div><img src='images/publications/tpami2023-bev_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Delving Into the Devils of Bird’s-Eye-View Perception: A Review, Evaluation and Recipe**](https://ieeexplore.ieee.org/abstract/document/10321736)

**Jia Zeng**: Co-first author

- *we conduct a thorough review on Bird’s-Eye-View (BEV) perception in recent years and provide a practical recipe according to our analysis in BEV design pipeline.*
- [IEEE T-PAMI](https://ieeexplore.ieee.org/abstract/document/10321736) \| [Github](https://github.com/OpenDriveLab/Birds-eye-view-Perception)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCIENTIA SINICA Informationis</div><img src='images/publications/data-ecosystem.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Open-sourced data ecosystem in autonomous driving: the present and future**](https://arxiv.org/abs/2312.03408)

**Jia Zeng**: Co-first author

- *We undertakes an exhaustive analysis and discourse regarding the characteristics and data scales that future third-generation autonomous driving datasets should possess.*
- [SCIENTIA SINICA Informationis](https://www.sciengine.com/SSI/doi/10.1360/SSI-2023-0313) \| [arXiv](https://arxiv.org/abs/2312.03408)
</div>
</div>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV</div><img src='images/publications/gapretrain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Noto Serif, Georgia, serif; font-size: 14px;">
[**Geometric-aware Pretraining for Vision-centric 3D Object Detection**](https://arxiv.org/abs/2304.03105)

Linyan Huang, Huijie Wang, **Jia Zeng**, et al.

- *We propose a geometric-aware pretraining method called **GAPretrain**, which distills geometric-rich information from LiDAR modality into camera-based 3D object detectors.*
- [arXiv](https://arxiv.org/abs/2304.03105)
</div>
</div>

# 🧑‍💻 Career Experience
<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://www.shlab.org.cn/"><img src='images/institutions/shailab.png' alt="sym" width="150px" style="padding: 5px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## Shanghai AI Labotory, Research scientist

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
- Reviewer for `CVPR`, `ECCV`, `NeurIPS`, `ICLR`, `ICML`, etc.
- Member of CAAI-Embodied AI Committee.



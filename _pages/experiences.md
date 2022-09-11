---
layout: archive
title: "Research Experiences"
permalink: /experiences/
author_profile: true
redirect_from:
  - /experiences
---

<!-- {% include base_path %} -->


My research experiences are listed as follows.
## 1. Out-of-Dynamics (OOD) Imitation Learning from Multimodal Demonstrations | March 2022 - now
> Advisor: Mingsheng Long, Tsinghua University

* Studied out-of-dynamics imitation learning (OOD-IL): the assumption in Imitation Learning(IL) is that the demonstrator who collects demonstrations share the same dynamics as the imitator limits the usage of IL. Aimed at enabling a wider usage of a mixture of mutimodal demonstrations in IL.

* Developed a novel sequence-based contrastive clustering algorithm to tackle the multimodal distribution problem in demonstrations collected under multiple sources and mitigated their negative mutual influence.


* Developed an adversarial-based transferability measurement to down-weight non-transferable demonstrations for OOD-IL which enables agents to learn from a mixture of source data under different dynamics.

* Conducted experiments on 3 MuJoCo environments, a driving and a simulated robot environment, showing that the proposed approach outperforms prior works on final IL performance by 100 ~ 300%.

## 2. Dynamics-Aware Offline-and-Online        Reinforcement Learning  |   Feb 2022 - April 2022
> Advisor: Xianyuan Zhan, Institute for AI Industry Research, Tsinghua University


* Combined learning from limited real data in offline RL and unrestricted exploration of imperfect simulators in online RL, which is a novel scenario.
  
* Proposed the Dynamics-Aware Hybrid Offline-and-Online Reinforcement Learning(H2O) framework, theoretically proved it can allow learning with high-fidelity from both offline-dataset and online-exploration. 

* Designed a practical implementation with PyTorch through an adversarial training process, adaptively penalizing the learning on simulated state-action pairs with large dynamics gaps.

* Conducted experiments in 4 datasets of MuJoCo each with 3 unreal dynamics (Gravity / Friction / Joint-Noise) and a real wheel-legged robot, and achieved results beat all existing baselines.

## 3. Universal Domain Adaptation with Meta-learning | Aug 2021-Dec 2022
> Advisor: Mingsheng Long, Tsinghua University

* Aimed to eliminate the label category gap on sources and target domains in Domain Adaptation (DA) tasks, called Universal DA by identifying outlier samples without the need for prior knowledge.

* Conducted experiments with PyTorch and achieved improving performance on Office31, OfficeHome settings. (1~2% in accuracy, 8% in h-score) by utilizing a meta-learning method.

* Demonstrated that identifying outlier samples through distributional distance measurement is beneficial. Detecting outlier is not enough, intended to consider harder circumstances like long-tail distribution in real-world settings.

## 4. Modular Networks for Domain Generalization |    Nov 2021-Jan 2022
> Advisor: Mingsheng Long, Tsinghua University


* Considered enabling the model to have the ability to solve problems for any target domain (while DA algorithm aims to solve domain gap for a specific single target) with the access to an abundance of source domains, called Domain Generalization (DG)

* Designed a novel mixture-of-experts modular structure with attention mechanism for models to merge domain-generic and domain-specific information selectively produce knowledge in a more flexible way.

* Conducted experiments on OfficeHome and WILDS datasets for image classification task in unseen domain(DG tasks) showing that the modularized design significantly boosts the performance by 1%, while there are currently no DG approaches proved to be effective on the WILDS dataset.
## What's more... Other interesting things I did in course projects.:)

### 5. Scenic spot guide based on Unitree Robotics A1 |   July 2021
> Special Operations Team, Tsinghua University


* Developed 4 functions with ROS system including: automatic navigation, human tracking, voice interaction and emergency management. 
  
* Integrated the system into a voice-conduct comprehensive product which could serve the purpose of a scenic spot guide.

### 6. Thunder-Classroom Application Development |          April 2020-June 2020

> Advisor: Jingtao Fan, Associate Professor, Laboratory of Brain and Cognitive Sciences, Department of Automation

* Built an online-meeting application aimed to serve as an online-classroom which resembles RainClassroom.

* Realized functions with GUI interface include: screen sharing, voice sharing, question attributing, etc. by C++ programming. Successfully used its release version to finish the project oral defense.

### 7. Video Desnowing with Speed and Effectiveness | High-tech Winter Olympics , July 2021-Aug 2021
> Advisor: Jianming Hu, Associate Professor, Institute of systems engineering, Department of Automation

* Focused on problems encountered when applying current vehicle recognition algorithms to real-life circumstances due to bad weather. Researched on traditional (dark channel; etc.) as well as deep learning methods (DesnowNet; etc.), which cannot promise speed and effectiveness at the same time.
* Proposed method based on Cycle GAN to promise better robustness on unseen circumstances and least-complexity for real-world implementation in Olympics Park.

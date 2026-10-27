---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

Please refer to the [.pdf](<../files/Resume - Zhenglang Weng.pdf>) version for more details.

{% include base_path %}

Education
======
- Jul. 2026 \~ Present: **Research Assistant**, [**Shanghai Jiao Tong University (SJTU)**](https://en.sjtu.edu.cn/)
  - **Advisor**: [Prof. Yao Mu](https://yaomarkmu.github.io/), [ScaleLab](https://scalelab-sjtu.github.io/)
- Jul. 2025 \~ Aug. 2025: [**Student Summer Research Fellowship Program**](https://cs.uchicago.edu/academics/undergraduate/summer-research/student-summer-research-fellowship-program/), [**The University of Chicago**](https://www.uchicago.edu/)
  - **Advisor**: [Prof. Ken Nakagaki](https://www.ken-nakagaki.com/), [AxLab](https://www.axlab.cs.uchicago.edu/)
- Sep. 2022 \~ Jun. 2026:  [**School of the Gifted Young**](https://en.scgy.ustc.edu.cn/main.htm), [**University of Science and Technology of China (USTC)**](https://en.ustc.edu.cn/)
  - **Major**: Electronic Information Engineering
  - **Overall GPA:** {{site.global.gpa}}  **Ranking:** {{site.global.ranking}}
  - **Standardized Test**: **TOEFL: 6.0** (Reading: 6.0, Listening: 6.0, Speaking: 5.5, Writing: 5.5)
- Aug. 2020 \~ Aug. 2022: [**The Affiliated High School of South China Normal University**](https://www.hsfz.net.cn/homepage/index.jsp)

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->


Publications
======

### [SP-HLM: Sparse-Pose-Driven Motion Generation and Whole-Body Control for Humanoid Loco-Manipulation](https://sp-hlm.github.io/)

Zhaohui Yang\*, Quanbao Lin, Chengqi Shi, **Zhenglang Weng**, Jicheng Lin, Boyu Chen, Tengjie Zhu, Guanzhu Ren, Jiahao Xu, Yang Feng, Xiaokang Yang, Yao Mu

Submitted to *ICRA 2027*

- Optimized the end-to-end humanoid loco-manipulation pipeline with TensorRT, accelerating VLA inference to **25 Hz** and whole-body motion generation to **10 Hz** for real-time execution.
- Adapted and debugged the **HumanoidArena** benchmark for SP-HLM, migrated simulation environments, and trained task-specific policies for humanoid loco-manipulation evaluation.
- Collaborated on **Unitree G1 real-world deployment**, including robot data collection, system integration, and physical loco-manipulation experiments.

[Project Website](https://sp-hlm.github.io/)

<!--
### Embodied Origami Robots: Bridging Physical and Computational Intelligence for Adaptive Manipulation and Locomotion
Advisor: Dr. Jianshu Zhou   
Submitted to *Advanced Science*, Sep. 2025

- Analyzed the mechanics of a multi-link structure through theoretical modeling.
- Modeled the potential energy of a bistable origami structure and visualized its energy landscape.
-->

### TorquePods: Multi-Module Coordinated Flywheel-based Haptic Toolkit for Advanced Haptic Design  
Advisor: Prof. Ken Nakagaki  
In Preparation, Aug. 2025
- Elaborated a compact, custom PCB for a novel modular haptic interface system based on flywheel actuation
- Implemented Bluetooth communication protocol for low-latency control of the module
- Derived theoretical force-torque transformation formulas and implemented real-time measurement for technical evaluation using a 6-DOF Force/Torque sensor.

### Mass.mov: Towards Movement-based Interactive Material using ‘Mass with Constraints’
Advisor: Prof. Ken Nakagaki  
In Preparation, Aug. 2025
- set up a closed-loop control motor system with FOC (Field Oriented Control) for the projects technical evaluation
- fine-tuned a PID algorithm that allowed for precise control and testing of the motion-based mechanism. 

Project Experience
======

### Robotic Manipulation via Video Generation and 6D Pose Tracking
Undergraduate Graduation Thesis | Advisor: Prof. Jiahu Qin — USTC <br />
Oct. 2025 – May 2026

- Enabled zero-shot manipulation of objects through a video-to-action pipeline by extracting 6D trajectories of target objects from generated videos.
- Integrated Kling-v3.0 video generation, Grounded-SAM instance segmentation, and RGBTrack 6D pose tracking to extract object motion trajectories from generated manipulation videos.
- Deployed the full pipeline on a 7-DoF OpenArm robotic arm and evaluated it on various manipulation tasks.

### Wordle Game Solver Utilizing Information Theory [.pdf](<../files/Information Theory and the Wordle Game.pdf>)
Advisor: Prof. Chen Gong  
Course Project for Information Theory, Jun. 2025
- Formed rigorous mathematical formulations of the rules and game-solving algorith.
- Designed a Wordle game solver based on information entropy.
- Formulated a funtional explanation for the Kullback-Leibler Divergence (KL Divergence).  

### A Software Defined Radio System for 5G PUSCH
Advisor: Prof. Wuyang Zhou, Prof. Puhua Zhang  
Course Project for Principles of Communications, Dec. 2024
- Accomplished modules using MATLAB, including QAM, Scrambling/Descrambling, OFDM, CRC, Channel Estimation.
- Constructed a simulated channel using MATLAB and a real channel using an RF antenna.
- Validated the code operation through various channels, focusing on Error Correction, Channel Estimation, and Equalization.

### Simplified 8-bit CPU Based on FPGA
Advisor: Prof. Xiaowen Liang  
Course Project for Electronic System Design, Nov. 2024
-  Designed an 8-bit Instruction Set of basic operations, including move, jump, basic computation, condition, immediate number.
- Implemented the self-designed Instruction Set using Verilog HDL, and verified the basic function of the CPU using peripheral interfaces on an experiment circuit board.


### Automatic Routing Gluttonous Snake Program Based on BFS Algorithm
Advisor: Dr. Linlin Qin
Course Project for Computer Programming A, Nov. 2022
- Designed and implemented a program of the classical game Gluttonous Snake.
- Established a program that can automatically lead the snake to eat most of the apples without dying, using the basic algorithm of Breadth First Search (BFS).


Honors and Awards
======
- Nov. 2024 **Outstanding Undergraduate Scholarship**-Gold Prize (Top 3%), USTC 
- Nov. 2023 **Scholarship Issued by JAC&NIO Enterprise** (Top 2%, 5000 CNY), USTC 
- Dec. 2023 [**CUMCM**](https://en.mcm.edu.cn/) (Contemporary Undergraduate Mathematical Contest in Modeling)  (1st in Anhui Province, Second Prize National), China
- Nov. 2023 **Robogame Robot Championship** (Second Prize), USTC 


Skills
======

- **Programming Language**: C, C++, MATLAB, Mathematica, Python, Verilog HDL
- **Software**: Sketchpad, GeoGebra, SolidWorks, Fusion360,  ArduinoIDE, PlatformIO, Markdown, LaTeX
- **Hardware**: Heat gun, Soldering station, 3D Printer, PPG, EDFA, Optical Attenuator, Optical Fibre

Leadership and Extracurricular Activities
======
- Class Representative for Academics
- Member of the USTC Ballroom Dance Association
- Volunteer of the USTC Science and Technology Opening Week (2023&2024)


<!-- Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->

---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## ICRA 2024 Robotic Grasping and Manipulation Competition - In-Hand Manipulation Track

* 03/2024 - 05/2024
* 1st Place of In-Hand Manipulation Track & The Most Elegant Solution Award Among All Tracks

<p align="center">
<iframe width="360" height="640" src="../files/24_ICRA_RGMC.mp4" title="24_ICRA_RGMC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

The [Robotic Grasping and Manipulation Competition - In-Hand Manipulation Track](https://cse.usf.edu/~yusun/rgmc/2024.html) is focused on reconfiguring objects in robot dexterous hands. The competition tasks focus on two essential skills: in-hand precise manipulation and in-hand object re-orientation. Our solution involving an open-sourced Leap Hand, trajectory optimization, and reinforcement learning won the 1st place of the in-hand manipulation competition, and also won the Most Elegant Solution Award among all tracks in the RGMC.

## Model Predictive Control of Long-horizon In-hand Manipulation

* 10/2023 - Now
* Intelligent Robotic Manipulation Lab, Tsinghua University / Mechanical Systems Control Lab, UC Berkeley
* Advisor: Prof. Xiang Li / Prof. Masayoshi Tomizuka

<p align="center">
<iframe width="640" height="360" src="../files/24_IROS_InHand.mp4" title="24_inhand_manipulation_iros" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

Inspired by recent advancements in contact-rich locomotion and manipulation, this paper proposes a novel model-based approach to control dexterous in-hand manipulation and overcome the current limitations. The proposed approach has the attractive feature, which allows the robot to robustly execute long-horizon in-hand manipulation without pre-defined contact sequences or separated planning procedures. Specifically, we design a contact-implicit model predictive controller at high-level to generate real-time contact plans, which are executed by the low-level tracking controller. Compared with other model-based methods, such a long-horizon feature enables replanning and robust execution of contact-rich motions to achieve large-displacement in-hand tasks more efficiently; Compared with existing learning-based methods, the proposed approach achieves the dexterity and also generalizes to different objects without any pre-training. Detailed simulations and ablation studies demonstrate the efficiency and effectiveness of our method. It runs at 20Hz on the 23-degree-of-freedom long-horizon in-hand object rotation task.


[[Website](https://director-of-g.github.io/in_hand_manipulation/)]

## Robotic Pushing Manipulation in the Cluttered Environments

* 10/2022 - Now
* Intelligent Robotic Manipulation Lab, Tsinghua University
* Advisor: Prof. Xiang Li

<p align="center">
<iframe width="640" height="360" src="../files/23_IROS_Pushing.mp4" title="23_planar_pushing_IROS" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>

This paper proposes a new non-prehensile manipulation method for the task of object retrieval in cluttered environments, using a rod-like pusher. Specifically, a candidate trajectory in a cluttered environment is first generated with an improved Rapidly-Exploring Random Tree (RRT) planner; Then, a Model Predictive Control (MPC) scheme is applied to stabilize the slider's poses through necessary contact with obstacles. Different from existing methods, the proposed approach is with the contact-aware feature, which enables the synthesized effect of active removal of obstacles, avoidance behavior, and switching contact face for improved dexterity. Hence both the feasibility and efficiency of the task are greatly promoted. The performance of the proposed method is validated in a planar object retrieval task, where the target object, surrounded by many fixed or movable obstacles, is manipulated and isolated. Both simulation and experimental results are presented.


[[Website](https://director-of-g.github.io/push_in_clutter/)]

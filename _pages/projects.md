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

## Model Predictive Control of Long-horizon In-hand Manipulation

* 10/2023 - Now
* Intelligent Robotic Manipulation Lab, Tsinghua University / Mechanical Systems Control Lab, UC Berkeley
* Advisor: Prof. Xiang Li / Prof. Masayoshi Tomizuka

<!-- <p align="center">
<iframe width="640" height="360" src="../files/23_DLO_planning_journal.mp4" title="23_DLO_planning_journal" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p> -->

Inspired by recent advancements in contact-rich locomotion and manipulation, this paper proposes a novel model-based approach to control dexterous in-hand manipulation and overcome the current limitations. The proposed approach has the attractive feature, which allows the robot to robustly execute long-horizon in-hand manipulation without pre-defined contact sequences or separated planning procedures. Specifically, we design a contact-implicit model predictive controller at high-level to generate real-time contact plans, which are executed by the low-level tracking controller. Compared with other model-based methods, such a long-horizon feature enables replanning and robust execution of contact-rich motions to achieve large-displacement in-hand tasks more efficiently; Compared with existing learning-based methods, the proposed approach achieves the dexterity and also generalizes to different objects without any pre-training. Detailed simulations and ablation studies demonstrate the efficiency and effectiveness of our method. It runs at 20Hz on the 23-degree-of-freedom long-horizon in-hand object rotation task.


[[Website](https://jump-thu.github.io/in_hand_manipulation/)]

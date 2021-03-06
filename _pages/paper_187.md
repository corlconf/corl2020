---
layout: page
title: "Learning a Contact-Adaptive Controller for Robust, Efficient Legged Locomotion"
subtitle: 
description:
permalink: /paper_187/
grand_parent: All Papers
parent: Monday
supp: 
code: 
youtube_id: ze7pAEHiwB4
pdf: https://drive.google.com/file/d/185kNH9zATbt95j3mTCuM-2rcy30TWbFq/view
---

# Learning a Contact-Adaptive Controller for Robust, Efficient Legged Locomotion

<a href="https://drive.google.com/file/d/185kNH9zATbt95j3mTCuM-2rcy30TWbFq/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Xingye Da (Nvidia)*; Zhaoming Xie (University of British Columbia); David Hoeller (Nvidia); Byron Boots (Nvidia); Anima Anandkumar (); Yuke Zhu (University of Texas - Austin); Buck Babich (NVIDIA); Animesh Garg (University of Toronto, Vector Institute, Nvidia)**

#### Interactive Session
<em>2020-11-16, 11:50 - 12:20 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESNOLUJIPYQLQN5A" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
We present a hierarchical framework that combines model-based control and reinforcement learning (RL) to synthesize robust controllers for a quadruped (the Unitree Laikago). The system consists of a high-level controller that learns to choose from a set of primitives in response to changes in the environment and a low-level controller that utilizes an established control method to robustly execute the primitives. Our framework learns a controller that can adapt to challenging environmental changes on the fly, including novel scenarios not seen during training. The learned controller is up to 85~percent more energy efficient and is more robust compared to baseline methods. We also deploy the controller on a physical robot without any randomization or adaptation scheme.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/11vRBA0_4LzqhTTsF-v6aFY2PJW9CeiaL/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


---
layout: page
title: "ROLL: Visual Self-Supervised Reinforcement Learning with Object Reasoning"
subtitle: 
description:
permalink: /paper_215/
grand_parent: All Papers
parent: Monday
supp: 
code: https://github.com/yufeiwang63/ROLL
youtube_id: OQ8R5C2qWco
pdf: https://drive.google.com/file/d/1Q-0xpq3QU6UlvBFPAEHMkz9ap3xDeiMi/view
---

# ROLL: Visual Self-Supervised Reinforcement Learning with Object Reasoning

<a href="https://drive.google.com/file/d/1Q-0xpq3QU6UlvBFPAEHMkz9ap3xDeiMi/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/yufeiwang63/ROLL" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Yufei Wang (Carnegie Mellon University)*; Narasimhan Gautham (Carnegie Mellon University); Xingyu Lin (Carnegie Mellon University); Brian Okorn (ROB); David Held (CMU)**

#### Interactive Session
<em>2020-11-16, 11:50 - 12:20 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESUFOXHM5Q65KB3J" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Current image-based reinforcement learning (RL) algorithms typically operate on the whole image without performing object-level reasoning.  This leads to inefficient goal sampling and ineffective reward functions. In this paper, we improve upon previous visual self-supervised RL by incorporating object-level reasoning and occlusion reasoning. Specifically, we use unknown object segmentation to ignore distractors in the scene for better reward computation and goal generation; we further enable occlusion reasoning by employing a novel auxiliary loss and training scheme. We demonstrate that our proposed algorithm, ROLL (Reinforcement learning with Object Level Learning), learns dramatically faster and achieves better final performance compared with previous methods in several simulated visual control tasks. Project video and code
are available at <a href="https://sites.google.com/andrew.cmu.edu/roll" target="_blank">https://sites.google.com/andrew.cmu.edu/roll</a>.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/12k48lou9x2YqTVExuICiaF7WO8uJh-co/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


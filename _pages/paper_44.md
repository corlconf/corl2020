---
layout: page
title: "Accelerating Reinforcement Learning with Learned Skill Priors"
subtitle: 
description:
permalink: /paper_44/
grand_parent: All Papers
parent: Wednesday
supp: 
code: https://github.com/clvrai/spirl
youtube_id: 6FSC2yeJ98U
pdf: https://drive.google.com/file/d/1svZaKvUrdVpBZN6XWWJC1bGUCX7pbQvw/view
---

# Accelerating Reinforcement Learning with Learned Skill Priors

<a href="https://drive.google.com/file/d/1svZaKvUrdVpBZN6XWWJC1bGUCX7pbQvw/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/clvrai/spirl" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Karl Pertsch (University of Southern California)*; Youngwoon Lee (University of Southern California); Joseph Lim (USC)**

#### Interactive Session
<em>2020-11-18, 12:30 - 13:00 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESGG0BZ13BTNWYZK" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Intelligent agents rely heavily on prior experience when learning a new task, yet most modern reinforcement learning (RL) approaches learn every task from scratch. One approach for leveraging prior knowledge is to transfer skills learned on prior tasks to the new task. However, as the amount of prior experience increases, the number of transferable skills grows too, making it challenging to explore the full set of available skills during downstream learning. Yet, intuitively, not all skills should be explored with equal probability; for example information about the current state can hint which skills are promising to explore. In this work, we propose to implement this intuition by learning a prior over skills. We propose a deep latent variable model that jointly learns an embedding space of skills and the skill prior from offline agent experience. We then extend common maximum-entropy RL approaches to use skill priors to guide downstream learning. We validate our approach, SPiRL (Skill-Prior RL), on complex navigation and robotic manipulation tasks and show that learned skill priors are essential for effective skill transfer from rich datasets. Videos and code are available at <a href="https://clvrai.com/spirl" target="_blank">https://clvrai.com/spirl</a>.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1RQGoHk4RDfG9uteogM6tL-vZ5T02mKgh/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


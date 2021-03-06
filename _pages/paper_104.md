---
layout: page
title: "PixL2R: Guiding Reinforcement Learning Using Natural Language by Mapping Pixels to Rewards"
subtitle: 
description:
permalink: /paper_104/
grand_parent: All Papers
parent: Tuesday
supp: 
code: https://github.com/prasoongoyal/PixL2R
youtube_id: nCridU7Kh0k
pdf: https://drive.google.com/file/d/1deMLP1C-NprbfZbtgbUuIAK60OBkInNm/view
---

# PixL2R: Guiding Reinforcement Learning Using Natural Language by Mapping Pixels to Rewards

<a href="https://drive.google.com/file/d/1deMLP1C-NprbfZbtgbUuIAK60OBkInNm/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/prasoongoyal/PixL2R" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Prasoon Goyal (The University of Texas at Austin)*; Scott Niekum (UT Austin); Raymond Mooney (Univ. of Texas at Austin)**

#### Interactive Session
<em>2020-11-17, 12:30 - 13:00 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESFDPOCAT25F9XKZ" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Reinforcement learning (RL), particularly in sparse reward settings, often requires prohibitively large numbers of interactions with the environment, thereby limiting its applicability to complex problems. To address this, several prior approaches have used natural language to guide the agent's exploration. However, these approaches typically operate on structured representations of the environment, and/or assume some structure in the natural language commands. In this work, we propose a model that directly maps pixels to rewards, given a free-form natural language description of the task, which can then be used for policy learning. Our experiments on the Meta-World robot manipulation domain show that  language-based rewards significantly improves the sample efficiency of policy learning, both in sparse and dense reward settings. 


#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1gnuFjB0uYc_46C2YlznByF0ez22Tci_y/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


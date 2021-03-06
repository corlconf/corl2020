---
layout: page
title: "CLOUD: Contrastive Learning of Unsupervised Dynamics"
subtitle: 
description:
permalink: /paper_74/
grand_parent: All Papers
parent: Wednesday
supp: 
code: https://jianrenw.github.io/cloud/
youtube_id: YHErdZ_szCM
pdf: https://drive.google.com/file/d/1d8Itdp0UANwUjbHSc5MiMhkDx9nKSBc7/view
---

# CLOUD: Contrastive Learning of Unsupervised Dynamics

<a href="https://drive.google.com/file/d/1d8Itdp0UANwUjbHSc5MiMhkDx9nKSBc7/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://jianrenw.github.io/cloud/" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Jianren Wang (Carnegie Mellon University)*; Yujie Lu (Tencent); Hang Zhao (Waymo)**

#### Interactive Session
<em>2020-11-18, 11:50 - 12:20 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESYH73AQ20NO3LDT" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Developing agents that can perform complex control tasks from high dimensional observations such as pixels is challenging due to difficulties in learning dynamics efficiently. In this work, we propose to learn forward and inverse dynamics in a fully unsupervised manner via contrastive estimation. Specifically, we train a forward dynamics model and an inverse dynamics model in the feature space of states and actions with data collected from random exploration. Unlike most existing deterministic models, our energy-based model takes into account the stochastic nature of agent-environment interactions. We demonstrate the efficacy of our approach across a variety of tasks including goal-directed planning and imitation from observations.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/150_R6VRqgThunI2-g-JAE78oCaF_XE5b/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


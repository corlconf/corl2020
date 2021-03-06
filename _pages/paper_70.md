---
layout: page
title: "Learning Obstacle Representations for Neural Motion Planning"
subtitle: 
description:
permalink: /paper_70/
grand_parent: All Papers
parent: Tuesday
supp: 
code: https://github.com/rstrudel/nmprepr
youtube_id: KRtrL4-IsFY
pdf: https://drive.google.com/file/d/1xgkZrgMfMr_aP2D1n2ljtWRCkQxsEJ0L/view
---

# Learning Obstacle Representations for Neural Motion Planning

<a href="https://drive.google.com/file/d/1xgkZrgMfMr_aP2D1n2ljtWRCkQxsEJ0L/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/rstrudel/nmprepr" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Robin STRUDEL (INRIA Paris)*; Ricardo Garcia Pinel (INRIA); Justin Carpentier (INRIA); Jean-Paul Laumond (LAAS-CNRS); Ivan Laptev (INRIA Paris); Cordelia Schmid (INRIA)**

#### Interactive Session
<em>2020-11-17, 12:30 - 13:00 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESVDCIQKBXODXGY9" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Motion planning and obstacle avoidance is a key challenge in robotics applications. While previous work succeeds to provide excellent solutions for known environments, sensor-based motion planning in new and dynamic environments remains to be  difficult. In this work we address sensor-based motion planning from a learning perspective. Motivated by recent advances in visual recognition, we argue the importance of learning appropriate representations for motion planning. We propose a new obstacle representation based on the PointNet architecture and learn it jointly with policies for obstacle avoidance. We experimentally evaluate our approach for rigid body motion planning in challenging environments and demonstrate significant improvements of the state of the art in terms of accuracy and efficiency. 

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1yBnb69eMnIYn0gLnYtzbAoJyXfVJL9TP/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


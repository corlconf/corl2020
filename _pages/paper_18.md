---
layout: page
title: "DROGON: A Trajectory Prediction Model based on Intention-Conditioned Behavior Reasoning"
subtitle: 
description:
permalink: /paper_18/
grand_parent: All Papers
parent: Tuesday
supp: 
code: 
youtube_id: PQlWx8AmoAs
pdf: https://drive.google.com/file/d/17GZtLbLp-LzpHqPJyB6Wfvoll3RDM1Wq/view
---

# DROGON: A Trajectory Prediction Model based on Intention-Conditioned Behavior Reasoning

<a href="https://drive.google.com/file/d/17GZtLbLp-LzpHqPJyB6Wfvoll3RDM1Wq/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Chiho Choi (Honda Research Institute US)*; Srikanth Malla (Honda Research Institute); Abhishek Patil (Hilti Inc); Joon Hee Choi (Sungkyunkwan University)**

#### Interactive Session
<em>2020-11-17, 11:50 - 12:20 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SES35XTHTPVUNNY6K" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
We propose a Deep RObust Goal-Oriented trajectory prediction Network (DROGON) for accurate vehicle trajectory prediction by considering behavioral intentions of vehicles in traffic scenes. Our main insight is that the behavior
(i.e., motion) of drivers can be reasoned from their high level possible goals (i.e.,
intention) on the road. To succeed in such behavior reasoning, we build a conditional prediction model to forecast goal-oriented trajectories with the following
stages: (i) relational inference where we encode relational interactions of vehicles
using the perceptual context; (ii) intention estimation to compute the probability
distributions of intentional goals based on the inferred relations; and (iii) behavior
reasoning where we reason about the behaviors of vehicles as trajectories conditioned on the intentions. To this end, we extend the proposed framework to the pedestrian trajectory prediction task, showing the potential applicability toward
general trajectory prediction.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1ZHmrBDQVyB5Gz40vUOEvMq0cHZPS1P2p/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


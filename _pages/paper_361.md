---
layout: page
title: "Uncertainty-Aware Constraint Learning for Adaptive Safe Motion Planning from Demonstrations"
subtitle: 
description:
permalink: /paper_361/
grand_parent: All Papers
parent: Tuesday
supp: https://drive.google.com/file/d/1V71zJVjzTDCms8vmOzFWKW4mO0FaRdEd/view
code: 
youtube_id: u2zDKOQqAlQ
pdf: https://drive.google.com/file/d/15TxLetso72pNSZYpvDpgdijN5TQNpRMJ/view
---

# Uncertainty-Aware Constraint Learning for Adaptive Safe Motion Planning from Demonstrations

<a href="https://drive.google.com/file/d/15TxLetso72pNSZYpvDpgdijN5TQNpRMJ/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="https://drive.google.com/file/d/1V71zJVjzTDCms8vmOzFWKW4mO0FaRdEd/view" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Glen Chou (University of Michigan)*; Dmitry Berenson (U Michigan); Necmiye Ozay (University of Michigan)**

#### Interactive Session
<em>2020-11-17, 12:30 - 13:00 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESND828XB53QBJE9" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
We present a method for learning to satisfy uncertain constraints from demonstrations. Our method uses robust optimization to obtain a belief over the potentially infinite set of possible constraints consistent with the demonstrations, and then uses this belief to plan trajectories that trade off performance with satisfying the possible constraints. We use these trajectories in a closed-loop policy that executes and replans using belief updates, which incorporate data gathered during execution. We derive guarantees on the accuracy of our constraint belief and probabilistic guarantees on plan safety. We present results on a 7-DOF arm and 12D quadrotor, showing our method can learn to satisfy high-dimensional (up to 30D) uncertain constraints and outperforms baselines in safety and efficiency.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1CHxA4XDFcnQ5AbNgf3vRAYdFLZsvYWqx/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


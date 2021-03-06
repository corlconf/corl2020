---
layout: page
title: "3D-OES: Viewpoint-Invariant Object-Factorized Environment Simulators"
subtitle: 
description:
permalink: /paper_374/
grand_parent: All Papers
parent: Monday
supp: 
code: https://zhouxian.github.io/3d-oes/
youtube_id: EghgmIEDnvE
pdf: https://drive.google.com/file/d/1XLe6cs3Xsca6g16apW80g8Hor272Yf08/view
---

# 3D-OES: Viewpoint-Invariant Object-Factorized Environment Simulators

<a href="https://drive.google.com/file/d/1XLe6cs3Xsca6g16apW80g8Hor272Yf08/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://zhouxian.github.io/3d-oes/" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Hsiao-Yu Tung (Carnegie Mellon University)*; Zhou Xian (Carnegie Mellon University); Mihir Prabhudesai (Carnegie Mellon University); Shamit Lal (CMU); Katerina Fragkiadaki (Carnegie Mellon University)**

#### Interactive Session
<em>2020-11-16, 11:50 - 12:20 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESA0QLXC61N9NC9O" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
We propose an action-conditioned dynamics model that predicts scene changes caused by object and agent interactions in a viewpoint-invariant 3D neural scene representation space, inferred from RGB-D videos. In this 3D feature space, objects do not interfere with one another and their appearance persists over time and across viewpoints. This permits our model to predict future scenes long in the future by simply “moving” 3D object features based on cumulative object motion predictions.  Object motion predictions are computed by a graph neural network that operates over the object features extracted from the 3D neural scene representation. Our model’s simulations can be decoded by a neural renderer into 2D image views from any desired viewpoint, which aids the interpretability of our latent 3D simulation space.  We show our model generalizes well its predictions across varying number and appearances of interacting objects as well as across camera viewpoints, outperforming existing 2D and 3D dynamics models. We further demonstrate sim-to-real transfer of the learnt dynamics by applying our model trained solely in simulation to model-based control for pushing objects to desired locations under clutter on a real robotic setup.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1tfobI2V32MRgnfkkUC7_WdlcCY1_cWfH/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


---
layout: page
title: "Learning RGB-D Feature Embeddings for Unseen Object Instance Segmentation"
subtitle: 
description:
permalink: /paper_99/
grand_parent: All Papers
parent: Wednesday
supp: 
code: 
youtube_id: VO8hALpL_aE
pdf: https://drive.google.com/file/d/1kk4a8Lco1VnkhkxV3hDnb5qdd28uzZ06/view
---

# Learning RGB-D Feature Embeddings for Unseen Object Instance Segmentation

<a href="https://drive.google.com/file/d/1kk4a8Lco1VnkhkxV3hDnb5qdd28uzZ06/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Yu Xiang (NVIDIA)*; Christopher Xie (University of Washington); Arsalan Mousavian (NVIDIA); Dieter Fox (NVIDIA)**

#### Interactive Session
<em>2020-11-18, 11:10 - 11:40 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESEE5MDVCJVD75FU" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Segmenting unseen objects in cluttered scenes is an important skill that robots need to acquire in order to perform tasks in new environments. In this work, we propose a new method for unseen object instance segmentation by learning RGB-D feature embeddings from synthetic data. A metric learning loss function is utilized to learn to produce pixel-wise feature embeddings such that pixels from the same object are close to each other and pixels from different objects are separated in the embedding space. With the learned feature embeddings, a mean shift clustering algorithm can be applied to discover and segment unseen objects. We further improve the segmentation accuracy with a new two-stage clustering algorithm. Our method demonstrates that non-photorealistic synthetic RGB and depth images can be used to learn feature embeddings that transfer well to real-world images for unseen object instance segmentation.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/16aDXXpmkSOuz1XOd_nJ1RFXoRZ2nk7Cr/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


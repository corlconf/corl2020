---
layout: page
title: "SoftGym: Benchmarking Deep Reinforcement Learning for Deformable Object Manipulation"
subtitle: 
description:
permalink: /paper_91/
grand_parent: All Papers
parent: Tuesday
supp: 
code: https://github.com/Xingyu-Lin/softgym
youtube_id: lt9UV9hev6w
pdf: https://drive.google.com/file/d/1LuhPlBgsaaUEP5bs_PIP3taaWQhcUdE5/view
---

# SoftGym: Benchmarking Deep Reinforcement Learning for Deformable Object Manipulation

<a href="https://drive.google.com/file/d/1LuhPlBgsaaUEP5bs_PIP3taaWQhcUdE5/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/Xingyu-Lin/softgym" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Xingyu Lin (Carnegie Mellon University)*; Yufei Wang (Carnegie Mellon University); Jake Olkin (CMU); David Held (CMU)**

#### Interactive Session
<em>2020-11-17, 11:10 - 11:40 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESVTRP2JS6WMYPE5" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Manipulating deformable objects has long been a challenge in robotics due to its high dimensional state representation and complex dynamics. Recent success in deep reinforcement learning provides a promising direction for learning to manipulate deformable objects with data driven methods. However, existing reinforcement learning benchmarks only cover tasks with direct state observability and simple low-dimensional dynamics or with relatively simple image-based environments, such as those with rigid objects. In this paper, we present SoftGym, a set of open-source simulated benchmarks for manipulating deformable objects, with a standard OpenAI Gym API and a Python interface for creating new environments. Our benchmark will enable reproducible research in this important area. Further, we evaluate a variety of algorithms on these tasks and highlight challenges for reinforcement learning algorithms, including dealing with a state representation that has a high intrinsic dimensionality and is partially observable. The experiments and analysis indicate the strengths and limitations of existing methods in the context of deformable object manipulation that can help point the way forward for future methods development.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


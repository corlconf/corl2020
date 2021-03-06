---
layout: page
title: "BayesRace: Learning to race autonomously using prior experience"
subtitle: 
description:
permalink: /paper_428/
grand_parent: All Papers
parent: Tuesday
supp: 
code: https://github.com/jainachin/bayesrace
youtube_id: dgIpf0Lg8Ek
pdf: https://drive.google.com/file/d/1ZVmsNLsQQAQQf5jAoUUIZ2wOVg7NjSgh/view
---

# BayesRace: Learning to race autonomously using prior experience

<a href="https://drive.google.com/file/d/1ZVmsNLsQQAQQf5jAoUUIZ2wOVg7NjSgh/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/jainachin/bayesrace" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Achin Jain (University of Pennsylvania)*; Matthew O'Kelly (University of Pennsylvania); Pratik Chaudhari (University of Pennsylvania); Manfred Morari (University of Pennsylvania)**

#### Interactive Session
<em>2020-11-17, 12:30 - 13:00 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SES9KYIJ0A8J4OSAD" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Autonomous race cars require perception, estimation, planning, and control modules which work together asynchronously while driving at the limit of a vehicle’s handling capability. A fundamental challenge encountered in designing these software components lies in predicting the vehicle’s future state (e.g. position, orientation, and speed) with high accuracy. The root cause is the difficulty in identifying vehicle model parameters that capture the effects of lateral tire slip. We present a model-based planning and control framework for autonomous racing that significantly reduces the effort required in system identification and control design. Our approach alleviates the gap induced by simulation-based controller design by learning from on-board sensor measurements. A major focus of this work is empirical, thus, we demonstrate our contributions by experiments on validated 1:43 and 1:10 scale autonomous racing simulations.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1oSo-xR_nMs5QUALHacNo5Pj_QmDBgOro/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


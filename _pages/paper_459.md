---
layout: page
title: "Sampling-based Reachability Analysis: A Random Set Theory Approach with Adversarial Sampling"
subtitle: 
description:
permalink: /paper_459/
grand_parent: All Papers
parent: Tuesday
supp: 
code: https://github.com/StanfordASL/UP
youtube_id: mo079YBVTzE
pdf: https://drive.google.com/file/d/1_ZKJV7JMX1i-xT6w6XfeH7iAKCR1XDDp/view
---

# Sampling-based Reachability Analysis: A Random Set Theory Approach with Adversarial Sampling

<a href="https://drive.google.com/file/d/1_ZKJV7JMX1i-xT6w6XfeH7iAKCR1XDDp/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/StanfordASL/UP" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Thomas Lew (Stanford University)*; Marco Pavone (Stanford University)**

#### Interactive Session
<em>2020-11-17, 11:10 - 11:40 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESQG6EYT2WC4O1HR" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Reachability analysis is at the core of many applications, from neural network verification, to safe trajectory planning of uncertain systems. However, this problem is notoriously challenging, and current approaches tend to be either too restrictive, too slow, too conservative, or approximate and therefore lack guarantees. In this paper, we propose a simple yet effective sampling-based approach to perform reachability analysis for arbitrary dynamical systems. Our key novel idea consists of using random set theory to give a rigorous interpretation of our method, and prove that it returns sets which are guaranteed to converge to the convex hull of the true reachable sets. Additionally, we leverage recent work on robust deep learning and propose a new adversarial sampling approach to robustify our algorithm and accelerate its convergence. We demonstrate that our method is faster and less conservative than prior work, present results for approximate reachability analysis of neural networks and robust trajectory optimization of high-dimensional uncertain nonlinear systems, and discuss future applications.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1mxO9GohPnmKO6amiJb8EghCjaGwSS7jL/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


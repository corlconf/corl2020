---
layout: page
title: "Task-Relevant Adversarial Imitation Learning"
subtitle: 
description:
permalink: /paper_50/
grand_parent: All Papers
parent: Monday
supp: 
code: 
youtube_id: BQMJ1umzvJI
pdf: https://drive.google.com/file/d/1Mj4Tm3fnnRkQTwLelsCCCj_7SAd7g1Yt/view
---

# Task-Relevant Adversarial Imitation Learning

<a href="https://drive.google.com/file/d/1Mj4Tm3fnnRkQTwLelsCCCj_7SAd7g1Yt/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Konrad Zolna (DeepMind)*; Scott Reed (DeepMind); Alexander Novikov (DeepMind); Sergio Gómez Colmenarejo (DeepMind); David Budden (DeepMind); Serkan Cabi (DeepMind); Misha Denil (DeepMind); Nando de Freitas (DeepMind); Ziyu Wang (Google Research, Brain Team)**

#### Interactive Session
<em>2020-11-16, 11:10 - 11:40 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESIROZ964FC04UDV" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
We show that a critical vulnerability in adversarial imitation is the tendency of discriminator networks to learn spurious associations between visual features and expert labels. When the discriminator focuses on task-irrelevant features, it does not provide an informative reward signal, leading to poor task performance. We analyze this problem in detail and propose a solution that outperforms standard Generative Adversarial Imitation Learning (GAIL). Our proposed method, Task-Relevant Adversarial Imitation Learning (TRAIL), uses constrained discriminator optimization to learn informative rewards. In comprehensive experiments, we show that TRAIL can solve challenging robotic manipulation tasks from pixels by imitating human operators without access to any task rewards, and clearly outperforms comparable baseline imitation agents, including those trained via behaviour cloning and conventional GAIL.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/17Y1uf_-H0IzYdHdtc_RUcz21Xso8isyt/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


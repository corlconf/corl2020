---
layout: page
title: "Augmenting GAIL with BC for sample efficient imitation learning"
subtitle: 
description:
permalink: /paper_25/
grand_parent: All Papers
parent: Monday
supp: 
code: https://github.com/rohitrango/BC-regularized-GAIL
youtube_id: nJUAY5BohaE
pdf: https://drive.google.com/file/d/1Dd571oHIddZrVnP4S9AWYWLVEaIpcRf4/view
---

# Augmenting GAIL with BC for sample efficient imitation learning

<a href="https://drive.google.com/file/d/1Dd571oHIddZrVnP4S9AWYWLVEaIpcRf4/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/rohitrango/BC-regularized-GAIL" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Rohit Jena (Carnegie Mellon University)*; Changliu Liu (Carnegie Mellon University); Katia Sycara (Carnegie Mellon University)**

#### Interactive Session
<em>2020-11-16, 11:10 - 11:40 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SEST4CSV8GKRQNUGZ" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Imitation learning is the problem of recovering an expert policy without access to a reward signal. Behavior cloning and GAIL are two widely used methods for performing imitation learning. Behavior cloning converges in a few iterations, but doesn't achieve peak performance due to its inherent iid assumption about the state-action distribution. GAIL addresses the issue by accounting for the temporal dependencies when performing a state distribution matching between the agent and the expert. Although GAIL is sample efficient in the number of expert trajectories required, it is still not very sample efficient in terms of the environment interactions needed for convergence of the policy. Given the complementary benefits of both methods, we present a simple and elegant method to combine both methods to enable stable and sample efficient learning. Our algorithm is very simple to implement and integrates with different policy gradient algorithms. We demonstrate the effectiveness of the algorithm in low dimensional control tasks, gridworlds and in high dimensional image-based tasks.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1TUoZ5IddSCapkb-CYELC_709C7DmdQtK/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


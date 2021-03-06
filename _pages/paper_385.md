---
layout: page
title: "Learning a natural-language to LTL executable semantic parser for grounded robotics"
subtitle: 
description:
permalink: /paper_385/
grand_parent: All Papers
parent: Monday
supp: 
code: https://github.com/czlwang/grounded_LTL_parser
youtube_id: jeBYxivT9o4
pdf: https://drive.google.com/file/d/1Y2514MAvBiizdsIFLAX24WVUvCDXGn8b/view
---

# Learning a natural-language to LTL executable semantic parser for grounded robotics

<a href="https://drive.google.com/file/d/1Y2514MAvBiizdsIFLAX24WVUvCDXGn8b/view" target="_blank" rel="noopener noreferrer" class="btn btn-blue"><i class="fa fa-file-text-o" aria-hidden="true"></i> Paper PDF </a> {% if page.supp %}<a href="" target="_blank" rel="noopener noreferrer" class="btn btn-green"><i class="fa fa-file-text-o" aria-hidden="true"></i> Supplemental </a>{% endif %} {% if page.code %}<a href="https://github.com/czlwang/grounded_LTL_parser" target="_blank" rel="noopener noreferrer" class="btn"><i class="fa fa-github" aria-hidden="true"></i> Code </a>{% endif %} 

#### Authors
**Christopher Wang (MIT)*; Candace Ross (Massachusetts Institute of Technology); Yen-Ling Kuo (MIT); Boris Katz (MIT); Andrei Barbu (MIT)**

#### Interactive Session
<em>2020-11-16, 12:30 - 13:00 PST </em> | <a href="https://pheedloop.com/corl2020/virtual/?page=sessions&section=SESXLDJ62W5I0YLPL" target="_blank" rel="noopener noreferrer"> PheedLoop Session <i class="fa fa-external-link" aria-hidden="true"></i> </a> 

#### Abstract
Children acquire their native language with apparent ease by observing how language is used in context and attempting to use it themselves. They do so without laborious annotations, negative examples, or even direct corrections. We take a step toward robots that can do the same by training a grounded semantic parser, which discovers latent linguistic representations that can be used for the execution of  natural-language commands. In particular, we focus on the difficult domain of commands with a temporal aspect, whose semantics we capture with Linear Temporal Logic, LTL. Our parser is trained with pairs of sentences and executions as well as an executor. At training time, the parser hypothesizes a meaning representation for the input as a formula in LTL. Three competing pressures allow the parser to discover  meaning from language. First, any hypothesized meaning for a sentence must be permissive enough to reflect all the annotated execution trajectories. Second, the executor - a pretrained end-to-end LTL planner - must find that the observed trajectories are  likely executions of the meaning. Finally, a generator, which reconstructs the original input, encourages the model to find representations that conserve knowledge about the command. Together these ensure that the meaning is neither too general nor too specific. Our model generalizes well, being able to parse and execute both machine-generated and human-generated commands, with near-equal accuracy, despite the fact that the human-generated sentences are much more varied and complex with an open lexicon. The approach presented here is not specific to LTL: it can be applied to any domain where sentence meanings can be hypothesized and  an executor can verify these meanings, thus opening the door to many applications for robotic agents.

#### Video
{% if page.youtube_id %}
{% include youtubePlayer.html id=page.youtube_id %}
{% endif %}

#### Reviews and Rebuttal
<a href="https://drive.google.com/file/d/1oGK50v_khNFTt_JfROBCIbIg3fZo6J0l/view" target="_blank" rel="noopener noreferrer" class="btn btn-purple"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Reviews & Rebuttal </a>


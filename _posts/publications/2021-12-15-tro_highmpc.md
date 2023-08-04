---
layout: post
title: "Policy Search for Model Predictive Control with Application to Agile Drone Flight"
date: 2021-12-16
categories: Publications
thumbnail: images/publications/high_mpc/Trajectory.jpg
comments: false
---

> Policy Search and Model Predictive Control (MPC) are two different paradigms for robot control: policy search has the strength of automatically learning complex policies using experienced data, while MPC can offer optimal control performance using models and trajectory optimization. An open research question is how to leverage and combine the advantages of both approaches. In this work, we provide an answer by using policy search for automatically choosing high-level decision variables for MPC, which leads to a novel policy-search-for-model-predictive-control framework. Specifically, we formulate the MPC as a parameterized controller, where the hard-to-optimize decision variables are represented as high-level policies. Such a formulation allows optimizing policies in a self-supervised fashion. We validate this framework by focusing on a challenging problem in agile drone flight: flying a quadrotor through fast-moving gates. Experiments show that our controller achieves robust and real-time control performance in both simulation and the real world. The proposed framework offers a new perspective for merging learning and control.

<p style="text-align:center; color:#AB3218; font-weight:bold">Yunlong Song, Davide Scaramuzza</p>

<a style="text-align:center; color:#081b86; font-weight:bold" href="http://rpg.ifi.uzh.ch/docs/TRO21_Yunlong.pdf">PDF</a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Qei7oGiEIxY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

##### BibTex

<div class="col-lg-8" style="padding:0;">
<div style="background:#ffffff;margin:0px;padding:0px;">
<pre>
    <code class="pre-scrollable" style="background:#ffffff;color:#333;font-size:12px;padding:0px;border-width:0px;">
    @article{song2021policy,
      title={Policy Search for Model Predictive Control with Application to Agile Drone Flight},
      author={Song, Yunlong and Scaramuzza, Davide},
      journal={arXiv preprint arXiv:2112.03850},
      year={2021}
    }
    </code>
</pre>
</div>
</div>

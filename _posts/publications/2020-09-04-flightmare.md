---
layout: post
title:  "Flightmare: A Flexible Quadrotor Simulator (CoRL 2020)"
date:  2020-09-04
categories: Publications
thumbnail: images/publications/flightmare/flightmare.png
comments: false
---


> Currently available quadrotor simulators have a rigid and highly-specialized structure: either are they really fast, physically accurate, or photo-realistic. In this work, we propose a paradigm-shift in the development of simulators: moving the trade-off between accuracy and speed from the developers to the end-users. We release a new modular quadrotor simulator: Flightmare. Flightmare is composed of two main components: a configurable rendering engine built on Unity and a flexible physics engine for dynamics simulation. Those two components are totally decoupled and can run independently from each other. Flightmare comes with several desirable features: (i) a large multi-modal sensor suite, including an interface to extract the 3D point-cloud of the scene; (ii) an API for reinforcement learning which can simulate hundreds of quadrotors in parallel; and (iii) an integration with a virtual-reality headset for interaction with the simulated environment. Flightmare can be used for various applications, including path-planning, reinforcement learning, visual-inertial odometry, deep learning, human-robot interaction, etc.

<p style="text-align:center; color:#AB3218; font-weight:bold">Yunlong Song, Selim Naji, Elia Kaufmann, Antonio Loquercio, Davide Scaramuzza</p>

<a style="text-align:center; color:#081b86; font-weight:bold" href="https://arxiv.org/abs/2009.00563">PDF</a>, <a style="text-align:center; color:#081b86; font-weight:bold" href="https://uzh-rpg.github.io/flightmare/">Website</a>


<iframe width="750" height="421" src="https://www.youtube.com/embed/m9Mx1BCNGFU" frameborder="0"
    allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

##### BibTex
<div class="col-lg-8" style="padding:0;">
<div style="background:#ffffff;margin:0px;padding:0px;">
<pre>
    <code class="pre-scrollable" style="background:#ffffff;color:#333;font-size:12px;padding:0px;border-width:0px;">
    @inproceedings{song2020flightmare,
        title={Flightmare: A Flexible Quadrotor Simulator},
        author={Song, Yunlong and Naji, Selim and Kaufmann, Elia and Loquercio, Antonio and Scaramuzza, Davide},
        booktitle={Conference on Robot Learning},
        year={2020}
    }
    </code>
</pre>
</div>
</div>
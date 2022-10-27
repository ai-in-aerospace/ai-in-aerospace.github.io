---
name: "Agile Earth-Observing Satellite Simulation"
layout: single
title:  "Agile Earth-Observing Satellite Simulation"
classes: wide
# date:   2020-08-09 18:22:51 -0600
collection: contributions

header:
  teaser: assets/concept_image_agile.png
---

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/concept_image_agile.png" alt="">
  <figcaption>Agile Earth-Observing Satellite Scheduling Problem Concept Figure.</figcaption>
</figure>

This is a simulator created for reinforcement learning research that utilizes the [Basilisk astrodynamics
software architecture](https://hanspeterschaub.info/basilisk/index.html). In the agile EOS scheduling problem, a
satellite in low-Earth orbit attempts to maximize the weighted sum of surface targets imaged and downlinked to seven
ground stations on the surface of the Earth while managing resources such as power, data buffer storage, and reaction
wheel speeds. The satellite has a set of targets, each with its own priority, it has access to throughout the planning
horizon.

[Paper](https://hanspeterschaub.info/Papers/Herrmann2022a.pdf){: .btn .btn--primary .btn--large}
[Source Code](https://bitbucket.org/avslab/basilisk-gym-interface/src/develop/basilisk_env/envs/multiTgtEarthEnvironment/){: .btn .btn--primary .btn--large}
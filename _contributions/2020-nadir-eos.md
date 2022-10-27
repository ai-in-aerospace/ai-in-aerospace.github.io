---
name: "Nadir-Science Earth-Observing Satellite Simulation"
layout: single
title:  "Nadir-Science Earth-Observing Satellite Simulation"
classes: wide
# date:   2020-08-09 18:22:51 -0600
collection: contributions

header:
  teaser: assets/concept_image_nadir.png
---

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/concept_image_nadir.png" alt="">
  <figcaption>Nadir-Science Earth-Observing Satellite Scheduling Problem Concept Figure.</figcaption>
</figure> 

This is a simulator created for reinforcement learning research that utilizes the [Basilisk astrodynamics
software architecture](https://hanspeterschaub.info/basilisk/index.html). In the nadir-science EOS scheduling problem, a
satellite in low-Earth orbit attempts to maximize the amount of data downlinked to seven ground stations on the
surface of the Earth while managing resources such as power, data buffer storage, and reaction wheel speeds. Data is
collected when the satellite points the instrument in the nadir-direction.

[Paper](https://arc.aiaa.org/doi/10.2514/1.I010992){: .btn .btn--primary .btn--large}
[Source Code](https://bitbucket.org/avslab/basilisk-gym-interface/src/develop/basilisk_env/envs/leoNadirEnvironment/){: .btn .btn--primary .btn--large}
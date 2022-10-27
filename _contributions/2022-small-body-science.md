---
name: "Small Body Science Simulation"
layout: single
title:  "Small Body Science Simulation"
classes: wide
# date:   2020-08-09 18:22:51 -0600
collection: contributions

header:
  teaser: assets/concept_image_small_body.png
---

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/concept_image_small_body.png" alt="">
  <figcaption>Small Body Science Concept Figure.</figcaption>
</figure>

This is a simulator created for reinforcement learning research that utilizes the [Basilisk astrodynamics
software architecture](https://hanspeterschaub.info/basilisk/index.html). In the small body science operations problem,
a spacecraft moves between waypoints defined in the small body's Hill frame while collecting mapping data and surface
target images. The spacecraft has access to the DSN every 24 hours and has to manage resources such as battery charge,
data buffer storage, and fuel while avoiding collision with the body. The spacecraft is collecting three separate
spectroscopy maps, each at a specific solar phase angle. The spacecraft also has a set of 10 surface targets that
represent candidate landing sites it is attempting to image.

[Paper](https://hanspeterschaub.info/Papers/Herrmann2022c.pdf){: .btn .btn--primary .btn--large}
[Source Code](https://bitbucket.org/avslab/basilisk-gym-interface/src/develop/basilisk_env/envs/smallBodyScienceEnvironment/){: .btn .btn--primary .btn--large}
---
name: "Agile Earth-Observing Constellation Simulation"
layout: single
title:  "Agile Earth-Observing Satellite Constellation Simulation"
classes: wide
# date:   2020-08-09 18:22:51 -0600
collection: contributions

header:
  teaser: assets/concept_image_multi.png
---

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/concept_image_multi.png" alt="">
  <figcaption>Agile Earth-Observing Satellite Constellation Concept Figure.</figcaption>
</figure>

This is a simulator created for reinforcement learning research. This simulator extends the [agile EOS simulator](2021-agile-eos.md)
to Walker-delta constellations. A global target set is distributed to each spacecraft based on their access, and
each satellite attempts to maximize the weighted sum of targets imaged and downlinked. My co-author on the paper listed
below, Jo&#227;o Vaz Carneiro, created a MultiSatBskSim architecture and applied it to this simulator. I was in charge of
wrapping the simulator in the Gym environment and creating the Walker-delta support functionality and initial condition
generation.

[Paper](https://hanspeterschaub.info/Papers/Herrmann2022.pdf){: .btn .btn--primary .btn--large}
[Source Code](https://bitbucket.org/avslab/basilisk-gym-interface/src/develop/basilisk_env/envs/multiSatMultiTgtEarthEnvironment/){: .btn .btn--primary .btn--large}
---
name: "On-Board Data Generation Modeling"
layout: single
title:  "On-Board Data Generation Modeling"
classes: wide
# date:   2020-08-09 18:22:51 -0600
collection: contributions

header:
  teaser: assets/GPGPU.jpg
---

<figure style="width: 300px" class="align-right">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/GPGPU_original.jpg" alt=""> 
  <figcaption>Parallelizing the spherical harmonic algorithm requires careful though how operations are sequence.</figcaption>
</figure> 

On-board science data generation, downlink, and storage are an important part of planning and scheduling for both
Earth-orbiting and deep space missions. Throughout my PhD, I've created many simulation tools within Basilisk to support
the modeling of on-board science data. This includes data buffers, instruments, transmitters, etc. that all interact
with one another to manage data on-board the spacecraft.

### On-Board Data Modeling Components
[Source Code](https://bitbucket.org/avslab/basilisk/src/develop/src/simulation/onboardDataHandling/){: .btn .btn--primary .btn--large}
[Documentation](https://hanspeterschaub.info/basilisk/Documentation/simulation/onboardDataHandling/index.html?highlight=onboard+data){: .btn .btn--primary .btn--large}

### Instrument Controller Based on Access Requirements
[Source Code](https://bitbucket.org/avslab/basilisk/src/develop/src/fswAlgorithms/sensorInterfaces/simpleInstrumentController/){: .btn .btn--primary .btn--large}
[Documentation](https://hanspeterschaub.info/basilisk/Documentation/fswAlgorithms/sensorInterfaces/simpleInstrumentController/simpleInstrumentController.html){: .btn .btn--primary .btn--large}

### Mapping Body-Fixed Points
[Source Code](https://bitbucket.org/avslab/basilisk/src/develop/src/simulation/environment/groundMapping/){: .btn .btn--primary .btn--large}
[Documentation](https://hanspeterschaub.info/basilisk/Documentation/simulation/environment/groundMapping/groundMapping.html){: .btn .btn--primary .btn--large}

### Simple Example Scenario w/ Nadir-Pointing Spacecraft
[Source Code](https://bitbucket.org/avslab/basilisk/src/develop/examples/scenarioDataDemo.py){: .btn .btn--primary .btn--large}
[Documentation](https://hanspeterschaub.info/basilisk/examples/scenarioDataDemo.html){: .btn .btn--primary .btn--large}

### Example Scenario w/ Target-Pointing Spacecraft and Access Constraints
[Source Code](https://bitbucket.org/avslab/basilisk/src/develop/examples/scenarioGroundLocationImaging.py){: .btn .btn--primary .btn--large}
[Documentation](https://hanspeterschaub.info/basilisk/examples/scenarioGroundLocationImaging.html){: .btn .btn--primary .btn--large}

### Example Scenario w/ Mapping
[Source Code](https://bitbucket.org/avslab/basilisk/src/develop/examples/scenarioGroundMapping.py){: .btn .btn--primary .btn--large}
[Documentation](https://hanspeterschaub.info/basilisk/examples/scenarioGroundMapping.html){: .btn .btn--primary .btn--large}
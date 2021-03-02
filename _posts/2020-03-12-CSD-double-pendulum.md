---
title: 'Controller Design for Double Pendulum'
categories:
  - projects
tags:
  - Control Engineering
  - Uni Project
# image:
#   path: /assets/images/2020-03-12-CSD-double-pendulum/
#   thumbnail: /assets/images/2020-03-12-CSD-double-pendulum
#   caption: "test"
actions:
  - label: "Github"
    icon: github  # references name of svg icon, see full list below
    url: "https://github.com/h0uter/control-system-design-double-pendulum"
---

<div class="embed-responsive embed-responsive-16by9">
  <iframe width="640" height="360" src="https://www.youtube.com/embed/qcokfeDFilA?controls=1&amp;" frameborder="0" allowfullscreen></iframe>
</div>

(not our video, but same setup. credits: Taamsie)

A double pendulum is studied, where only the first link can be actuated using a motor. Firstly, the system will be modeled using a white-box approach. After determining the equations of motion and state-space equations, the parameters of the system are estimated using an error-function and least-squares fit on generated data. To stabilize the double pendulum in the unstable equilibrium where both links point upwards, the system is linearized around this point. After linearizing and designing an observer, two controllers are designed to stabilize the system around this point. Since the physical setups are not available due to the Corona virus, all results were analyzed in Simulink.


<!-- <iframe width="560" height="400" src="https://www.youtube.com/embed/qcokfeDFilA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<!-- (credits: not my video, but same setup) -->

<!-- https://github.com/h0uter/control-system-design-double-pendulum -->

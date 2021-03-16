---
title: 'Quadrotor Motion Planning'
# categories:
#   - projects
# tags:
#   - Motion Planning
#   - Uni Project
#   - Python
img: /assets/img/PDM_preview.gif
# image: 
#   path: /assets/img/PDM_preview.gif
#   thumbnail: /assets/img/PDM_preview.gif
#   caption: "test"
# actions:
#   - label: "Our paper"
#     icon: pdf # references name of svg icon, see full list below
#     url: "/assets/quad-rotor_routing_RRT.pdf"
#   - label: "Show me the code!"
#     icon: github  # references name of svg icon, see full list below
#     url: "https://github.com/h0uter/PDM-project"

---

<!-- ![wow](/assets/img/PDM_preview.gif) -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/PDM_preview.gif' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Here you can see the generated path being chased.
</div>


In this report we present a comparison between RRT, RRT* and Informed-RRT* path planners in $R^3$ for a general quad-rotor. We compare their runtime performance and optimal path cost in two unique environments. We introduce kinodynamic constraints to prevent collisions and evaluate their impact on runtime performance. 
ok
[PDM Project](https://github.com/h0uter/PDM-project)

<!-- In short: we built a simulation from the ground up in Python and then implemented RRT and RRT* path planning algorithms to find a path through an obstacle course. Then we simulated a quadrotor to execute this trajectory with a PID controller and chase mode. -->

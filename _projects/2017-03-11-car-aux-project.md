---
layout: page
title: 'Upgrading Car Radio with AUX'
description: Spotify take the wheel

# categories:
#   - projects
# tags:
#   - Electronics
img: /assets/2017-03-11-car-aux-project/car-aux-pcb_thumb.jpg

# actions:
#   - label: "Download the car radio manual"
#     icon: pdf # references name of svg icon, see full list below
#     url: "/assets/pioneer_keh-2700_2730r_SM.pdf"
---


Me and my brother share our grandmas old car, it's a beautiful Renault Mégane 2.0 from 1998. However we wanted to listen to our own music, unfortunately the car only supported radio or cassette. So a new projects was conceived.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/2017-03-11-car-aux-project/car-aux-wires.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    The radio removed from its enclosure to find the model number.
</div>

<!-- ![](/assets/images/car-aux-wires.jpg) -->
I removed the car radio from its socket to inspect the model type. A search on google bought me to the manual, luckily back in the day companies still provide in-depth electronic schematics for their products.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/2017-03-11-car-aux-project/car-aux-diagram-min.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    The diagram of the PCB including the cassete amplifier.
</div>
<!-- ![](/assets/images/car-aux-diagram-min.png) -->
Inspecting the schematics allowed be to identify the cassette amplifier.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/2017-03-11-car-aux-project/car-aux-pcb.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    The red and blue wires are the L and R channel soldered into the cassete amplifier. The black wire is the grounding.
</div>

<!-- ![](/assets/images/car-aux-pcb.jpg) -->

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/2017-03-11-car-aux-project/car-aux-jack.jpeg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    The resulting 3.5mm jack neatly inserted in the corner of the radio front.
</div>
<!-- ![](/assets/images/car-aux-jack.jpeg) -->
So I soldered in an 3.5mm female port parallel to the cassette input.
This ensured the 3.5mm output from my phone would be properly amplified before it's sent to car the speakers.

## Update 2021
The custom AUX port is still going strong and has allowed me and my brother to listen to many hours of music and podcasts.
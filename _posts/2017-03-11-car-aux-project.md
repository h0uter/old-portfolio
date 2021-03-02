---
title: 'Upgrading my car radio with AUX'
categories:
  - projects
tags:
  - Electronics
image: 
  path: /assets/images/car-aux-pcb.jpg
  thumbnail: /assets/images/car-aux-pcb_thumb.jpg
  caption: "test"
actions:
  - label: "Download the car radio manual"
    icon: pdf # references name of svg icon, see full list below
    url: "/assets/pioneer_keh-2700_2730r_SM.pdf"
---


Me and my brother share our grandmas old car, it's a beautiful Renault Mégane 2.0 from 1998. However we wanted to listen to our own music, unfortunately the car only supported radio or cassette. So a new projects was conceived.


![](/assets/images/car-aux-wires.jpg)
I removed the car radio from its socket to inspect the model type. A search on google bought me to the manual, luckily back in the day companies still provide in-depth electronic schematics for their products.


![](/assets/images/car-aux-diagram-min.png)
Inspecting the schematics allowed be to identify the cassette amplifier.


![](/assets/images/car-aux-pcb.jpg)
![](/assets/images/car-aux-jack.jpeg)
So I soldered in an 3.5mm female port parallel to the cassette input.
This ensured the 3.5mm output from my phone would be properly amplified before it's sent to car the speakers.

## Update 2021
The custom AUX port is still going strong and has allowed me and my brother to listen to many hours of music and podcasts.
---
layout: project
title: Statics Homework Problem
description: Homework Problem
technologies: [n/a]
image: /assets/images/statics-step1.jpg
---

For homework, we were asked to design a frame/mechanism to lift the maximum possible weight to the highest possible height. 

There are 4 main constraints. One, the mechanism must exist in a 2D design space that is 150 cm long by 50 cm tall. Two, the bar must be a fixed length. Three, there must be 3 pin supports, two of which need to be mounted to the ground. Four, the design must use a linear actuator.

The main objective of the problem is to lift the maximum possible weight to the highest possible height.

In terms of degrees of freedom, there are 3 main ones: the type of actuator, the length of the bar, and the placement of the pins. 

This next section will discuss the static analysis I conducted to determine my final design. To start, I chose the RSX linear actuator because out of all the actuators in the catalog, it was able to supply the most force. Next, I conducted torque analysis. I thought about the design like a door, the closer to the hinges I push on a door, the harder it is to swing it open. I wanted to maximize the amount of torque applied to the bar in order to raise it to the max height. Using this concept and therefore the equation M = r x F, I decided to place the actuator closest to do end of the bar - furthest from the pivot.

The image below shows my final design.

![Photo of old radio]({{ "/assets/images/statics-step1.jpg" | relative_url }}){: .inline-image-l}

The second part of the homework asked to consider the same situation, but the beam is now in bending. To find the maximum deflection of the beam and choose the most mass-efficent beam design, I conducted the following analysis.
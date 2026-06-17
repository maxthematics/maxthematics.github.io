---
title: "Dynamic Quantum Walk"
layout: illustration
tool: CindyJS
topics: [physics, quantum mechanics, probability]
thumbnail: /assets/images/illustrations/quantum-walk.png
applet_url: https://maxthematics.github.io/dynamicQuantumWalk/quantumwalk.html
applet_height: 700
source_url: https://github.com/maxthematics/dynamicQuantumWalk
---

A **quantum walk** is the quantum version of the simplest random process there is: a coin-flip walk. In the everyday version you flip a coin at each step and move one place left or right—and after many steps you have usually drifted only a little from where you started. A quantum particle does something stranger. Instead of going left *or* right, it goes left *and* right at the same time, in a **superposition**, and these overlapping possibilities can **interfere**—reinforcing each other in some places and cancelling out in others.

That interference completely changes how far the walk reaches. A classical coin-flip walk creeps outward only with the square root of the number of steps,

$$\text{classical spread} \sim \sqrt{n},$$

and settles into the familiar bell curve. A quantum walk instead spreads in proportion to the number of steps itself ($\sim n$)—far faster—and builds a very different, two-horned shape with most of the particle pushed out toward the edges.

This visualization shows the **probability of finding the particle** at each position as time goes on, alongside the classical case, so you can watch quantum interference outrun ordinary diffusion. This faster spreading is one of the reasons quantum walks power some quantum algorithms.

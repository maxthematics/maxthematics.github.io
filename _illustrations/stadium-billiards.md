---
title: "Stadium Billiards"
layout: illustration
tool: CindyJS
topics: [dynamical systems, chaos, billiards]
thumbnail: /assets/images/illustrations/stadium-billiards.png
applet_url: https://maxthematics.github.io/illustratingMath-cindy/stadion.html
applet_height: 700
source_url: https://github.com/maxthematics/illustratingMath-cindy
---

A **mathematical billiard** is a single ball that travels in a straight line and bounces off the walls of a table with no friction—the angle coming in equals the angle going out, forever. Remarkably, the *shape* of the table alone decides whether the motion stays predictable or turns chaotic.

The **stadium**—a rectangle with two semicircular ends—is the textbook example of a *chaotic* billiard. In this innocent-looking shape the bouncing becomes completely unpredictable in the long run: a single ball eventually visits every part of the table, and the rounded ends gradually pull apart paths that started out side by side.

This simulation makes that unpredictability visible. Launch a tight bundle of balls from almost the same point and watch them: they stay together for a moment, then separate and scatter across the whole stadium. The tiny gap between two paths grows faster and faster—roughly

$$\delta(t) \sim \delta_0 \, e^{\lambda t},$$

doubling again and again. This runaway sensitivity to the starting point is the defining feature of **chaos**.

Use the sliders to set the **number of balls** (1 to 1000), how far apart they start (from $10^{0}$ down to $10^{-7}$), and the **animation speed**. Press **Start/Pause** to run the simulation and **Reset** to relaunch with the current settings. Try the smallest start distance with many balls to see how quickly even near-identical launches fan out.

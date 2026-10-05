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

A **quantum walk** is the quantum counterpart of the coin-flip walk. In the classical version you flip a coin at each step and move one place left or right. In the quantum version the walker carries a **qubit**, and nothing is random until you look. At every position the state of the walk is a pair of arrows (phasors), one for "left" and one for "right". Each step applies the same fixed rule to every pair—the **coin gate**—and then shifts one arrow to the left and the other to the right. Where two arrows meet, the next coin gate **adds** them: they can reinforce each other or cancel. This is **interference**.

Because arrows are added instead of probabilities, the walk spreads differently. A classical coin-flip walk creeps outward with the square root of the number of steps,

$$\text{classical spread} \sim \sqrt{n},$$

and settles into the familiar bell curve. The quantum walk spreads in proportion to the number of steps ($\sim n$) and builds a two-horned shape with most of the probability near the edges.

This visualization shows the **probability of finding the walker** at each position as time goes on—the sum of the squared lengths of the two arrows there—alongside the classical case. Chance enters only when the position is measured; measured after every step, the walk gives the bell curve again. On a line all of this can be computed classically: the walk shows how interference works, not a speed-up. On other graphs, quantum walks are building blocks of quantum algorithms.
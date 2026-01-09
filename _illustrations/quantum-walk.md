---
title: "Dynamic Quantum Walk"
layout: illustration
tool: CindyJS
topics: [quantum, physics, probability]
thumbnail: /assets/images/illustrations/quantum-walk.png
applet_url: https://maxthematics.github.io/dynamicQuantumWalk/quantumwalk.html
applet_height: 700
source_url: https://github.com/maxthematics/dynamicQuantumWalk
---

A **quantum walk** is the quantum-mechanical analog of a simple classical random walk. In the classical 1D model, a particle steps left or right with equal probability. A quantum walk, in contrast, evolves in **superposition**, and different paths can **interfere**.

For a classical random walk, the position distribution after n steps is derived from a binomial distribution and becomes approximately Gaussian for large n. A quantum walk typically yields a very different shape: interference can suppress some positions and amplify others, often leading to an overall **faster spread** than in the classical case.

The (discrete-time, coined) quantum walk is governed by a unitary step operator U acting on the combined Hilbert space of **position** and **coin**:

$$U = S \cdot (C \otimes I)$$

where C is the coin operator (often chosen as the Hadamard gate) and S is the conditional shift operator.

This visualization shows how the **measurement probabilities** over position evolve with time, highlighting the contrast between classical diffusion and quantum interference.

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

A **quantum walk** is the quantum mechanical analog of a classical random walk. While a classical random walk describes a particle moving left or right with equal probability, a quantum walk exploits superposition and interference.

In a classical random walk, the probability distribution after $n$ steps follows a binomial distribution, converging to a Gaussian. The quantum walk, however, produces a strikingly different distribution due to quantum interference.

The evolution is governed by a unitary operator $U$ acting on the combined Hilbert space of position and coin:

$$U = S \cdot (C \otimes I)$$

where $C$ is the coin operator (often a Hadamard gate) and $S$ is the conditional shift operator.

This visualization shows how the probability distribution evolves over time, highlighting the difference between classical and quantum behavior.

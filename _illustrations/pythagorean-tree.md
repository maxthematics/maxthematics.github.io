---
title: "Dynamic Pythagorean Tree"
layout: illustration
tool: CindyJS
topics: [geometry, fractals, recursion]
thumbnail: /assets/images/illustrations/pythagorean-tree.png
applet_url: https://maxthematics.github.io/illustratingMath-cindy/dynamic_pythagoreanTree.html
applet_height: 700
source_url: https://github.com/maxthematics/illustratingMath-cindy
---

The **Pythagorean tree** is a fractal constructed from squares. Starting with a square, two smaller squares are attached to one side such that they form a right triangle with the original square's edge as hypotenuse.

The construction uses the Pythagorean theorem: if the original square has side length $c$, and the two new squares have side lengths $a$ and $b$, then:

$$a^2 + b^2 = c^2$$

This process is repeated recursively. In this interactive version, you can drag the point on the semicircle to change the angle of the triangle, affecting the ratio between $a$ and $b$.

Use the slider to control the recursion depth.

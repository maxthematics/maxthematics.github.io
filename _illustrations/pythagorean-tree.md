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

The **Pythagorean tree** is a fractal you can build entirely out of squares. Start with one square. On top of it, balance two smaller squares so that they lean together and leave a right-angled triangle in the gap between them. Then do exactly the same on top of each of those squares—and again, and again.

The whole picture is held together by the **Pythagorean theorem**. Because the triangle in every fork has a right angle, the areas of the two smaller squares always add up to the area of the larger one beneath them:

$$a^2 + b^2 = c^2$$

Here $c$ is the side length of the lower square, and $a$ and $b$ are the side lengths of the two squares growing out of it. Repeating this one rule across every branch grows a shape that looks strikingly like a leafy tree.

Drag the point on the semicircle to change the angle of the triangle: this shifts the balance between $a$ and $b$ and bends the tree to the left or right. Use the slider to control how many times the branching repeats.

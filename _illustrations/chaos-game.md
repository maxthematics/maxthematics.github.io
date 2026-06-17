---
title: "Chaos Game"
layout: illustration
tool: CindyJS
topics: [geometry, fractals, chaos]
thumbnail: /assets/images/illustrations/chaos-game.png
applet_url: https://maxthematics.github.io/illustratingMath-cindy/ChaosGame.html
applet_height: 700
source_url: https://github.com/maxthematics/illustratingMath-cindy
---

The **chaos game** turns pure randomness into perfect order. Mark the corners of a polygon, start from any point, and repeat one simple step over and over:

1. Pick one corner at random.
2. Move a fixed fraction of the way from your current spot toward that corner.
3. Mark the new spot.

In formula form, each new point lands a fraction $r$ of the way from the old point $p_k$ toward the chosen corner $v_i$:

$$p_{k+1} = (1-r)\,p_k + r\,v_i$$

Here is the surprise: even though the corner is chosen at random every time, the dots never scatter into a shapeless cloud. They always settle into the *same* intricate, repeatable pattern—a **fractal**. With a triangle and $r = \tfrac{1}{2}$, that pattern is the famous **Sierpiński triangle**.

Use the **N** slider to change the number of corners (3 to 36) and the **r** slider to set how far each step moves. It snaps to special ratios (such as $N/(N+3)$) that produce especially clean shapes. The **speed** slider controls how fast new dots appear. Toggle **COLOR** to tint each dot by the corner it jumped toward, and **GUIDE** to show or hide the corners and the current step.

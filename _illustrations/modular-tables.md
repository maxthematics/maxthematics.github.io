---
title: "Modular Arithmetic Tables"
layout: illustration
tool: CindyJS
topics: [number theory, modular arithmetic, algebra]
thumbnail: /assets/images/illustrations/modular-tables.png
applet_url: https://maxthematics.github.io/illustratingMath-cindy/modular_tables.html
applet_height: 700
source_url: https://github.com/maxthematics/illustratingMath-cindy
---

Modular arithmetic is the arithmetic of **remainders**. Fix a number $q$ and, after every calculation, keep only what is left over after dividing by $q$—so the only values that ever appear are $0, 1, \dots, q-1$. Count upward and you climb to $q-1$, then wrap straight back to $0$. Mathematicians call this working "modulo $q$":

$$a + b \pmod{q} \qquad\text{and}\qquad a \cdot b \pmod{q}$$

This applet shows the complete **times table** (or addition table) for a chosen $q$, with every cell shaded by its value—larger results are darker—so the arithmetic turns into a visual pattern. Click the symbol in the top-left corner to switch between the **addition** and **multiplication** table.

The two look very different. Addition simply shifts along by one at each step, giving tidy diagonal stripes. Multiplication is richer and reveals real number theory. When $q$ is a **prime number**, every row except the first contains each value exactly once. When $q$ is **not prime**, gaps and repeats appear—for instance two nonzero numbers can multiply together to give $0$—and the pattern of these surprises is tied to the divisors of $q$.

Use the **slider** to change $q$ from 1 to 99; the table instantly resizes and recolors, so you can flip between prime and non-prime values and watch the patterns shift.

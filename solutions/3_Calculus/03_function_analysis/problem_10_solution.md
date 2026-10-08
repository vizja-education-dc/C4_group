# Problem 10: Complete Function Analysis

## Problem Statement
Analyze $f(x)=x/(x^2+1)$ completely.

## Theoretical Background and Concepts
Combine symmetry, limits, first derivative, and second derivative into one graph description.

### How to Think About This Problem

Use a fixed checklist: domain, symmetry, zeros and signs, endpoint limits, asymptotes, first derivative, extrema, second derivative, and curvature. Put critical and excluded points on a number line before making sign charts. A sketch should be the final summary of these facts, not a guess made at the beginning.

## Detailed Step-by-Step Solution
The domain is $\mathbb R$; $f$ is odd and has zero $(0,0)$. It tends to $0$ at both infinities, so $y=0$ is horizontal asymptote. Since
$$
f'=\frac{1-x^2}{(x^2+1)^2},
$$
it increases on $(-1,1)$ and decreases outside; the minimum is $(-1,-1/2)$ and maximum $(1,1/2)$. Further,
$$
f''=\frac{2x(x^2-3)}{(x^2+1)^3}.
$$
It is concave on $(-\infty,-\sqrt3)$ and $(0,\sqrt3)$, convex on $(-\sqrt3,0)$ and $(\sqrt3,\infty)$. Inflection points are
$$
\left(-\sqrt3,-\frac{\sqrt3}{4}\right),(0,0),
\left(\sqrt3,\frac{\sqrt3}{4}\right).
$$

## Common Mistakes and Key Takeaway

Do not infer a derivative's sign merely from its zeros; test or factor each interval. Never join graph branches across an excluded domain point. The key takeaway is that every visible feature of the sketch should be supported by a calculation, and symmetry plus limiting behavior can be used to detect inconsistent results.

## Verification and Consistency Checks
All extrema and inflection data respect odd symmetry, providing a strong consistency check for the sketch.

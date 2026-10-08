# Problem 8: The Second Derivative

## Problem Statement
Find extrema, curvature intervals, and inflection points of $x^4-4x^2$.

## Theoretical Background and Concepts
$f'$ controls monotonicity and $f''$ controls concavity/convexity.

### How to Think About This Problem

Use a fixed checklist: domain, symmetry, zeros and signs, endpoint limits, asymptotes, first derivative, extrema, second derivative, and curvature. Put critical and excluded points on a number line before making sign charts. A sketch should be the final summary of these facts, not a guess made at the beginning.

## Detailed Step-by-Step Solution
$$
f'=4x(x^2-2),
$$
so local minima are $(\pm\sqrt2,-4)$ and a local maximum is $(0,0)$. Also
$$
f''=12x^2-8=0\iff x=\pm\sqrt{2/3}.
$$
The graph is convex on $(-\infty,-\sqrt{2/3})\cup(\sqrt{2/3},\infty)$ and concave on $(-\sqrt{2/3},\sqrt{2/3})$. Inflection points are
$$
\left(\pm\sqrt{\frac23},-\frac{20}{9}\right).
$$

## Common Mistakes and Key Takeaway

Do not infer a derivative's sign merely from its zeros; test or factor each interval. Never join graph branches across an excluded domain point. The key takeaway is that every visible feature of the sketch should be supported by a calculation, and symmetry plus limiting behavior can be used to detect inconsistent results.

## Verification and Consistency Checks
Sign tests for $f'$ and $f''$ confirm every transition; even symmetry makes the features mirror across the $y$-axis.

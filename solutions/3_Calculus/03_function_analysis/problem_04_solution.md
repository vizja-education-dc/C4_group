# Problem 4: Two Vertical Asymptotes

## Problem Statement
Analyze domain, asymptotes, sign, and monotonicity of $1/(x^2-1)$.

## Theoretical Background and Concepts
Disconnected domain intervals must be treated separately because a function cannot be monotone across points where it is undefined.

### How to Think About This Problem

Use a fixed checklist: domain, symmetry, zeros and signs, endpoint limits, asymptotes, first derivative, extrema, second derivative, and curvature. Put critical and excluded points on a number line before making sign charts. A sketch should be the final summary of these facts, not a guess made at the beginning.

## Detailed Step-by-Step Solution
The domain excludes $\pm1$. Vertical asymptotes are $x=\pm1$ and the horizontal asymptote is $y=0$. The function is positive for $|x|>1$ and negative for $|x|<1$. Since
$$
f'(x)=\frac{-2x}{(x^2-1)^2},
$$
it increases on $(-\infty,-1)$ and $(-1,0)$, and decreases on $(0,1)$ and $(1,\infty)$.

## Common Mistakes and Key Takeaway

Do not infer a derivative's sign merely from its zeros; test or factor each interval. Never join graph branches across an excluded domain point. The key takeaway is that every visible feature of the sketch should be supported by a calculation, and symmetry plus limiting behavior can be used to detect inconsistent results.

## Verification and Consistency Checks
The derivative denominator is positive, so its sign is exactly the sign of $-x$. One-sided infinite limits at each excluded point confirm the asymptotes.

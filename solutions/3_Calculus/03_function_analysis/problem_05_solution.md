# Problem 5: Exponential Function with a Maximum

## Problem Statement
Analyze monotonicity, extrema, and right-end behavior of $xe^{-x}$.

## Theoretical Background and Concepts
The exponential factor is positive, so the other derivative factor controls its sign.

### How to Think About This Problem

Use a fixed checklist: domain, symmetry, zeros and signs, endpoint limits, asymptotes, first derivative, extrema, second derivative, and curvature. Put critical and excluded points on a number line before making sign charts. A sketch should be the final summary of these facts, not a guess made at the beginning.

## Detailed Step-by-Step Solution
$$
f'(x)=e^{-x}(1-x).
$$
Thus $f$ increases on $(-\infty,1)$ and decreases on $(1,\infty)$, giving a global maximum
$$
f(1)=\frac1e.
$$
Furthermore, $\lim_{x\to\infty}xe^{-x}=0^+$, so the right branch approaches the $x$-axis from above.

## Common Mistakes and Key Takeaway

Do not infer a derivative's sign merely from its zeros; test or factor each interval. Never join graph branches across an excluded domain point. The key takeaway is that every visible feature of the sketch should be supported by a calculation, and symmetry plus limiting behavior can be used to detect inconsistent results.

## Verification and Consistency Checks
The derivative changes from positive to negative at $1$; exponential growth in the denominator dominates the linear numerator at $+\infty$.

# Problem 13: A Logarithm and an Asymptote

## Problem Statement
Completely analyze $f(x)=\ln x/x$ for $x>0$.

## Theoretical Background and Concepts
Domain-end limits, zeros, and derivative signs determine the essential sketch.

### How to Think About This Problem

Use a fixed checklist: domain, symmetry, zeros and signs, endpoint limits, asymptotes, first derivative, extrema, second derivative, and curvature. Put critical and excluded points on a number line before making sign charts. A sketch should be the final summary of these facts, not a guess made at the beginning.

## Detailed Step-by-Step Solution
The domain is $(0,\infty)$ and the zero is $x=1$. Limits are
$$
\lim_{x\to0^+}\frac{\ln x}{x}=-\infty,\qquad
\lim_{x\to\infty}\frac{\ln x}{x}=0^+.
$$
Thus $x=0$ is a vertical and $y=0$ a right horizontal asymptote. Since
$$
f'(x)=\frac{1-\ln x}{x^2},
$$
$f$ increases on $(0,e)$, decreases on $(e,\infty)$, and has global maximum $f(e)=1/e$.

## Common Mistakes and Key Takeaway

Do not infer a derivative's sign merely from its zeros; test or factor each interval. Never join graph branches across an excluded domain point. The key takeaway is that every visible feature of the sketch should be supported by a calculation, and symmetry plus limiting behavior can be used to detect inconsistent results.

## Verification and Consistency Checks
The sign changes at $\ln x=1$, and the zero and both end behaviors fit these monotonicity intervals.

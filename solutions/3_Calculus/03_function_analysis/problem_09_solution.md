# Problem 9: An Oblique Asymptote

## Problem Statement
Find all asymptotes using polynomial division.

## Theoretical Background and Concepts
If $f(x)=mx+b+r(x)$ with $r(x)\to0$, then $y=mx+b$ is an oblique asymptote.

### How to Think About This Problem

Use a fixed checklist: domain, symmetry, zeros and signs, endpoint limits, asymptotes, first derivative, extrema, second derivative, and curvature. Put critical and excluded points on a number line before making sign charts. A sketch should be the final summary of these facts, not a guess made at the beginning.

## Detailed Step-by-Step Solution
$$
\frac{x^2+1}{x-1}=x+1+\frac2{x-1}.
$$
Thus $x=1$ is a vertical asymptote and
$$
y=x+1
$$
is the oblique asymptote as $x\to\pm\infty$.

## Common Mistakes and Key Takeaway

Do not infer a derivative's sign merely from its zeros; test or factor each interval. Never join graph branches across an excluded domain point. The key takeaway is that every visible feature of the sketch should be supported by a calculation, and symmetry plus limiting behavior can be used to detect inconsistent results.

## Verification and Consistency Checks
$f(x)-(x+1)=2/(x-1)\to0$ for large $|x|$, which is exactly the asymptote criterion.

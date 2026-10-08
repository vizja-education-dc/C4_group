# Problem 15: Correcting a Monotonicity Analysis

## Problem Statement
Find and correct the student's derivative sign error.

## Theoretical Background and Concepts
Derivative zeros divide the line into test intervals but do not determine signs by themselves.

### How to Think About This Problem

Use a fixed checklist: domain, symmetry, zeros and signs, endpoint limits, asymptotes, first derivative, extrema, second derivative, and curvature. Put critical and excluded points on a number line before making sign charts. A sketch should be the final summary of these facts, not a guess made at the beginning.

## Detailed Step-by-Step Solution
For $f'=3(x-1)(x+1)$, test points give
$$
f'(-2)=9>0,\qquad f'(0)=-3<0,\qquad f'(2)=9>0.
$$
Thus $f$ increases on $(-\infty,-1)$, decreases on $(-1,1)$, and increases on $(1,\infty)$. It has a local maximum at
$$
(-1,f(-1))=(-1,2)
$$
and a local minimum at $(1,-2)$. The student's unsupported claim reversed every interval sign and therefore both extremum types.

## Common Mistakes and Key Takeaway

Do not infer a derivative's sign merely from its zeros; test or factor each interval. Never join graph branches across an excluded domain point. The key takeaway is that every visible feature of the sketch should be supported by a calculation, and symmetry plus limiting behavior can be used to detect inconsistent results.

## Verification and Consistency Checks
The three explicit test-point evaluations confirm the complete sign chart without differentiating again.

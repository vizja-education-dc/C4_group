# Exercise 8: Linear Combination

## Problem Statement
Determine whether $w=au+bv$ and find the coefficients.

## Theoretical Background and Concepts
Equating vector components converts a linear-combination question into a linear system.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
a+2b=5,\qquad a-b=1.
$$
Thus $3b=4$, so $b=4/3$ and $a=7/3$.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
$$
\frac73(1,1)+\frac43(2,-1)=(5,1)=w.
$$
Geometrically, $w$ lies in the span of the two nonparallel directions.

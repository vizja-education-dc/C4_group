# Exercise 5: Angle Between Vectors

## Problem Statement
Predict and compute the angle between $u$ and $v$.

## Theoretical Background and Concepts
$\cos\theta=(u\cdot v)/(\|u\|\|v\|)$; a positive dot product predicts an acute angle.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
u\cdot v=1>0,\quad \|u\|=\|v\|=\sqrt2,
\quad \cos\theta=\frac12.
$$
Therefore $\theta=\pi/3=60^\circ$, which is acute.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
The computed angle agrees with the sign-based prediction.

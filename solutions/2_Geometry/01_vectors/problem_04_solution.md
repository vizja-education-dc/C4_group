# Exercise 4: Dot Product and Perpendicularity

## Problem Statement
Test $u,v$ for perpendicularity and choose $a$ making $w\perp u$.

## Theoretical Background and Concepts
Nonzero vectors are perpendicular exactly when their dot product is zero.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
u\cdot v=1(2)+2(-1)+(-1)3=-3,
$$
so $u,v$ are not perpendicular. Also
$$
u\cdot w=2-2-a=-a,
$$
which is zero for $a=0$.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
With $w=(2,-1,0)$, $u\cdot w=2-2+0=0$.

# Exercise 11: Parallel and Perpendicular Components

## Problem Statement
Decompose $u$ relative to the direction $v$.

## Theoretical Background and Concepts
The parallel component is the projection; the remainder is perpendicular.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
u_\parallel=\frac{u\cdot v}{v\cdot v}v=\frac{11}{5}(1,2)
=\left(\frac{11}5,\frac{22}5\right),
$$
$$
u_\perp=u-u_\parallel=\left(\frac45,-\frac25\right).
$$

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
Their sum is $(3,4)$, and $u_\perp\cdot v=4/5-4/5=0$; these check reconstruction and direction independently.

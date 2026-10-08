# Exercise 12: Normal Vector to a Plane

## Problem Statement
Construct two in-plane vectors and a vector perpendicular to both.

## Theoretical Background and Concepts
The cross product of two nonparallel in-plane vectors is normal to their plane.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
\overrightarrow{AB}=(1,1,-2),\qquad \overrightarrow{AC}=(-1,3,-1),
$$
$$
n=\overrightarrow{AB}\times\overrightarrow{AC}=(5,3,4).
$$

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
$(5,3,4)\cdot(1,1,-2)=0$ and $(5,3,4)\cdot(-1,3,-1)=0$.

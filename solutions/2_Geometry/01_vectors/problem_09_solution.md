# Exercise 9: Cross Product

## Problem Statement
Compute both cross-product orders and verify perpendicularity.

## Theoretical Background and Concepts
$u\times v$ is perpendicular to both factors and $v\times u=-(u\times v)$.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
u\times v=(6,-3,1),\qquad v\times u=(-6,3,-1).
$$

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
$$
(6,-3,1)\cdot(1,2,0)=0,\qquad
(6,-3,1)\cdot(0,1,3)=0,
$$
and the reversed product is the negative, as required.

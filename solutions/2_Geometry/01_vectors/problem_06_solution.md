# Exercise 6: Projection and Perpendicular Component

## Problem Statement
Project $u$ onto $v$ and verify the remainder is perpendicular.

## Theoretical Background and Concepts
$\operatorname{proj}_v u=((u\cdot v)/(v\cdot v))v$.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
\operatorname{proj}_v u=\frac6{2}(1,1)=(3,3),\qquad
r=(4,2)-(3,3)=(1,-1).
$$

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
$r\cdot v=1-1=0$. Thus $u$ is decomposed into a component parallel to $v$ and an orthogonal remainder.

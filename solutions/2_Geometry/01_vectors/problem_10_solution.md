# Exercise 10: Triangle Area

## Problem Statement
Use a cross product to find parallelogram and triangle areas.

## Theoretical Background and Concepts
$\|u\times v\|$ is the parallelogram area; a diagonal divides it into two congruent triangles.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
\overrightarrow{AB}=(2,1,0),\quad \overrightarrow{AC}=(1,3,2),
$$
$$
\overrightarrow{AB}\times\overrightarrow{AC}=(2,-4,5).
$$
The parallelogram area is $\sqrt{4+16+25}=3\sqrt5$, so the triangle area is $3\sqrt5/2$.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
The factor $1/2$ is justified because two copies of the triangle form the parallelogram.

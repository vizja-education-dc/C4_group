# Exercise 2: Distance as Vector Length

## Problem Statement
Construct $\overrightarrow{AB}$ and compute the distance in two ways.

## Theoretical Background and Concepts
$\overrightarrow{AB}=B-A$, and point distance is the Euclidean norm of this displacement.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
\overrightarrow{AB}=(3,-4,3),\qquad
\|\overrightarrow{AB}\|=\sqrt{3^2+(-4)^2+3^2}=\sqrt{34}.
$$
The coordinate distance formula gives the same expression.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
Both methods use the identical coordinate differences $4-1,-2-2,6-3$, hence must agree.

# Exercise 15: Comparing Directions

## Problem Statement
Compute pairwise angle cosines and order the angles.

## Theoretical Background and Concepts
For nonzero vectors, $\cos\theta=(u\cdot v)/(\|u\|\|v\|)$; cosine decreases as $\theta$ increases on $[0,\pi]$.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
\cos(a,b)=1,\qquad
\cos(a,c)=\frac5{\sqrt{78}},\qquad
\cos(b,c)=\frac5{\sqrt{78}}.
$$
Therefore
$$
\angle(a,b)<\angle(a,c)=\angle(b,c).
$$

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
Since $b=2a$, $a,b$ have exactly the same orientation despite different lengths, explaining cosine $1$.

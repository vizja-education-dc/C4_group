# Exercise 13: Coplanarity of Four Points

## Problem Statement
Use a normal vector and scalar product to test whether $D$ lies in plane $ABC$.

## Theoretical Background and Concepts
A displacement lies in a plane precisely when it is perpendicular to a normal of that plane.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
\overrightarrow{AB}=(1,2,0),\quad \overrightarrow{AC}=(0,1,1),
\quad n=(2,-1,1).
$$
Also $\overrightarrow{AD}=(2,5,1)$, and
$$
\overrightarrow{AD}\cdot n=4-5+1=0.
$$
Thus $D$ lies in the plane through $A,B,C$.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
Indeed $\overrightarrow{AD}=2\overrightarrow{AB}+\overrightarrow{AC}$, an explicit in-plane combination.

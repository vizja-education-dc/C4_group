# Exercise 14: Closest Point on a Line

## Problem Statement
Project $P$ onto the line, find the distance, and verify perpendicularity.

## Theoretical Background and Concepts
For a line through the origin, the closest point is the orthogonal projection onto its direction.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
Q=\operatorname{proj}_vP=\frac{P\cdot v}{v\cdot v}v
=\frac65(1,2)=\left(\frac65,\frac{12}5\right).
$$
$$
P-Q=\left(\frac{14}5,-\frac75\right),\qquad
d(P,L)=\|P-Q\|=\frac{7\sqrt5}{5}.
$$

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
$(P-Q)\cdot v=14/5-14/5=0$, proving the joining segment is perpendicular and hence shortest.

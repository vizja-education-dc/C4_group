# Exercise 10: Projection onto a Plane

## Problem Statement
Find the orthogonal projection and reflection of $P$.

## Theoretical Background and Concepts
For $n\cdot x=d$, projection is $Q=P-\frac{n\cdot P-d}{\|n\|^2}n$; reflection is $P'=2Q-P$.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
With $n=(1,1,1)$, $n\cdot P-d=3$, and $\|n\|^2=3$,
$$
Q=(2,1,3)-(1,1,1)=(1,0,2).
$$
Thus
$$
P'=2Q-P=(0,-1,1).
$$

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
$Q$ has coordinate sum $3$, and $(P+P')/2=Q$, so the midpoint lies on the plane.

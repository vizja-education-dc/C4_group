# Exercise 13: Closest Point on a Plane

## Problem Statement
Project $P$ onto the plane and find the distance.

## Theoretical Background and Concepts
The closest segment follows the plane's normal vector.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
For $n=(1,2,2)$, $n\cdot P-4=-1$, $\|n\|^2=9$. Thus
$$
Q=P-\frac{-1}{9}n=\left(\frac{28}9,\frac29,\frac29\right),
\qquad d(P,\Pi)=\frac{|-1|}{3}=\frac13.
$$

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
$Q$ satisfies $x+2y+2z=4$, and $Q-P=\frac19n$ is perpendicular to the plane.

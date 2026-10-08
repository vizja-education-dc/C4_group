# Exercise 12: Intersection of Two Planes

## Problem Statement
Parametrize the intersection and find its direction in two ways.

## Theoretical Background and Concepts
Solving both equations leaves one free parameter; the cross product of plane normals is parallel to their intersection.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
Subtracting equations gives $2y=2$, so $y=1$, while $x+z=2$. Let $z=t$:
$$
(x,y,z)=(2,1,0)+t(-1,0,1).
$$
Also
$$
(1,1,1)\times(1,-1,1)=(2,0,-2),
$$
which is parallel to $(-1,0,1)$.

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
Substitution of the parametric point satisfies both plane equations for every $t$.

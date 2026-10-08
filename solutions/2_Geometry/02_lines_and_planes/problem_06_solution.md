# Exercise 6: Angle Between Planes

## Problem Statement
Determine parallelism and the angle between the planes.

## Theoretical Background and Concepts
The angle between planes is the acute angle between their normal vectors.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
$$
n_1=(1,1,1),\qquad n_2=(1,-1,0).
$$
They are not proportional, so the planes are not parallel. Moreover,
$$
n_1\cdot n_2=1-1+0=0,
$$
so the angle is $90^\circ$.

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
Perpendicular normals give perpendicular planes; only normal directions are needed because they determine plane orientation.

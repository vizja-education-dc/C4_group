# Exercise 5: Relative Position of Two Lines

## Problem Statement
Classify the two spatial lines and find an intersection if one exists.

## Theoretical Background and Concepts
Nonparallel lines in space may intersect or be skew; intersection requires one pair of parameters satisfying all three coordinates.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
The direction vectors $(1,2,1)$ and $(0,1,-1)$ are not proportional. Equality of $x$-coordinates forces $t=1$; equality of $y$-coordinates then forces $s=3$. But the $z$-coordinates are $1$ and $1-3=-2$, not equal.
Therefore the lines are skew.

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
They are neither parallel (directions not proportional) nor intersecting (the coordinate system is inconsistent), exhausting the possibilities.

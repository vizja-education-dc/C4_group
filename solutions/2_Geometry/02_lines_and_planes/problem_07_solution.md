# Exercise 7: A Line Relative to a Plane

## Problem Statement
Classify the line relative to the plane.

## Theoretical Background and Concepts
If $v\cdot n=0$, a line is parallel to the plane; it is contained when one of its points also lies in the plane.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
Here $v=(1,-1,0)$, $n=(1,1,1)$, and $v\cdot n=0$. The base point satisfies $1+1+0=2$, so it lies in $\Pi$. Hence the entire line lies in the plane.

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
For every $t$, $(1+t)+(1-t)+0=2$, directly verifying containment.

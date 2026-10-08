# Exercise 14: Intersection and Parallelism

## Problem Statement
Classify two lines through $P$ relative to $z=0$.

## Theoretical Background and Concepts
A line intersects when its direction has nonzero normal component; it is parallel when that component is zero.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
For $v_1=(2,1,-1)$, the line is $(2t,t,1-t)$; setting $z=0$ gives $t=1$, hence intersection $(2,1,0)$.
For $v_2=(2,1,0)$, every point has $z=1$, so the line is parallel to and distinct from the plane.

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
The plane normal is $(0,0,1)$: its dot products with $v_1,v_2$ are $-1$ and $0$, respectively.

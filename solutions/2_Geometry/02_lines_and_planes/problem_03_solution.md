# Exercise 3: Plane from Point and Normal

## Problem Statement
Find the plane through $P$ normal to $n$.

## Theoretical Background and Concepts
A plane through $P$ with normal $n$ satisfies $n\cdot(x-P)=0$.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
$$
2(x-1)+(y+2)-(z-3)=0,
$$
or
$$
2x+y-z+3=0.
$$

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
At $P=(1,-2,3)$, the left side is $2-2-3+3=0$. Coefficients $(2,1,-1)$ equal the specified normal.

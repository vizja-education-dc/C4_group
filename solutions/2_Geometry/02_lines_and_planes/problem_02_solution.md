# Exercise 2: A Line in Space

## Problem Statement
Read the line data, test $P$, and evaluate the point at $t=-1$.

## Theoretical Background and Concepts
In $p+tv$, $p$ is a point and $v$ the direction; one common parameter must satisfy all coordinates.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
A point is $(2,-1,3)$ and the direction is $(1,2,-2)$. For $P=(4,3,-1)$, the first coordinate gives $t=2$; the other coordinates then give $3$ and $-1$, so $P\in L$. At $t=-1$, the point is
$$
(1,-3,5).
$$

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
Substitution of $t=2$ and $t=-1$ reproduces all listed coordinates.

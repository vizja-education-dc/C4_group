# Exercise 1: Line Through Two Points

## Problem Statement
Find parametric and general equations through $A,B$, identify direction and normal vectors, and check both points.

## Theoretical Background and Concepts
A line is $A+t(B-A)$; a normal vector is perpendicular to its direction.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
$$
d=B-A=(3,-3)\sim(1,-1).
$$
Thus
$$
(x,y)=(1,2)+t(1,-1).
$$
A normal is $n=(1,1)$, yielding the general equation $x+y-3=0$.

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
Both $1+2-3=0$ and $4-1-3=0$; also $n\cdot d=0$.

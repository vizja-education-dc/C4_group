# Exercise 11: Plane Containing a Line and Point

## Problem Statement
Construct the plane containing the given line and external point.

## Theoretical Background and Concepts
Two independent directions in the plane determine a normal via their cross product.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
From line point $Q=(1,0,2)$, use
$$
d=(1,1,-1),\qquad P-Q=(-1,2,-1).
$$
Their cross product is $n=(1,2,3)$. Hence
$$
n\cdot((x,y,z)-Q)=0
\quad\Longrightarrow\quad x+2y+3z=7.
$$

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
$P$ gives $7$, and a general line point gives $(1+t)+2t+3(2-t)=7$, independent of $t$.

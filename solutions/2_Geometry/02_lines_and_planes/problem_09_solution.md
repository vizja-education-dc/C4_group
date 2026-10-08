# Exercise 9: Distances

## Problem Statement
Find a point-to-line distance and a point-to-plane distance.

## Theoretical Background and Concepts
For $a\cdot x+d=0$, distance equals the absolute equation value divided by the norm of the normal.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
$$
d(P,L)=\frac{|3(2)+4(3)-10|}{\sqrt{3^2+4^2}}=\frac85,
$$
$$
d(Q,\Pi)=\frac{|2(2)-2(-1)+3-4|}{\sqrt{2^2+(-2)^2+1^2}}=\frac53.
$$

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
Both formulas measure the signed normal component and then take its magnitude, explaining their identical structure.

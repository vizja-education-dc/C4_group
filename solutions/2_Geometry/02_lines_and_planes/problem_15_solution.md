# Exercise 15: Complete Line–Plane Classification

## Problem Statement
State general criteria and illustrate all three cases.

## Theoretical Background and Concepts
Substitution gives $n\cdot(p+tv)=n\cdot p+t(n\cdot v)=d$.

### How to Think About This Problem

Identify the geometric data before manipulating equations: a line needs a point and direction, while a plane needs a point and normal. Relative-position questions become dot-product or consistency tests. For intersections, substitute the parametric object into the implicit equation and solve for a common parameter; for distances and projections, move only in the normal direction.

## Detailed Step-by-Step Solution
- If $n\cdot v\ne0$, there is one intersection, with $t=(d-n\cdot p)/(n\cdot v)$.
- If $n\cdot v=0$ and $n\cdot p\ne d$, the line is parallel and disjoint.
- If $n\cdot v=0$ and $n\cdot p=d$, the line is contained.

For $\Pi:z=0$: $(0,0,1)+t(0,0,-1)$ illustrates one intersection; $(0,0,1)+t(1,0,0)$ is parallel; $(0,0,0)+t(1,0,0)$ is contained.

## Common Mistakes and Key Takeaway

Do not confuse a plane normal with a direction lying in the plane. In three dimensions, nonparallel lines need not intersect—they may be skew. The key check is substitution: put the final point, line, or plane data back into every original description and confirm all equations simultaneously.

## Verification and Consistency Checks
The $z$-coordinates are respectively $1-t$, $1$, and $0$, which directly confirm all classifications.

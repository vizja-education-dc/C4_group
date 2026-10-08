# Exercise 1: Vector Operations

## Problem Statement
Compute the three vector expressions, verify an identity, and interpret addition.

## Theoretical Background and Concepts
Vector operations are performed componentwise; geometrically, addition is the tip-to-tail/parallelogram rule.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
u+v=(1,3,5),\quad u-v=(3,-5,1),\quad3u-2v=(8,-11,5).
$$

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
$(u+v)-v=(1,3,5)-(-1,4,2)=(2,-1,3)=u$.

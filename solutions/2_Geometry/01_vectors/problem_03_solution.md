# Exercise 3: Vector Normalization

## Problem Statement
Normalize $v=(3,4)$, verify unit length, and reconstruct $v$.

## Theoretical Background and Concepts
A nonzero vector's unit direction is $e=v/\|v\|$.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
\|v\|=5,\qquad e=\left(\frac35,\frac45\right).
$$
Normalization changes length to $1$ but preserves direction and orientation.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
$$
\|e\|=\sqrt{9/25+16/25}=1,\qquad \|v\|e=5e=(3,4)=v.
$$

# Exercise 7: Linear Dependence

## Problem Statement
Recognize a dependence relation without lengthy computation.

## Theoretical Background and Concepts
A set containing one vector that is a scalar multiple of another is linearly dependent.

### How to Think About This Problem

Separate the computation from its geometric meaning. Component formulas tell you how to calculate, while dot products, cross products, and projections tell you about angles, perpendicularity, areas, and closest points. Draw or imagine the directions first; this often predicts whether a result should be positive, negative, parallel, or perpendicular.

## Detailed Step-by-Step Solution
$$
v=2u.
$$
Hence $2u-v+0w=0$ is a nontrivial linear relation, so $u,v,w$ cannot be linearly independent.

## Common Mistakes and Key Takeaway

Typical mistakes include forgetting to divide by $v\cdot v$ in a projection, confusing $u\times v$ with $v\times u$, and treating points as vectors without forming a displacement. Verify geometric claims algebraically: perpendicular vectors have dot product zero, unit vectors have norm one, and decomposed components must add back to the original vector.

## Verification and Consistency Checks
Twice each component of $u=(1,2,3)$ gives $v=(2,4,6)$.

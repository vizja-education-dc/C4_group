# Exercise 12: Homogeneous System

## Problem Statement
Solve the homogeneous system parametrically.

## Theoretical Background and Concepts
A homogeneous system always contains the zero solution; free variables may create nonzero solutions.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
The second equation duplicates the first. From the first, $x=-2y+z$. In the third,
$$
(-2y+z)-y+2z=0\implies z=y.
$$
Let $y=t$; then
$$
(x,y,z)=(-t,t,t)=t(-1,1,1).
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
Substitution gives zero in every equation. Setting $t=0$ confirms the always-present trivial solution.

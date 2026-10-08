# Exercise 11: Parameter in Three Equations

## Problem Statement
Classify the number of solutions depending on $t$.

## Theoretical Background and Concepts
Parameter values that make an elimination pivot zero must be examined separately.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
Subtract equation 1 from equations 2 and 3:
$$
(t-1)y=1,\qquad(t-1)z=2.
$$
If $t\ne1$,
$$
y=\frac1{t-1},\quad z=\frac2{t-1},\quad
x=1-y-z=\frac{t-4}{t-1},
$$
so the solution is unique. If $t=1$, elimination yields $0=1$ and $0=2$, so there is no solution.

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
Substituting the formulas into the original equations verifies them; no parameter value gives infinitely many solutions.

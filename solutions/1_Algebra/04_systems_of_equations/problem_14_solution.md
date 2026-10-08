# Exercise 14: A Small Right-Hand-Side Change

## Problem Statement
Compare the consistency of two nearly identical systems.

## Theoretical Background and Concepts
An overdetermined system is consistent only if every equation agrees with the solution forced by the others.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
The first two equations give $3x=3$, hence $x=1,y=1$. In the first system the third equation is $3x=3$, so it is satisfied and the unique solution is $(1,1)$. In the second, the third equation requires $3x=3.1$, contradicting $x=1$; it has no solution.

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
The first two equations themselves imply the third left side equals $3$, proving both the consistency of the first and contradiction in the second.

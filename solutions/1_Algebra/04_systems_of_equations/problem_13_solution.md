# Exercise 13: Redundant Information

## Problem Statement
Solve the system and determine whether every equation is independent.

## Theoretical Background and Concepts
An equation is redundant if it is a linear combination of the others.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
Let $x_2=t$. The first two equations give
$$
x_1=10-t,\qquad x_3=8-t.
$$
Then $x_1-x_3=(10-t)-(8-t)=2$, so the third equation follows from the first minus the second. All solutions are
$$
(x_1,x_2,x_3)=(10-t,t,8-t).
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
Substitution satisfies all equations for every real $t$; removing the third does not change the solution set.

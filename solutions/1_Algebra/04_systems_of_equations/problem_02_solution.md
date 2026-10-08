# Exercise 2: Gaussian Elimination

## Problem Statement
Solve the system by elimination and check all equations.

## Theoretical Background and Concepts
Elementary row operations preserve the solution set.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
Subtracting $2R_1$ from $R_2$ and $R_1$ from $R_3$ gives
$$
\begin{cases}-3y-z=-9,\\y-2z=-4.\end{cases}
$$
Thus $3y+z=9$, so $z=9-3y$. Substitution gives $7y=14$, hence
$$
(x,y,z)=(1,2,3).
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
The three left sides are $6,3,2$, exactly the three right sides.

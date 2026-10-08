# Exercise 8: Two Systems with One Coefficient Matrix

## Problem Statement
Solve both systems by elimination and compare the steps.

## Theoretical Background and Concepts
The elimination multipliers depend on the coefficient matrix, not the right-hand side.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
For both systems, substitute $x=y+\text{(second RHS)}$. The first gives
$$
(x,y)=(2,1),
$$
and the second gives
$$
(x,y)=\left(\frac53,-\frac73\right).
$$
Equivalently, the same operation $R_1\leftarrow R_1-2R_2$ eliminates $x$ in both augmented matrices; only the updated right side differs.

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
Direct substitution gives $(5,1)$ as the two left sides in the first system and $(1,4)$ in the second.

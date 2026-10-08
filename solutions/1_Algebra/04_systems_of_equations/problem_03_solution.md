# Exercise 3: Inconsistent System

## Problem Statement
Show by elimination that the system has no solution.

## Theoretical Background and Concepts
A row $[0\ 0\mid c]$ with $c\ne0$ represents the contradiction $0=c$.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
$$
\left[\begin{array}{cc|c}1&2&3\\2&4&7\end{array}\right]
\xrightarrow{R_2-2R_1}
\left[\begin{array}{cc|c}1&2&3\\0&0&1\end{array}\right].
$$
The second row says $0=1$, so there is no solution.

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
Twice the first left side equals the second left side, but twice $3$ is $6$, not $7$.

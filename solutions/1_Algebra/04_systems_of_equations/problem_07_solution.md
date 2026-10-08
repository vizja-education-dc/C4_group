# Exercise 7: Choosing a Method

## Problem Statement
Choose methods suited to three different system structures.

## Theoretical Background and Concepts
Back-substitution exploits triangular form; a known inverse is reusable across right-hand sides; elimination avoids computing an unnecessary inverse.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
1. Back-substitution: $4y=8$ gives $y=2$, then $2x-y=3$ gives $x=5/2$.
2. For the three systems, compute $x_i=A^{-1}b_i$. The already-known $A^{-1}$ is reused for every right-hand side.
3. For one $3\times3$ system, row-reduce $[A\mid b]$. Computing all of $A^{-1}$ would solve three basis right-hand sides and is unnecessary.

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
For case 1, $4(2)=8$ and $2(5/2)-2=3$.

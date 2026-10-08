# Exercise 1: From a System to a Matrix

## Problem Statement
Write the given system as $Ax=b$.

## Theoretical Background and Concepts
Each equation supplies one row of coefficients and one component of the right-hand side.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
$$
\underbrace{\begin{pmatrix}2&-1&1\\1&3&-2\\3&1&1\end{pmatrix}}_A
\underbrace{\begin{pmatrix}x\\y\\z\end{pmatrix}}_{\mathbf x}
=
\underbrace{\begin{pmatrix}4\\1\\7\end{pmatrix}}_b.
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
Multiplying each row of $A$ by $(x,y,z)^T$ reproduces the corresponding original equation.

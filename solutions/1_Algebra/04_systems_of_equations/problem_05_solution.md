# Exercise 5: Reading Row Echelon Form

## Problem Statement
Determine and parametrize the solutions of the augmented matrix.

## Theoretical Background and Concepts
Pivot variables are determined by free variables; a zero row adds no restriction.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
The equations are $x+2y-z=3$ and $y+2z=1$. Let $z=t$. Then
$$
y=1-2t,\qquad x=3-2(1-2t)+t=1+5t.
$$
Hence
$$
(x,y,z)=(1+5t,1-2t,t),\quad t\in\mathbb R.
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
Substitution makes the two nonzero rows equal $3$ and $1$; one free variable agrees with three variables minus two pivots.

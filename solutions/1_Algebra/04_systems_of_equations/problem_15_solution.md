# Exercise 15: Classifying Three Systems

## Problem Statement
Use minimal elimination to classify the three systems.

## Theoretical Background and Concepts
A pivot in every variable gives one solution; $0=0$ with a free variable gives infinitely many; $0=c\ne0$ gives none.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
1. Adding the equations gives $2x=2$, so $(x,y)=(1,1)$: one solution.
2. Subtracting twice row 1 from row 2 gives $0=0$: infinitely many solutions $(t,2-t)$.
3. The same operation gives $0=1$: no solution.

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
The classifications correspond respectively to two intersecting lines, coincident lines, and distinct parallel lines.

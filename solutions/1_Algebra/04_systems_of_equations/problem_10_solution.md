# Exercise 10: A Polynomial Through Three Points

## Problem Statement
Determine $p(x)=ax^2+bx+c$ through the three given points.

## Theoretical Background and Concepts
Substituting each point creates a linear equation in the unknown coefficients.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
The points give
$$
c=1,\qquad a+b+c=3,\qquad4a+2b+c=9.
$$
Thus $a+b=2$ and $2a+b=4$, giving $a=2,b=0,c=1$. Therefore
$$
p(x)=2x^2+1.
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
$p(0)=1,p(1)=3,p(2)=9$, so all three points lie on the graph.

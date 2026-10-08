# Exercise 4: Infinitely Many Solutions

## Problem Statement
Find a parametric solution and check one member.

## Theoretical Background and Concepts
A variable without a pivot is free; assigning a parameter describes all solutions.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
The second equation duplicates the first. Subtracting the third from the first gives $2y=2$, so $y=1$ and $x+z=1$. Let $x=t$. Then
$$
(x,y,z)=(t,1,1-t),\qquad t\in\mathbb R.
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
For $t=0$, $(0,1,1)$ gives left sides $2,4,0$, matching the system.

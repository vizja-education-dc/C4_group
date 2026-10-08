# Exercise 9: A System from a Sum Condition

## Problem Statement
Find $x,y$ and explain uniqueness geometrically.

## Theoretical Background and Concepts
Two nonparallel lines in the plane meet in exactly one point.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
From $x=10-y$,
$$
2(10-y)+5y=32\implies3y=12\implies y=4,\quad x=6.
$$

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
$6+4=10$ and $2(6)+5(4)=32$. The line slopes $-1$ and $-2/5$ differ, so the intersection is unique.

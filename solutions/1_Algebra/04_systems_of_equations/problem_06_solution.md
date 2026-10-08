# Exercise 6: A System with a Parameter

## Problem Statement
Classify the system for every $a$.

## Theoretical Background and Concepts
Equations with proportional left sides are consistent only when their right sides have the same proportion.

### How to Think About This Problem

Translate the equations into an augmented matrix while preserving variable order. Use reversible row operations to create pivots and zeros, then read the result from the bottom upward. Watch for the three decisive row patterns: a pivot for every variable, a zero row that leaves a free variable, or a contradiction of the form $0=c$ with $c\ne0$.

## Detailed Step-by-Step Solution
The first equation implies $a(x+y)=2a$, while the second demands $a(x+y)=4$. These agree only when $2a=4$, i.e. $a=2$. Thus:
$$
a=2:\ \text{infinitely many solutions }(x,y)=(t,2-t);
$$
$$
a\ne2:\ \text{no solution}.
$$
Exactly one solution never occurs.

## Common Mistakes and Key Takeaway

A common mistake is to divide by an expression containing a parameter without first considering when it is zero. Another is to stop after obtaining a candidate solution without substituting it back. The key takeaway is that elimination does more than find numbers: it also reveals whether the system has one, infinitely many, or no solutions.

## Verification and Consistency Checks
At $a=2$, the second equation is twice the first. For all other $a$, the two required sums conflict (including $a=0$, where $0=4$).

# Exercise 14: A System and the Determinant

## Problem Statement
Classify $Ax=b$ by $k$, and give examples at the exceptional value.

## Theoretical Background and Concepts
$Ax=b$ has exactly one solution for every $b$ iff $A$ is invertible.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det A=4-2k.
$$
Thus uniqueness for every $b$ occurs when $k\ne2$. At $k=2$, row 2 is twice row 1. For $b=(1,2)^T$, the system has infinitely many solutions; for $b=(1,0)^T$, it has none.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
In the first example the second equation duplicates the first; in the second it contradicts twice the first equation.

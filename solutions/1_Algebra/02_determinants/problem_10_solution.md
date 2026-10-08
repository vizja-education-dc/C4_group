# Exercise 10: Detecting Dependence

## Problem Statement
Explain structurally why the given determinant is zero.

## Theoretical Background and Concepts
A matrix with linearly dependent rows has determinant zero and is noninvertible.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
The second row is exactly twice the first:
$$
(2,4,6)=2(1,2,3).
$$
Thus $R_2-2R_1=0$, so the rows are dependent and the determinant is $0$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
Row reduction produces a zero row, so the matrix cannot have a pivot in every row and cannot be invertible.

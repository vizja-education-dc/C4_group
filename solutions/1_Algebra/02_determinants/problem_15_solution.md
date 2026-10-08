# Exercise 15: Combining Determinant Properties

## Problem Statement
Compute $\det(B^{-1}A^TB)$ from the given determinant data.

## Theoretical Background and Concepts
Determinants multiply over products, satisfy $\det A^T=\det A$, and invert under matrix inversion.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det(B^{-1}A^TB)
=\det(B^{-1})\det(A^T)\det B
=\frac13(-2)(3)=-2.
$$

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
The $B$-factors cancel because $\det(B^{-1})\det B=1$, leaving $\det A=-2$.

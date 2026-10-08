# Exercise 7: Determinant Properties

## Problem Statement
Given a $3\times3$ matrix with $\det A=-4$, evaluate four related determinants.

## Theoretical Background and Concepts
For $n\times n$ matrices, $\det(cA)=c^n\det A$, $\det A^T=\det A$, and $\det(AB)=\det A\det B$.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det(2A)=2^3(-4)=-32,\quad \det(A^T)=-4,
$$
$$
\det(A^2)=(-4)^2=16,\quad \det(-A)=(-1)^3(-4)=4.
$$

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
The exponents $3$ occur because multiplying the whole matrix scales all three rows.

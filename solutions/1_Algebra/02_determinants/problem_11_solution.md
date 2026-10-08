# Exercise 11: Shortening a Determinant Calculation

## Problem Statement
Create zeros by row operations and compute the determinant.

## Theoretical Background and Concepts
Replacing a row by itself plus a multiple of another row preserves the determinant.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
Apply $R_2\leftarrow R_2-R_1$, $R_3\leftarrow R_3-R_1$, then $R_3\leftarrow R_3-2R_2$:
$$
\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix}.
$$
Therefore $\det A=1$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
No row was swapped or scaled, and the triangular diagonal product is $1\cdot1\cdot1=1$.

# Exercise 13: Determinant by Elimination

## Problem Statement
Compute the determinant while recording every row-operation effect.

## Theoretical Background and Concepts
Row additions leave determinants unchanged; a triangular determinant is its diagonal product.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
Use $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:
$$
\begin{pmatrix}1&2&3\\0&1&1\\0&-2&-1\end{pmatrix}.
$$
Then $R_3\leftarrow R_3+2R_2$ gives diagonal $1,1,1$. Thus $\det A=1$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
Every operation used was determinant-preserving, so the diagonal product needs no adjustment.

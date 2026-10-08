# Exercise 5: Row Operations

## Problem Statement
Find $\det A$ by determinant-preserving row reduction.

## Theoretical Background and Concepts
Adding a multiple of one row to another leaves the determinant unchanged.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
Use $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3+R_1$:
$$
\begin{pmatrix}1&2&3\\0&-3&-6\\0&6&5\end{pmatrix}.
$$
Then $R_3\leftarrow R_3+2R_2$ gives
$\begin{pmatrix}1&2&3\\0&-3&-6\\0&0&-7\end{pmatrix}$.
Thus $\det A=1(-3)(-7)=21$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
All three operations are row additions, so no correction factor is required; direct expansion gives $2-8+27=21$.

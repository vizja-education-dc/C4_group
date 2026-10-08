# Exercise 12: A Parameter Revealed by a Row Operation

## Problem Statement
Determine when $A(t)$ is singular and interpret the exceptional case.

## Theoretical Background and Concepts
Row addition preserves determinant and can reveal row dependence.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
After $R_2\leftarrow R_2-2R_1$,
$$
\begin{pmatrix}1&2&3\\0&0&t-6\\0&1&1\end{pmatrix}.
$$
Expansion along row 2 gives $\det A=6-t$. Hence the matrix is noninvertible exactly for $t=6$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
At $t=6$, the original second row is twice the first, directly confirming singularity.

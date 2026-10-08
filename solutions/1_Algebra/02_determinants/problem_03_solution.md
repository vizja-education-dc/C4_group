# Exercise 3: Swapping Two Rows

## Problem Statement
Compute $\det A$, predict the determinant after swapping rows 1 and 2, and verify.

## Theoretical Background and Concepts
Interchanging two rows multiplies a determinant by $-1$.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det A=1(3-1)-2(0-2)=6.
$$
Therefore the row-swapped matrix $B$ must satisfy $\det B=-6$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
For $B=\begin{pmatrix}0&3&1\\1&2&0\\2&1&1\end{pmatrix}$, expansion along row 1 gives
$-3(1)+1(1-4)=-6$, as predicted.

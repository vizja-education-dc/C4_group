# Exercise 1: Determinants of $2\times2$ Matrices

## Problem Statement
Compute both determinants and identify the invertible matrix.

## Theoretical Background and Concepts
For $\begin{pmatrix}a&b\\c&d\end{pmatrix}$, the determinant is $ad-bc$; the matrix is invertible exactly when this is nonzero.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det\begin{pmatrix}3&-2\\5&4\end{pmatrix}=3(4)-(-2)(5)=22,
\quad
\det\begin{pmatrix}1&7\\2&14\end{pmatrix}=14-14=0.
$$
Thus only the first matrix is invertible.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
The second row of the second matrix is twice the first, independently confirming determinant zero.

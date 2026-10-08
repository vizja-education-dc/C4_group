# Exercise 9: Area and the Determinant

## Problem Statement
Find the parallelogram area and examine what happens when the vectors are reversed.

## Theoretical Background and Concepts
For planar vectors used as columns, the signed area is their determinant and geometric area is its absolute value.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det[u\ v]=\det\begin{pmatrix}3&1\\1&4\end{pmatrix}=12-1=11.
$$
Thus the area is $11$. Reversing the columns changes the determinant to $-11$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
The absolute value remains $11$, so orientation changes but geometric area does not.

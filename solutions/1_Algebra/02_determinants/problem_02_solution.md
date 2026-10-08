# Exercise 2: Determinant of a $3\times3$ Matrix

## Problem Statement
Compute $\det A$ using Sarrus' rule and check it.

## Theoretical Background and Concepts
Sarrus' rule sums the three downward diagonal products and subtracts the three upward products.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det A=(15+16+0)-(-6+4+0)=31-(-2)=33.
$$

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
Expansion along column 1 gives
$$
1(15-4)+2\det\begin{pmatrix}2&-1\\3&4\end{pmatrix}=11+2(11)=33,
$$
confirming the result.

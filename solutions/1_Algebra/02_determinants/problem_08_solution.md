# Exercise 8: Determinant of a Product

## Problem Statement
Use $\det A=3$ and $\det B=-5$ to evaluate the requested products.

## Theoretical Background and Concepts
$\det(AB)=\det A\det B$ and $\det(A^{-1})=1/\det A$.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det(AB)=\det(BA)=3(-5)=-15,
$$
$$
\det(A^{-1}B)=\frac{1}{3}(-5)=-\frac53.
$$
The inverse exists because $\det A\ne0$.

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
Both orders yield the same scalar product $3(-5)$, even though the product matrices need not be equal.

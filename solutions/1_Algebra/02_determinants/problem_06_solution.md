# Exercise 6: Parameter and Invertibility

## Problem Statement
Find all $t$ for which $A(t)$ is not invertible.

## Theoretical Background and Concepts
A square matrix is singular exactly when its determinant is zero.

### How to Think About This Problem

Before expanding a determinant, inspect the matrix. A triangular form, proportional rows, or easy row operations can make the calculation much shorter. When using elimination, record beside every operation whether the determinant stays unchanged, changes sign, or is multiplied by a number. This bookkeeping is part of the solution, not an optional detail.

## Detailed Step-by-Step Solution
$$
\det A(t)=t^2-2.
$$
Therefore $A(t)$ is not invertible for
$$
t=\pm\sqrt2.
$$

## Common Mistakes and Key Takeaway

The most common errors are losing a minus sign in cofactor expansion and forgetting the effect of a row swap or row scaling. Remember that the determinant is a signed scale factor: zero means collapse and noninvertibility, while its absolute value gives area or volume scaling. A second calculation or structural observation is an excellent check.

## Verification and Consistency Checks
Substituting either excluded value gives $t^2-2=0$; every other real $t$ gives a nonzero determinant.

# Exercise 15: Two Methods for One System

## Problem Statement
Solve $Ax=b$ by inversion and elimination, then compare.

## Theoretical Background and Concepts
Both methods perform equivalent reversible operations when $A$ is invertible.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
Since $A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}$,
$$
x=A^{-1}b=\frac15\binom{21-8}{-7+16}=\binom{13/5}{9/5}.
$$
For elimination, $2x+y=7$, $x+3y=8$. Replacing the first equation by $3(2x+y)-(x+3y)$ gives $5x=13$; then $y=7-2x=9/5$.

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
Substitution gives $2(13/5)+9/5=7$ and $13/5+3(9/5)=8$. Elimination is slightly shorter here because computing a reusable inverse is unnecessary.

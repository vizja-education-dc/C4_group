# Exercise 3: When the Inverse Does Not Exist

## Problem Statement
Give determinant and row-dependence arguments for noninvertibility.

## Theoretical Background and Concepts
A square matrix is invertible iff its determinant is nonzero, equivalently iff its rows are independent.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
\det A=2(2)-4(1)=0.
$$
Also, the first row $(2,4)$ is twice the second row $(1,2)$. Thus the rows are dependent.

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
Both criteria independently show that $A^{-1}$ cannot exist.

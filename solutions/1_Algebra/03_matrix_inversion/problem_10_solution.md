# Exercise 10: Inverse of a Diagonal Matrix

## Problem Statement
Decide which diagonal matrix is invertible and give its inverse.

## Theoretical Background and Concepts
A diagonal matrix is invertible exactly when every diagonal entry is nonzero; its inverse contains their reciprocals.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
D^{-1}=\begin{pmatrix}1/2&0&0\\0&-1/3&0\\0&0&1/5\end{pmatrix}.
$$
Matrix $E$ is not invertible because its middle diagonal entry is zero.

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
$DD^{-1}=I_3$, while $E(0,1,0)^T=0$, so $E$ has a nontrivial null vector.

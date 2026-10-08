# Exercise 5: Inverting a $3\times3$ Matrix

## Problem Statement
Use Gauss–Jordan elimination to find and check $A^{-1}$.

## Theoretical Background and Concepts
Reducing $[A\mid I]$ to $[I\mid C]$ gives $C=A^{-1}$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
Row reduction of the augmented matrix gives
$$
[A\mid I]\sim
\left[I\ \middle|\ \frac12
\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}\right].
$$
Therefore
$$
A^{-1}=\frac12\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
Row-by-column multiplication gives
$$
A\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}=2I,
$$
so multiplying by $1/2$ indeed gives $I$.

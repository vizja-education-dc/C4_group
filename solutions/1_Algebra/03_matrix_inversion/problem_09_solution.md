# Exercise 9: Matrix Equation

## Problem Statement
Solve $AX=B$ and check the result.

## Theoretical Background and Concepts
Because matrix order matters, multiply by $A^{-1}$ on the left: $X=A^{-1}B$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
A^{-1}=\begin{pmatrix}1&-2\\0&1\end{pmatrix},
\quad
X=A^{-1}B
=\begin{pmatrix}-1&-7\\2&4\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
$$
AX=\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}-1&-7\\2&4\end{pmatrix}
=\begin{pmatrix}3&1\\2&4\end{pmatrix}=B.
$$

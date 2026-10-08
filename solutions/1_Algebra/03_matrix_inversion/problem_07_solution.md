# Exercise 7: Inverse of a Product

## Problem Statement
Compute $(AB)^{-1}$ and $B^{-1}A^{-1}$.

## Theoretical Background and Concepts
Undoing a composition reverses its order: $(AB)^{-1}=B^{-1}A^{-1}$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
AB=\begin{pmatrix}2&3\\0&3\end{pmatrix},
\qquad
(AB)^{-1}=\begin{pmatrix}1/2&-1/2\\0&1/3\end{pmatrix}.
$$
Also,
$$
B^{-1}A^{-1}
=\begin{pmatrix}1/2&0\\0&1/3\end{pmatrix}
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
=\begin{pmatrix}1/2&-1/2\\0&1/3\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
Multiplying $AB$ by the displayed inverse yields $I$.

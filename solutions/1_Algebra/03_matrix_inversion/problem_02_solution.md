# Exercise 2: Formula for a $2\times2$ Matrix

## Problem Statement
Find and verify the inverse of $A$.

## Theoretical Background and Concepts
For $A=\begin{pmatrix}a&b\\c&d\end{pmatrix}$, $A^{-1}=(ad-bc)^{-1}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}$ if $ad-bc\ne0$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
\det A=12-10=2,\qquad
A^{-1}=\frac12\begin{pmatrix}4&-2\\-5&3\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
$$
A\left(\frac12\begin{pmatrix}4&-2\\-5&3\end{pmatrix}\right)
=\frac12\begin{pmatrix}2&0\\0&2\end{pmatrix}=I.
$$

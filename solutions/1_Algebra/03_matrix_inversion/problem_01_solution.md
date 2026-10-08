# Exercise 1: Definition of the Inverse

## Problem Statement
Check directly whether the given $B$ equals $A^{-1}$.

## Theoretical Background and Concepts
$B=A^{-1}$ precisely when both $AB=I$ and $BA=I$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
AB=\begin{pmatrix}2&1\\1&1\end{pmatrix}\begin{pmatrix}1&-1\\-1&2\end{pmatrix}
=\begin{pmatrix}1&0\\0&1\end{pmatrix},
$$
and direct multiplication in the other order also gives $BA=I$. Hence $B=A^{-1}$.

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
Both required products equal $I$, so the conclusion follows directly from the definition.

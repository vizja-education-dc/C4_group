# Exercise 14: A Matrix That Is Its Own Inverse

## Problem Statement
Prove $A^{-1}=A$ from $A^2=I$ and give a nontrivial example.

## Theoretical Background and Concepts
An inverse is a matrix whose product with the original matrix on both sides is $I$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
Since $A^2=AA=I$, the matrix $A$ itself satisfies the defining property of $A^{-1}$. Therefore $A^{-1}=A$.
A nontrivial example is
$$
A=\begin{pmatrix}0&1\\1&0\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
$$
A^2=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I,
$$
and this matrix differs from both $I$ and $-I$.

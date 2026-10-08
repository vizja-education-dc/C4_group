# Exercise 8: Inverse of a Transformation

## Problem Statement
Find $S^{-1}$, interpret it, and check it on a vector.

## Theoretical Background and Concepts
The inverse of a diagonal scaling reciprocates each nonzero scale factor.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
S^{-1}=\begin{pmatrix}1/2&0\\0&2\end{pmatrix}.
$$
It halves the first coordinate and doubles the second, undoing $S$. For $v=(2,2)^T$,
$$
Sv=(4,1)^T,\qquad S^{-1}Sv=(2,2)^T.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
$S^{-1}S=\operatorname{diag}(1,1)=I$.

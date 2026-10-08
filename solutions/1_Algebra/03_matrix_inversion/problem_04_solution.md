# Exercise 4: Gauss–Jordan Inversion

## Problem Statement
Find $A^{-1}$ by reducing $[A\mid I]$.

## Theoretical Background and Concepts
Row operations applied to $[A\mid I]$ multiply both blocks by the same elementary matrices; when the left becomes $I$, the right is $A^{-1}$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
\left[\begin{array}{cc|cc}1&2&1&0\\3&5&0&1\end{array}\right]
\xrightarrow{R_2-3R_1}
\left[\begin{array}{cc|cc}1&2&1&0\\0&-1&-3&1\end{array}\right]
$$
$$
\xrightarrow{-R_2}
\left[\begin{array}{cc|cc}1&2&1&0\\0&1&3&-1\end{array}\right]
\xrightarrow{R_1-2R_2}
\left[\begin{array}{cc|cc}1&0&-5&2\\0&1&3&-1\end{array}\right].
$$
Thus $A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}$.

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
Multiplication gives $AA^{-1}=I$.

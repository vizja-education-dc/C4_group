# Exercise 11: Parameter and Invertibility

## Problem Statement
Find the invertible parameter values and a formula for the inverse.

## Theoretical Background and Concepts
The $2\times2$ inverse formula is valid only when the determinant is nonzero.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
\det A(t)=1-t^2.
$$
Thus $A(t)$ is invertible for $t\ne\pm1$, and
$$
A(t)^{-1}=\frac1{1-t^2}\begin{pmatrix}1&-t\\-t&1\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
Multiplication produces $(1-t^2)I/(1-t^2)=I$. At $t=\pm1$, the denominator vanishes because the rows are dependent.

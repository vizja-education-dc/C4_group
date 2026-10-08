# Exercise 6: Solving a System Using the Inverse

## Problem Statement
Solve $Ax=b$ via $x=A^{-1}b$ and verify.

## Theoretical Background and Concepts
If $A$ is invertible, multiplying $Ax=b$ on the left by $A^{-1}$ gives $x=A^{-1}b$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix},
\quad
x=A^{-1}b=\frac15\binom{15-7}{-5+14}
=\binom{8/5}{9/5}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
$$
A\binom{8/5}{9/5}=\binom{25/5}{35/5}=\binom57=b.
$$

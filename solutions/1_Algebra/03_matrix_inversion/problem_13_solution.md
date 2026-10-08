# Exercise 13: Undoing a Composite Transformation

## Problem Statement
Find $T^{-1}$ by two methods and show that the reversed order is necessary.

## Theoretical Background and Concepts
$(HS)^{-1}=S^{-1}H^{-1}$: the last action performed must be undone first.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution
$$
T=HS=\begin{pmatrix}2&1\\0&1\end{pmatrix},
\quad
T^{-1}=\begin{pmatrix}1/2&-1/2\\0&1\end{pmatrix}.
$$
Also,
$$
S^{-1}H^{-1}
=\begin{pmatrix}1/2&0\\0&1\end{pmatrix}
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
=T^{-1}.
$$
The incorrect order gives
$$
H^{-1}S^{-1}=\begin{pmatrix}1/2&-1\\0&1\end{pmatrix}\ne T^{-1}.
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks
$TT^{-1}=I$, whereas multiplying $T$ by the incorrect-order matrix does not give $I$.

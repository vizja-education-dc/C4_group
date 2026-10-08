# Exercise 12: Inverse Properties

## Problem Statement
Use the known $A^{-1}$ to compute three related inverses.

## Theoretical Background and Concepts

Let

$$
M=A^{-1}=
\begin{pmatrix}
2&-1\\
-3&2
\end{pmatrix}.
$$

We will use three inverse rules:

1. $(cA)^{-1}=c^{-1}A^{-1}$ for every nonzero scalar $c$.
2. $(A^T)^{-1}=(A^{-1})^T$.
3. $(A^2)^{-1}=A^{-1}A^{-1}=(A^{-1})^2$.

These rules are consequences of the definition of an inverse. For example,

$$
(cA)\left(\frac1cA^{-1}\right)
=AA^{-1}=I.
$$

Similarly, transposing $AA^{-1}=I$ gives

$$
(A^{-1})^TA^T=I,
$$

which shows that $(A^{-1})^T$ is the inverse of $A^T$.

### How to Think About This Problem

First decide whether an inverse can exist by checking the determinant or row independence. For a small matrix, choose between the explicit formula and Gauss–Jordan elimination. In matrix equations, write the inverse on the correct side before simplifying; matrix multiplication is not commutative. Think of the inverse as an operation that exactly undoes the original transformation.

## Detailed Step-by-Step Solution

### 1. Computing $(3A)^{-1}$

Multiplying a matrix by $3$ makes its transformation three times as large. The inverse must therefore include a factor $1/3$:

$$
(3A)^{-1}=\frac13A^{-1}=\frac13M.
$$

Multiply every entry of $M$ by $1/3$:

$$
(3A)^{-1}
=
\begin{pmatrix}
\frac23&-\frac13\\
-1&\frac23
\end{pmatrix}.
$$

### 2. Computing $(A^T)^{-1}$

The inverse and transpose operations may be applied in either order:

$$
(A^T)^{-1}=(A^{-1})^T=M^T.
$$

Transposition changes rows into columns:

$$
(A^T)^{-1}
=
\begin{pmatrix}
2&-3\\
-1&2
\end{pmatrix}.
$$

### 3. Computing $(A^2)^{-1}$

The product rule for inverses says $(AB)^{-1}=B^{-1}A^{-1}$. Taking $B=A$ gives

$$
(A^2)^{-1}=A^{-1}A^{-1}=M^2.
$$

Now multiply $M$ by itself. Showing every entry,

$$
M^2
=
\begin{pmatrix}
2&-1\\
-3&2
\end{pmatrix}
\begin{pmatrix}
2&-1\\
-3&2
\end{pmatrix}
$$

$$
=
\begin{pmatrix}
2(2)+(-1)(-3)&2(-1)+(-1)(2)\\
(-3)(2)+2(-3)&(-3)(-1)+2(2)
\end{pmatrix}
$$

$$
=
\begin{pmatrix}
7&-4\\
-12&7
\end{pmatrix}.
$$

Therefore,

$$
\boxed{
\begin{aligned}
(3A)^{-1}&=
\begin{pmatrix}
\frac23&-\frac13\\
-1&\frac23
\end{pmatrix},\\[4pt]
(A^T)^{-1}&=
\begin{pmatrix}
2&-3\\
-1&2
\end{pmatrix},\\[4pt]
(A^2)^{-1}&=
\begin{pmatrix}
7&-4\\
-12&7
\end{pmatrix}.
\end{aligned}}
$$

## Common Mistakes and Key Takeaway

Do not divide matrices as if they were numbers, and do not change the order in an inverse-of-a-product formula. A proposed inverse is easy to test: multiply it by the original matrix and look for the identity matrix. The central takeaway is that finding an inverse and verifying an inverse are separate steps, and both should appear.

## Verification and Consistency Checks

Each answer can be checked without knowing the entries of $A$:

$$
(3A)\left(\frac13A^{-1}\right)=AA^{-1}=I,
$$

$$
A^T(A^{-1})^T=(A^{-1}A)^T=I^T=I,
$$

and

$$
A^2(A^{-1})^2
=AA\,A^{-1}A^{-1}
=AIA^{-1}
=AA^{-1}
=I.
$$

The last simplification uses associativity, not commutativity: the order of the factors has not been changed.

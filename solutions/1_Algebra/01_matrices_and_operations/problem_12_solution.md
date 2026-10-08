# Exercise 12: Formula for a Matrix Power

## Problem Statement

Compute initial powers of $A$, conjecture $A^n$, and prove the formula inductively.

## Theoretical Background and Concepts

Mathematical induction proves a formula by establishing a base case and showing that truth for $n$ implies truth for $n+1$.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},\quad
A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},\quad
A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}.
$$
Thus conjecture
$$
A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}.
$$
It holds for $n=1$. Assuming it for $n$,
$$
A^{n+1}=A^nA=
\begin{pmatrix}1&n\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
=\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

The induction step produces precisely the conjectured expression with $n$ replaced by $n+1$, completing the proof.

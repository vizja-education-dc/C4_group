# Exercise 6: Transpose

## Problem Statement

Compute $A^T$, $B^T$, and $AB$, then verify $(AB)^T=B^TA^T$.

## Theoretical Background and Concepts

Transposition exchanges rows and columns. The transpose of a product reverses the order of its factors.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
A^T=\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix},\qquad
B^T=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}.
$$
Row-by-column multiplication gives
$$
AB=\begin{pmatrix}2&11\\8&23\end{pmatrix},
\qquad
(AB)^T=\begin{pmatrix}2&8\\11&23\end{pmatrix}.
$$
Finally,
$$
B^TA^T=
\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}
\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix}
=\begin{pmatrix}2&8\\11&23\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Both sides of $(AB)^T=B^TA^T$ are $2\times2$ and have identical entries.

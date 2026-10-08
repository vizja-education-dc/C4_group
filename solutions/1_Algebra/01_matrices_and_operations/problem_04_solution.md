# Exercise 4: Matrix Multiplication and Noncommutativity

## Problem Statement

Compute $AB$ and $BA$ for the given two $2\times2$ matrices and compare them.

## Theoretical Background and Concepts

Matrix products are computed row by column. Unlike multiplication of real numbers, matrix multiplication generally does not commute.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
AB=\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}2&0\\3&1\end{pmatrix}
=\begin{pmatrix}8&2\\3&1\end{pmatrix},
$$
$$
BA=\begin{pmatrix}2&0\\3&1\end{pmatrix}
\begin{pmatrix}1&2\\0&1\end{pmatrix}
=\begin{pmatrix}2&4\\3&7\end{pmatrix}.
$$
Therefore $AB\ne BA$.

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

The $(1,1)$-entries already differ: $1(2)+2(3)=8$, whereas $2(1)+0(0)=2$. This alone verifies noncommutativity in this example.

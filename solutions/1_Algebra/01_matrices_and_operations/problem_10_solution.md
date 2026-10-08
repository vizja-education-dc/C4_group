# Exercise 10: Columns of a Matrix Product

## Problem Statement

Compute $Ab_1,Ab_2$ and $AB$, then compare their columns.

## Theoretical Background and Concepts

If $B=[b_1\ b_2]$, distributivity of matrix multiplication gives $AB=[Ab_1\ Ab_2]$.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
b_1=\begin{pmatrix}1\\-1\\3\end{pmatrix},\quad
b_2=\begin{pmatrix}2\\0\\1\end{pmatrix}.
$$
Therefore
$$
Ab_1=\binom{-1}2,\qquad Ab_2=\binom21,
$$
and
$$
AB=\begin{pmatrix}-1&2\\2&1\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

The first and second columns of the computed product are exactly $Ab_1$ and $Ab_2$, respectively.

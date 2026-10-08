# Exercise 2: Addition and Scalar Multiplication

## Problem Statement

For $A=\begin{pmatrix}1&2\\-1&3\end{pmatrix}$ and $B=\begin{pmatrix}4&-2\\0&5\end{pmatrix}$, compute $A+B$, $A-B$, and $3A-2B$, and explain the dimension requirement.

## Theoretical Background and Concepts

Matrix addition, subtraction, and scalar multiplication act entry by entry. Addition and subtraction require equal dimensions because entries in identical positions must be paired.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
A+B=\begin{pmatrix}1+4&2-2\\-1+0&3+5\end{pmatrix}
=\begin{pmatrix}5&0\\-1&8\end{pmatrix},
$$
$$
A-B=\begin{pmatrix}-3&4\\-1&-2\end{pmatrix}.
$$
Also,
$$
3A-2B=\begin{pmatrix}3&6\\-3&9\end{pmatrix}
-\begin{pmatrix}8&-4\\0&10\end{pmatrix}
=\begin{pmatrix}-5&10\\-3&-1\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

All results are $2\times2$. For example, entry $(1,2)$ of the final matrix is $3(2)-2(-2)=10$, agreeing with the result.

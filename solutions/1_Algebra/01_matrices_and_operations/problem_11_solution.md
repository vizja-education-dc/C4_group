# Exercise 11: When Do Matrices Commute?

## Problem Statement

Find all $B=\begin{pmatrix}a&b\\c&d\end{pmatrix}$ satisfying $AB=BA$.

## Theoretical Background and Concepts

Two matrices commute when both product orders have equal corresponding entries.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
AB=\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix},\qquad
BA=\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}.
$$
Equating entries gives $c=0$ and $d=a$, while $a,b$ remain arbitrary. Hence
$$
B=\begin{pmatrix}a&b\\0&a\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

For this form,
$$
AB=BA=\begin{pmatrix}a&a+b\\0&a\end{pmatrix},
$$
so the conditions are sufficient as well as necessary.

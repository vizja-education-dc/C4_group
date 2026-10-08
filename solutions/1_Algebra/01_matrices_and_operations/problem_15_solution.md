# Exercise 15: Associativity and Calculation Paths

## Problem Statement

Compute $(AB)C$ and $A(BC)$, compare results and computational effort.

## Theoretical Background and Concepts

Associativity states $(AB)C=A(BC)$ whenever the products are defined; it permits regrouping but not reordering.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
AB=\begin{pmatrix}5&2\\1&4\end{pmatrix},\qquad
(AB)C=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
$$
Alternatively,
$$
BC=\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix},\qquad
A(BC)=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
$$
The first route forms a $2\times2$ intermediate and uses $12+8=20$ scalar multiplications; the second uses $12+12=24$. Thus the first grouping is shorter here.

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Both paths produce the identical $2\times2$ matrix, directly verifying associativity.

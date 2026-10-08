# Exercise 7: Identity Matrix, Zero Matrix, and Powers

## Problem Statement

Compute $AI,IA,A+0,A^2,A^3$ and describe the pattern in the powers.

## Theoretical Background and Concepts

The identity matrix is the multiplicative neutral element and the zero matrix is the additive neutral element.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
AI=IA=A,\qquad A+0=A.
$$
Direct multiplication gives
$$
A^2=\begin{pmatrix}4&4\\0&4\end{pmatrix},\qquad
A^3=\begin{pmatrix}8&12\\0&8\end{pmatrix}.
$$
Writing $A=2I+N$, where $N=\begin{pmatrix}0&1\\0&0\end{pmatrix}$ and $N^2=0$, yields
$$
A^n=2^nI+n2^{n-1}N
=\begin{pmatrix}2^n&n2^{n-1}\\0&2^n\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Putting $n=1,2,3$ into the formula reproduces $A,A^2,A^3$.

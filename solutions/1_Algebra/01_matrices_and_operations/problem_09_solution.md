# Exercise 9: Composing Transformations

## Problem Statement

Compute $RSx$ and $SRx$, then interpret why they differ.

## Theoretical Background and Concepts

In a product, the rightmost transformation acts first. Nonuniform scaling is tied to coordinate directions, so it need not commute with rotation.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
Sx=\binom22,\qquad RSx=R\binom22=\binom{-2}2.
$$
In the opposite order,
$$
Rx=\binom{-2}1,\qquad SRx=S\binom{-2}1=\binom{-4}1.
$$
Thus $RSx\ne SRx$. Rotation changes which component lies in the direction stretched by $S$.

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Multiplying the composite matrices gives
$$
RS=\begin{pmatrix}0&-1\\2&0\end{pmatrix},\quad
SR=\begin{pmatrix}0&-2\\1&0\end{pmatrix};
$$
applying them to $x$ reproduces the two results.

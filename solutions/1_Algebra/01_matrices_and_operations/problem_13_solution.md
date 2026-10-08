# Exercise 13: A Recurrence Written in Matrix Form

## Problem Statement

Compute powers of $F$, compare them with Fibonacci numbers, and interpret $F(a,b)^T$.

## Theoretical Background and Concepts

The Fibonacci recurrence is $F_{n+1}=F_n+F_{n-1}$. Matrix multiplication can update both consecutive terms simultaneously.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix},\quad
F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix},\quad
F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix},\quad
F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}.
$$
The pattern is
$$
F^n=\begin{pmatrix}F_{n+1}&F_n\\F_n&F_{n-1}\end{pmatrix}.
$$
Moreover,
$$
F\binom ab=\binom{a+b}{a},
$$
which forms the next term and retains the previous one.

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Multiplying $F^4$ by $F$ gives $F^5$, and every displayed entry follows the sum-of-two-predecessors rule.

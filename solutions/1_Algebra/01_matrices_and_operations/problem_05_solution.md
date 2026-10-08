# Exercise 5: Matrix Times Vector

## Problem Statement

Compute $Ax$ and express it as a linear combination of the columns of $A$.

## Theoretical Background and Concepts

If $A=[a_1\ a_2]$ and $x=(x_1,x_2)^T$, then $Ax=x_1a_1+x_2a_2$.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
Ax=\begin{pmatrix}2&-1\\1&3\end{pmatrix}\binom42
=\binom{2(4)-1(2)}{1(4)+3(2)}
=\binom6{10}.
$$
Using the columns explicitly,
$$
Ax=4\binom21+2\binom{-1}3=\binom8 4+\binom{-2}6=\binom6{10}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

The direct row calculation and the column-combination calculation give the same vector, $(6,10)^T$.

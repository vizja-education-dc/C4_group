# Exercise 8: Row Operations and Their Reversibility

## Problem Statement

Perform the three specified row operations in order and state their inverses.

## Theoretical Background and Concepts

Elementary row operations are reversible: undo row addition with the opposite addition, undo a nonzero scaling with reciprocal scaling, and undo a swap by repeating it.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

After $R_2\leftarrow R_2-2R_1$,
$$
\begin{pmatrix}1&2&-1\\0&0&3\\-1&1&3\end{pmatrix}.
$$
After $R_3\leftarrow R_3+R_1$,
$$
\begin{pmatrix}1&2&-1\\0&0&3\\0&3&2\end{pmatrix}.
$$
After interchanging $R_2,R_3$,
$$
\begin{pmatrix}1&2&-1\\0&3&2\\0&0&3\end{pmatrix}.
$$
To reverse the complete sequence, swap $R_2,R_3$, then use $R_3\leftarrow R_3-R_1$, then $R_2\leftarrow R_2+2R_1$.

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Applying those inverse operations in reverse chronological order returns exactly the original matrix.

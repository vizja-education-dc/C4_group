# Exercise 1: Matrix Size and Entries

## Problem Statement

Given

$$
A=\begin{pmatrix}2&-1&3\\0&4&5\end{pmatrix},\qquad
B=\begin{pmatrix}1&0\\-2&3\\4&1\end{pmatrix},
$$

determine the sizes of the matrices, identify the requested entries, and write the second row of $A$ and first column of $B$ as vectors.

## Theoretical Background and Concepts

An $m\times n$ matrix has $m$ rows and $n$ columns. An entry $a_{ij}$ is located in row $i$ and column $j$. A row vector is conventionally written horizontally, while a column vector is written vertically.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

Matrix $A$ has two rows and three columns, so

$$
A\text{ is }2\times3.
$$

Matrix $B$ has three rows and two columns, so

$$
B\text{ is }3\times2.
$$

Reading each requested entry by row and then column gives

$$
a_{12}=-1,\qquad a_{23}=5,\qquad b_{21}=-2,\qquad b_{32}=1.
$$

The second row of $A$ is

$$
\begin{pmatrix}0&4&5\end{pmatrix},
$$

and the first column of $B$ is

$$
\begin{pmatrix}1\\-2\\4\end{pmatrix}.
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

- The index $a_{12}$ points to row 1, column 2 of $A$, where the value is $-1$.
- The index $a_{23}$ points to row 2, column 3 of $A$, where the value is $5$.
- The index $b_{21}$ points to row 2, column 1 of $B$, where the value is $-2$.
- The index $b_{32}$ points to row 3, column 2 of $B$, where the value is $1$.
- The extracted row contains three entries, consistent with the three columns of $A$; the extracted column contains three entries, consistent with the three rows of $B$.

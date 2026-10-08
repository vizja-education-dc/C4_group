# Exercise 3: When Can Matrices Be Multiplied?

## Problem Statement

For $A_{2\times3},B_{3\times4},C_{4\times2},D_{2\times2}$, determine whether each listed product exists and give its size.

## Theoretical Background and Concepts

An $m\times n$ matrix can multiply an $r\times p$ matrix exactly when $n=r$; the result then has size $m\times p$.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
\begin{array}{c|c|c}
\text{Product}&\text{Inner dimensions}&\text{Conclusion}\\\hline
AB&3=3&2\times4\\
BA&4\ne2&\text{undefined}\\
BC&4=4&3\times2\\
CB&2=2&4\times4\\
AC&3\ne4&\text{undefined}\\
CA&2=2&4\times3\\
AD&3\ne2&\text{undefined}\\
DA&2=2&2\times3
\end{array}
$$

Thus $CA$ is defined because $C$ has two columns and $A$ has two rows.

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Rechecking each pair as “columns of the first = rows of the second” confirms that $AB,BC,CB,CA,DA$ are defined, while $BA,AC,AD$ are undefined.

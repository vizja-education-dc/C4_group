# Exercise 14: Rotation Matrices

## Problem Statement

Multiply $R(\alpha)R(\beta)$ and identify the resulting rotation.

## Theoretical Background and Concepts

The angle-sum identities are
$\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta$ and
$\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta$.

### How to Think About This Problem

Start by writing the dimensions next to every matrix or vector. Dimensions are a quick error detector: addition needs equal sizes, while multiplication needs the inner dimensions to match. For an actual product, cover all but one row of the first matrix and one column of the second; their dot product produces one entry. Keep the order of factors visible because changing it can change both the answer and whether the product is defined.

## Detailed Step-by-Step Solution

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta&
-(\cos\alpha\sin\beta+\sin\alpha\cos\beta)\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta&
\cos\alpha\cos\beta-\sin\alpha\sin\beta
\end{pmatrix}.
$$
Applying the angle-sum identities gives
$$
R(\alpha)R(\beta)=
\begin{pmatrix}\cos(\alpha+\beta)&-\sin(\alpha+\beta)\\
\sin(\alpha+\beta)&\cos(\alpha+\beta)\end{pmatrix}
=R(\alpha+\beta).
$$

## Common Mistakes and Key Takeaway

A frequent mistake is to multiply entries position by position or silently reverse factor order. Another is to state a pattern after seeing only a few examples without proving it. The key habit is to check dimensions first, calculate entry by entry, and then verify using a second viewpoint such as columns, transformations, or induction.

## Verification and Consistency Checks

Geometrically, the rightmost rotation through $\beta$ followed by rotation through $\alpha$ rotates every vector through the total angle $\alpha+\beta$, agreeing with the matrix result.

# Problem 6: When a Logarithm Appears

## Problem Statement
Integrate the derivative-over-function expression.

## Theoretical Background and Concepts
$\int u'/u\,dx=\ln|u|+C$ on intervals where $u\ne0$.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
Let $u=x^2+5$, so $du=2x\,dx$. Then
$$
\int\frac{2x}{x^2+5}dx=\int\frac{du}{u}
=\ln(x^2+5)+C.
$$
Absolute value is unnecessary because $x^2+5>0$.

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
Differentiating gives $2x/(x^2+5)$.

# Problem 10: Definite Integral Check

## Problem Statement
Bound the integral before computing it exactly.

## Theoretical Background and Concepts
If $m\le f\le M$ on an interval of length $L$, then $mL\le\int f\le ML$.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
The given bounds imply
$$
2\le\int_0^2(x^2+1)dx\le10.
$$
Exactly,
$$
\int_0^2(x^2+1)dx
=\left[\frac{x^3}{3}+x\right]_0^2
=\frac{14}{3}.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
$14/3$ lies between $2$ and $10$. The bound would catch a sign error or implausibly large/small arithmetic result.

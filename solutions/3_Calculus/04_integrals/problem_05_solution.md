# Problem 5: Structural Substitution

## Problem Statement
Integrate $xe^{x^2}$ and compare its structure with Problem 4.

## Theoretical Background and Concepts
Both integrals contain a function of $x^2$ multiplied by a constant multiple of the derivative of $x^2$.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
Let $u=x^2$, so $du=2x\,dx$:
$$
\int xe^{x^2}dx=\frac12\int e^u du
=\frac12e^{x^2}+C.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
$(\frac12e^{x^2})'=\frac12e^{x^2}(2x)=xe^{x^2}$.

# Problem 4: Substitution and the Chain Rule

## Problem Statement
Integrate $2x(x^2+1)^4$ using substitution.

## Theoretical Background and Concepts
Substitution reverses the chain rule by replacing an inner function and its differential.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
Let $u=x^2+1$, so $du=2x\,dx$. Then
$$
\int2x(x^2+1)^4dx=\int u^4du=\frac{u^5}{5}+C
=\frac{(x^2+1)^5}{5}+C.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
Differentiation yields $\frac15\cdot5(x^2+1)^4(2x)$, the original integrand.

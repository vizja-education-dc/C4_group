# Problem 2: Powers, Roots, and Domain

## Problem Statement
Rewrite, determine the domain, integrate, and verify.

## Theoretical Background and Concepts
Use $\int x^pdx=x^{p+1}/(p+1)+C$ for $p\ne-1$.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
The integrand is $2x^{1/2}+3x^{-2}-x^{1/3}$ and its real domain is $(0,\infty)$. Therefore
$$
\int\left(2\sqrt x+\frac3{x^2}-x^{1/3}\right)dx
=\frac43x^{3/2}-\frac3x-\frac34x^{4/3}+C.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
Termwise differentiation gives $2x^{1/2}+3x^{-2}-x^{1/3}$ on $(0,\infty)$.

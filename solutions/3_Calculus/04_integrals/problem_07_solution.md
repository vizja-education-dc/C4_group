# Problem 7: Integration by Parts

## Problem Statement
Compute $\int xe^x dx$ and connect the method to the product rule.

## Theoretical Background and Concepts
From $(uv)'=u'v+uv'$, integration gives $\int u\,dv=uv-\int v\,du$.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
Choose $u=x$, $dv=e^xdx$, so $du=dx$, $v=e^x$:
$$
\int xe^xdx=xe^x-\int e^xdx=e^x(x-1)+C.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
$[e^x(x-1)]'=e^x(x-1)+e^x=xe^x$.

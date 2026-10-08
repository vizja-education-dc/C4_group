# Problem 8: Choosing Factors in Integration by Parts

## Problem Statement
Compute $\int x\cos x\,dx$ with a justified choice.

## Theoretical Background and Concepts
Differentiating the polynomial simplifies it, while integrating $\cos x$ remains elementary.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
Take $u=x$, $dv=\cos x\,dx$, hence $du=dx$, $v=\sin x$:
$$
\int x\cos x\,dx=x\sin x-\int\sin x\,dx
=x\sin x+\cos x+C.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
The derivative is $\sin x+x\cos x-\sin x=x\cos x$.

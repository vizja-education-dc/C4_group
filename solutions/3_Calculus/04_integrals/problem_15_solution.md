# Problem 15: Recovering a Function

## Problem Statement
Find the antiderivative satisfying $F(0)=3$.

## Theoretical Background and Concepts
Substitution recognizes an inner derivative; an initial condition selects one constant from the antiderivative family.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
With $u=x^2$, $du=2x\,dx$:
$$
F(x)=e^{x^2}+C.
$$
The condition gives $1+C=3$, so
$$
F(x)=e^{x^2}+2.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
$F'(x)=2xe^{x^2}$ and $F(0)=1+2=3$, verifying both requirements.

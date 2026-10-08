# Problem 9: Signed Integral and Geometric Area

## Problem Statement
Compute the definite integral and compare it with total geometric area.

## Theoretical Background and Concepts
A definite integral is signed: regions below the axis contribute negatively.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
$$
\int_{-1}^2x\,dx=\left[\frac{x^2}{2}\right]_{-1}^2
=2-\frac12=\frac32.
$$
Below the axis is a triangle of area $1/2$; above is a triangle of area $2$. Total geometric area is
$$
\frac12+2=\frac52,
$$
while signed area is $2-\frac12=3/2$.

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
The geometric decomposition reproduces the integral when the lower area is assigned a minus sign.

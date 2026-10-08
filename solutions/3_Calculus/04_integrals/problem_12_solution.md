# Problem 12: Symmetry, Sign, and Absolute Value

## Problem Statement
Compare the two symmetric definite integrals.

## Theoretical Background and Concepts
An odd function integrates to zero over $[-a,a]$; an even nonnegative function doubles its half-interval area.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
Since $x$ is odd,
$$
\int_{-2}^2x\,dx=0.
$$
Since $|x|$ is even,
$$
\int_{-2}^2|x|dx=2\int_0^2x\,dx=2\left[\frac{x^2}{2}\right]_0^2=4.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
The first graph's signed triangular areas cancel; the second reflects both triangles above the axis, so they add.

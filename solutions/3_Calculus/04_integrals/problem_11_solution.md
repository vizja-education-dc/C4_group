# Problem 11: Choosing Integration Methods

## Problem Statement
Identify a method and evaluate each integral.

## Theoretical Background and Concepts
Use linear substitution for a composite, parts for a polynomial times logarithm, and substitution when an inner derivative is present.

### How to Think About This Problem

Before calculating, identify the structure. Use direct rules for sums of familiar powers, substitution when an inner function appears with its derivative, and integration by parts for products where differentiating one factor simplifies it. For definite integrals, first determine sign and geometry so the numerical answer has context.

## Detailed Step-by-Step Solution
1. With $u=3x$:
$$
\int\sin(3x)dx=-\frac13\cos(3x)+C.
$$
2. By parts, $u=\ln x$, $dv=x\,dx$:
$$
\int x\ln x\,dx=\frac{x^2}{2}\ln x-\frac{x^2}{4}+C,\quad x>0.
$$
3. With $u=x^2+1$:
$$
\int\frac{x}{\sqrt{x^2+1}}dx=\sqrt{x^2+1}+C.
$$

## Common Mistakes and Key Takeaway

For indefinite integrals, remember $+C$ and verify by differentiation on the correct domain. For definite integrals, do not confuse signed accumulation with geometric area; split where the function changes sign or definition. Method recognition is more important than memorizing isolated examples.

## Verification and Consistency Checks
Differentiating each result reproduces its integrand.

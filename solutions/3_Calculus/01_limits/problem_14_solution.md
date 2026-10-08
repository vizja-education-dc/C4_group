# Exercise 14: A Trigonometric $0/0$ Limit

## Problem Statement
Compute the limit without l'Hôpital's rule.

## Theoretical Background and Concepts
Use $1-\cos x=2\sin^2(x/2)$ and the fundamental sine limit.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\frac{1-\cos x}{x^2}
=\frac{2\sin^2(x/2)}{x^2}
=\frac12\left(\frac{\sin(x/2)}{x/2}\right)^2\to\frac12.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The normalized sine ratio tends to $1$, so its square does also.

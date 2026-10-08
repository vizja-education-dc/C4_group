# Exercise 5: The Classical Limit

## Problem Statement
Evaluate $(1+1/n)^n$ and compare numerical observations.

## Theoretical Background and Concepts
The number $e$ is characterized by the classical limit $\lim_{n\to\infty}(1+1/n)^n$.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\boxed{\lim_{n\to\infty}\left(1+\frac1n\right)^n=e}.
$$
Examples: $n=1:2$, $n=10:\,2.5937$, $n=100:\,2.7048$, $n=1000:\,2.7169$, approaching $e\approx2.71828$.

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The values support the limit but do not prove it: finitely many terms cannot control every later term. The analytical classical-limit theorem supplies the proof.

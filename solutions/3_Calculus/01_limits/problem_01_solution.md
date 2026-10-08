# Exercise 1: Dominant Terms

## Problem Statement
Compute the sequence limit and explain dominance.

## Theoretical Background and Concepts
Dividing a rational polynomial expression by its highest power isolates the leading coefficients.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\frac{4n^2-3n+1}{2n^2+5n-7}
=\frac{4-3/n+1/n^2}{2+5/n-7/n^2}\longrightarrow\frac42=2.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
All lower-degree ratios tend to zero, leaving only the quadratic coefficients.

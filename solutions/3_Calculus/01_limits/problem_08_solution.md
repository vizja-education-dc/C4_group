# Exercise 8: Rationalizing a Function Limit

## Problem Statement
Evaluate the radical limit by rationalization.

## Theoretical Background and Concepts
Multiplication by the conjugate removes a $0/0$ form without changing nearby values.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
$$
\frac{\sqrt x-2}{x-4}\frac{\sqrt x+2}{\sqrt x+2}
=\frac1{\sqrt x+2}\quad(x\ne4).
$$
Thus
$$
\lim_{x\to4}\frac{\sqrt x-2}{x-4}=\frac14.
$$

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
As in the sequence radical problem, conjugation turns a difference of roots into a difference of squares.

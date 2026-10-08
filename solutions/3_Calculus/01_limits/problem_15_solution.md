# Exercise 15: Observation Versus Proof

## Problem Statement
Numerically explore one sequence and one function limit, then distinguish evidence from proof.

## Theoretical Background and Concepts
Tables and sketches suggest limiting behavior; algebraic transformations establish it for arbitrarily close or large arguments.

### How to Think About This Problem

Begin with direct substitution to identify the form. If it is determinate, stop; if it is $0/0$, $\infty/\infty$, or $\infty-\infty$, choose an algebraic transformation such as factoring, dividing by the dominant term, or multiplying by a conjugate. Every transformation should preserve the expression for nearby admissible values.

## Detailed Step-by-Step Solution
Choose Exercise 1's sequence. Values for $n=10,100,1000$ are approximately
$$
1.5267,\quad1.9373,\quad1.9935,
$$
consistent with the proved limit $2$.

Choose Exercise 7's function near $3$:
$$
\begin{array}{c|cccc}
x&2.90&2.99&3.01&3.10\\\hline
f(x)&1.90&1.99&2.01&2.10
\end{array}
$$
because $f(x)=x-1$ for $x\ne3$. The graph is the line $y=x-1$ with a hole at $(3,2)$.

## Common Mistakes and Key Takeaway

An indeterminate form is not an answer—it only says more work is needed. Numerical tables can suggest a limit but cannot prove it. The key takeaway is to expose the dominant behavior and then use established limit laws; for one-sided limits, keep track of the sign as well as the magnitude.

## Verification and Consistency Checks
The analytic division arguments prove the limits. Any finite table could miss later or closer exceptional behavior, so numerical observation alone is not proof.

# Problem 6: Average Value

## Problem Statement
Find the average of $x^2$ on $[0,3]$ and a point attaining it.

## Theoretical Background and Concepts
The average value on $[a,b]$ is $(b-a)^{-1}\int_a^bf(x)dx$.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
$$
f_{\mathrm{avg}}=\frac13\int_0^3x^2dx
=\frac13\left[\frac{x^3}{3}\right]_0^3=3.
$$
Solving $c^2=3$ in $[0,3]$ gives $c=\sqrt3$.

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
Geometrically, the area under $x^2$ equals the rectangle area $3\cdot3=9$ at average height $3$.

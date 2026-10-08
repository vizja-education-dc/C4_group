# Problem 4: Area Between Curves

## Problem Statement
Find the bounded area between $y=x$ and $y=x^2$.

## Theoretical Background and Concepts
Area is the integral of upper curve minus lower curve between intersections.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
Intersections satisfy $x=x^2$, so $x=0,1$. On $[0,1]$, $x\ge x^2$. Therefore
$$
\text{Area}=\int_0^1(x-x^2)dx
=\left[\frac{x^2}{2}-\frac{x^3}{3}\right]_0^1
=\frac16.
$$

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
The integrand is nonnegative on the full interval, so the positive result is geometrically consistent.

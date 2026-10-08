# Problem 1: Motion

## Problem Statement
Find velocity, acceleration, stopping times, and directions of motion.

## Theoretical Background and Concepts
Velocity is $s'(t)$, acceleration is $s''(t)$, and velocity's sign determines direction.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
$$
v(t)=3t^2-12t+9=3(t-1)(t-3),\qquad a(t)=6t-12.
$$
The point stops at $t=1,3$. For $t\ge0$, it moves positively on $[0,1)$ and $(3,\infty)$, and negatively on $(1,3)$.

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
Testing $t=0,2,4$ gives velocity signs $+,-,+$, confirming the interval classification.

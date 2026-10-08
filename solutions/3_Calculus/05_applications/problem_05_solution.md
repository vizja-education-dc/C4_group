# Problem 5: Distance from Velocity

## Problem Statement
Compute distance over five seconds and distinguish distance from displacement.

## Theoretical Background and Concepts
Integrating velocity gives displacement; when velocity is nonnegative, displacement equals distance.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
Here $v(t)=4t+2>0$ on $[0,5]$, so
$$
\text{distance}=\int_0^5(4t+2)dt
=\left[2t^2+2t\right]_0^5=60\text{ m}.
$$

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
If velocity took negative values, displacement would remain $\int v\,dt$, but actual distance would be $\int|v|\,dt$, split at velocity zeros.

# Problem 11: Volume of Revolution

## Problem Statement
Construct and evaluate the disk-method integral.

## Theoretical Background and Concepts
At coordinate $x$, rotation creates a disk of radius $y$ and area $\pi y^2$.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
Since $y=\sqrt x$,
$$
V=\pi\int_0^4y^2dx
=\pi\int_0^4x\,dx
=\pi\left[\frac{x^2}{2}\right]_0^4
=8\pi.
$$

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
The factor $\pi y^2$ is exactly the circular cross-sectional area; integrating these thin disks accumulates the volume.

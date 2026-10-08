# Problem 3: Open Box from Cardboard

## Problem Statement
Model the box volume and find the maximizing cut size.

## Theoretical Background and Concepts
After cutting, height is $x$ and base dimensions are reduced by $2x$.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
$$
V(x)=x(30-2x)(40-2x),\qquad0<x<15.
$$
Expanding,
$$
V'=1200-280x+12x^2=4(3x^2-70x+300).
$$
The roots are
$$
x=\frac{35\pm5\sqrt{13}}3.
$$
Only
$$
x=\frac{35-5\sqrt{13}}3\approx5.657\text{ cm}
$$
lies in the physical domain, so it maximizes volume.

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
$V''=24x-280<0$ at this value, and volume tends to zero at both endpoints.

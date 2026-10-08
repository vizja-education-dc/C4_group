# Problem 9: Minimizing Material for a Can

## Problem Statement
Minimize the surface area of a closed cylinder with fixed volume.

## Theoretical Background and Concepts
Use the constraint to express the objective in one positive variable.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
The constraint is
$$
V=\pi r^2h,\qquad h=\frac{V}{\pi r^2}.
$$
Thus
$$
S(r)=2\pi r^2+2\pi rh
=2\pi r^2+\frac{2V}{r},\quad r>0.
$$
Setting $S'=4\pi r-2V/r^2=0$ gives $V=2\pi r^3$. Therefore
$$
h=\frac{V}{\pi r^2}=2r.
$$

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
$S''=4\pi+4V/r^3>0$, so this is the unique minimum. Geometrically, height equals diameter.

# Exercise 9: Ellipsoid and Cross-Sections

## Problem Statement
Read the semiaxes and describe horizontal cross-sections.

## Theoretical Background and Concepts
Fixing one coordinate in an ellipsoid produces smaller similar ellipses.

### How to Think About This Problem

Try to reach canonical form before naming the object. Complete squares to reveal translations, read denominators as squared semiaxis lengths, and use the signs of squared terms to distinguish ellipses, hyperbolas, and parabolas. For a surface, hold one coordinate constant and recognize the resulting two-dimensional cross-section.

## Detailed Step-by-Step Solution
The semiaxes are $3,2,4$ along $x,y,z$. At $z=0$,
$$
\frac{x^2}{9}+\frac{y^2}{4}=1.
$$
At $z=c$, $|c|<4$,
$$
\frac{x^2}{9}+\frac{y^2}{4}=1-\frac{c^2}{16};
$$
the semiaxes are $3\sqrt{1-c^2/16}$ and $2\sqrt{1-c^2/16}$.

## Common Mistakes and Key Takeaway

A common mistake is reading a denominator as the semiaxis instead of its square root, or naming a surface from memory without checking whether real sections exist. Build sketches from dependable landmarks: center or vertex, intercepts, axes, asymptotes, and several cross-sections. Substituting these landmarks provides a direct consistency check.

## Verification and Consistency Checks
The sections shrink as $|c|$ grows, become points at $|c|=4$, and do not exist beyond, matching a closed ellipsoid.

# Exercise 15: Recognition from Algebra and Sections

## Problem Statement
Reduce the first equation and identify the second only after analyzing sections.

## Theoretical Background and Concepts
Completing squares reveals translated conics; fixed-coordinate sections reveal three-dimensional shape and scale.

### How to Think About This Problem

Try to reach canonical form before naming the object. Complete squares to reveal translations, read denominators as squared semiaxis lengths, and use the signs of squared terms to distinguish ellipses, hyperbolas, and parabolas. For a surface, hold one coordinate constant and recognize the resulting two-dimensional cross-section.

## Detailed Step-by-Step Solution
The first equation becomes
$$
4(x-1)^2+9(y+2)^2=36
\quad\Longleftrightarrow\quad
\frac{(x-1)^2}{9}+\frac{(y+2)^2}{4}=1.
$$
It is an ellipse centered at $(1,-2)$, with horizontal semiaxis $3$, vertical semiaxis $2$, and vertices $(-2,-2),(4,-2),(1,-4),(1,0)$.

For $4x^2+y^2=z^2$, $z=c$ gives ellipses with semiaxes $|c|/2$ in $x$ and $|c|$ in $y$. The section $x=0$ is $y=\pm z$; $y=0$ is $z=\pm2x$. The sections meet at the origin and expand in both $z$-directions, identifying an elliptic double cone.

## Common Mistakes and Key Takeaway

A common mistake is reading a denominator as the semiaxis instead of its square root, or naming a surface from memory without checking whether real sections exist. Build sketches from dependable landmarks: center or vertex, intercepts, axes, asymptotes, and several cross-sections. Substituting these landmarks provides a direct consistency check.

## Verification and Consistency Checks
The ellipse's four vertices satisfy the original equation. The cone sections show the stated unequal horizontal scales and two nappes.

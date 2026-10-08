# Problem 10: Cable Through Water and Land

## Problem Statement
Build and minimize the cable cost.

## Theoretical Background and Concepts
Choose the emergence point as one variable and combine Euclidean underwater distance with remaining land distance.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
Let $x\in[0,500]$ be the distance along the opposite bank from the point directly across from $A$ to the emergence point. In units of land cost per meter,
$$
C(x)=2\sqrt{100^2+x^2}+(500-x).
$$
Then
$$
C'(x)=\frac{2x}{\sqrt{10000+x^2}}-1.
$$
Setting this to zero gives $3x^2=10000$, hence
$$
x=\frac{100}{\sqrt3}\approx57.7\text{ m}.
$$
The remaining land cable is about $442.3$ m.

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
$C''(x)=20000/(10000+x^2)^{3/2}>0$, so the critical point is the unique minimum on the domain.

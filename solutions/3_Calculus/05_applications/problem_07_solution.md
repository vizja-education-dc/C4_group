# Problem 7: Exponential Growth

## Problem Statement
Verify proportional growth and find doubling time.

## Theoretical Background and Concepts
An exponential's derivative is proportional to itself.

### How to Think About This Problem

Write down variables with units before writing formulas. Translate every verbal restriction into an equation or domain condition, reduce the model to one independent variable, and only then use calculus. After finding a critical point, compare it with the physical domain and interpret the numerical result in the original units.

## Detailed Step-by-Step Solution
$$
N'(t)=kN_0e^{kt}=kN(t).
$$
For doubling time $T$,
$$
N_0e^{kT}=2N_0\implies e^{kT}=2
\implies T=\frac{\ln2}{k}.
$$

## Common Mistakes and Key Takeaway

A correct derivative cannot rescue an incorrect model. Frequent mistakes include ignoring endpoint or positivity restrictions, mixing displacement with distance, and reporting a number without units. The key takeaway is the full chain: assumptions → model → domain → calculation → verification → real-world interpretation.

## Verification and Consistency Checks
$N_0$ cancels from the doubling equation, so doubling time depends only on the growth constant $k$.

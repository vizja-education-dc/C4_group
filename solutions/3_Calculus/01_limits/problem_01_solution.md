## Solution: Dominant Terms in a Sequence

We want to compute

\\[ \lim\_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}. \\]

### Step 1. Identify the dominant terms

The highest-degree terms are:

- Numerator: \\(4n^2\\)
- Denominator: \\(2n^2\\)

Both polynomials have degree 2.

### Step 2. Divide by the highest power of \\(n\\)

Divide the numerator and denominator by \\(n^2\\):

\\[ =\lim\_{n\to\infty} \frac{4-\frac3n+\frac1{n^2}} {2+\frac5n-\frac7{n^2}}. \\]

### Step 3. Evaluate the limit

As \\(n\to\infty\\),

\\[ \frac1n\to0,\qquad \frac1{n^2}\to0. \\]

Therefore,

\\[ =\frac{4-0+0}{2+0-0}=\frac42. \\]

FINAL ANSWER

\\[ \boxed{\displaystyle\lim\_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}=2} \\]

### Why do the highest-degree terms determine the result?

As \\(n\\) becomes very large, \\(n^2\\) grows much faster than \\(n\\) or a constant.

Consequently,

\\[ 4n^2-3n+1\sim4n^2 \\]

and

\\[ 2n^2+5n-7\sim2n^2. \\]

Thus, for large \\(n\\),

\\[ \frac{4n^2-3n+1}{2n^2+5n-7} \approx\frac{4n^2}{2n^2}=2. \\]

Key principle: When the numerator and denominator are polynomials of the same degree, the limit as \\(n\to\infty\\) equals the ratio of their leading coefficients.

I can also create a graph illustrating how the sequence approaches 2.
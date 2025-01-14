### Solution

Let's label the 2 missing numbers as `a` and `b`.

- Formula 1: Sum of 1 to n is (n)(n+1)/2
- Formula 2: Sum of squares of 1 to n is 1<sup>2</sup> + 2<sup>2</sup> + .... n<sup>2</sup>

We can calculate "ActualValue" by using the 2 formulas above, giving us:

- ActualValue + a   + b   = (n)(n+1)/2
- ActualValue + a^2 + b^2 = 1<sup>2</sup> + 2<sup>2</sup> + .... n<sup>2</sup>

Since ActualValue and `n` are both known, this gives us 2 formulas with 2 unknowns: `a`, `b`

We can solve these 2 equations for `a` and `b` (giving us the 2 missing numbers)

Note: We dont use 1\*2\*...\*n as a formula since that will likely cause integer overflow

# Peak Finding tests

1. Sort the functions in increasing order of asymptotic (big-O) complexity

$f\_1(n)$ = $n^{0.99999} log\_n$

$f\_2(n)$ = 10000000n

$f\_3(n)$ = $1.000001^n$

$f\_4(n)$ = $n^2$



**Solution**:

We will solve this problem by identifying the asymptotic growth (big-O). We should also know that logarithmic functions grows slower as compared to linear function so in that case $f\_1(n)$ grows slowest.

**Note** In the worse case we have $\theta(n)$ complexities. This implies that all integers are the same. The growth rate remains the same since we have the same number/length of n items to be looked into.

**1.000001n** is a real number fraction. They have a slightly higher complexities compared to integer numbers.

Finally, exponential function will grow very fast and its is for this reason they are highly regulated by big organization.

**Answer** : $f_1(n), f_2(n), f_3(n), f_4(n)$ 

---
## Correct answer with reasons:
 $f_1(n), f_2(n), f_4(n), f_3(n)$

The first function $f_1(n) = $n^{0.9999}log_n$ can be evaluated to $O(n)log_n)$ complexities.

The second function $f_2(n) = 1000000n$ is a linear complexity thus given as $O(n)$ complexities.

The third function $f_3(n) = 1.000001^n$ has a higher complexity and grows much faster compared to even the exponential complexity. This is a quadratic complexity as: $O(n^3)$ 

Finally, the function $f_4(n) = n^2$ has an exponential of complexity given as: $O(n^2)$


2. Group two of functions:

$f_1(n)$ = $2^{2^{10000}}$
$f_2(n)$ = $2^10000n$
$f_3(n)$ = $\binom{n}{2}$
$f_4(n)$ = $n\sqrt{n}$

My solution:

The first function will have a single resultant solution and hence, it's a $O(1)$.

In the second function, we will apply some little mathematical concepts whereby $2^{10000n}$ = $1000nlog_2 2$. This has a very low growth rate compared to other functions but slightly higher that the one with a single solution.

In the third function, we have two combination and therefore for a worst case scenario the complexity time will be $O(2)$ 

Finally, for the final function with the square root. The square root will make the function grow slower and slower but much faster compared to the second function. There reason is because the second function is growing slower 5000 times that of the fourth function.

**Answer** $f_1(n)$, $f_3(n)$, $f_2(n)$, $f_4(n)$ 

**Correct answer with reasons**:
 








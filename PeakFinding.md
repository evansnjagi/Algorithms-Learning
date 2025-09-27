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

The first function $f_1(n) = $n^0.9999log_n$ can be evaluated to $O(n)log_n) complexities.

The second function $f_2(n) = 1000000n$ is a linear complexity thus given as $O(n)$ complexities.

The third function $f_3(n) = 1.000001^n$ has a higher complexity and grows much faster compared to even the exponential complexity. This is a quadratic complexity as: $O(n^3)$ 

Finally, the function $f_4(n) = n^2$ has an exponential of complexity given as: $O(n^2)


2. 







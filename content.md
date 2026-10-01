[scipy.special.comb{.python}](https://docs.scipy.org/doc/scipy/reference/generated/scipy.special.comb.html) computes the number of unordered ways of taking $k$ things from a pool of $n$ things (also know as the binomial coefficient):

$$
|\binom{n}{k} = \frac{n!}{k!(n-k)!}
$$

The first argument to `comb`{.python} is `n`, the total number of things, and the second argument is `k`, the number of things to choose. For example:

```py-cell
from scipy.special import comb

print(comb(5, 2))
print(comb(100, 2))
```

The function returns a float.
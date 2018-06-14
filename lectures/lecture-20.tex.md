# Lecture 20: Pascal's triangle and the binomial theorem

## Patterns

Choosing $r$ elements from a set of $n$ elements to be in a combination is
equivalent to choosing $n-r$ elements from the same set to not be in the
combination. So:

$$\binom{n}{r} = \binom{n}{n-r} \text{ for } 0 \leq r \leq n$$

Let $x$ be the set of $n$ elements and $x$ is a fixed element of $X$. For any $r
\in \{1, \dots, n\}$, there are $\binom{n-1}{r}$ combinations of $r$ elements of
$X$ that do not contain $x$ and there are $\binom{n-1}{r-1}$ combinations of $r$
elements of $X$ that do contain $x$. So:

$$\binom{n}{r} = \binom{n-1}{r-q} + \binom{n-1}{r} \text{ for } 1 \leq r \leq
n$$

**Question** The binomial coefficient $\binom{0}{0}$ is the number of ways to
choose zero things from the empty set. The value of $\binom{0}{0}$ is:

1. 0
2. 1
3. Undefined
4. None of the above

**Answer** **2** It is the top entry in Pascal's triangle.

## Binomial Theorem

$$(x+y)^n = \binom{n}{0}x^n y^0 + \binom{n}{1} x^{n-1} y^1 + \bin{n}{2} x^{n-2}
y^2 + \dots + \binom{n}{n-1} x^1 y^{n-1} + \binom{n}{n} x^0 y^n$$

**Questions**

**20.1** Substitute $x=1$ and $y=-1$ into the statement of the binomial theorem.
What does this tell you about the rows of Pascal's triangle?

$$(1-1)^n = \binom{n}{0} - \binom{n}{1} + \binom{n}{2} - \dots + \pm
\binom{n}{n}$$

The alternating sum of the terms in each row is zero except the first row.

**20.2** Find a pattern in the sums of the rows in Pascal's triangle. Prove your
pattern holds using the binomial theorem. Also prove it holds by considering the
powerset of a set.

Substitute $x=1, y=1$ into the binomial theorem to get

$$\binom{n}{0} + \binom{n}{1} + \binom{n}{2} + \dots + \binom{n}{n} = (1+1)^n
= 2^n$$

If $|X| = n$ then $|\wp(X)| = 2^n$. We count all subsets by counting those with
0 elements, then those with 1 element, then those with 2 elements and so on, up
to those with $n$ elements.

**Question** The number of terms that I would get if I expanded $(x+y)^{2018}$
using the binomial theorem is:

1. 2016
2. 2017
3. 2018
4. 2019

**Answer** **4** There are terms for every power of $x$ from $x^0$ to
$x^{2018}$. There are 2019 numbers in $\{0,1,2,\dots,2018\}$.

## Inclusion-exclusion

In general, if $A$ and $B$ are finite sets then we have:

$$|A \cup B| = |A| + |B| - |A \cap B|$$

We can also set that if $A, B$ and $C$ are sets then we have

$$|A \cup B \cup C| = |A| + |B| + |C| - |A \cap B| - |A \cup C| - |B \cup C| +
|A \cup B \cup C|$$


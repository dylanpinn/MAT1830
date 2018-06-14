# Lecture 19: Selections and Arrangements

## Ordered selections without repetition

The number of ordered selections without repetition of $r$ elements from a set
of $n$ elements $(9 \leq r \leq n)$ is:

$$n(n-1) \dots (n-r+1) = \frac{n!}{(n-r)!}$$

When $r=n$ and all the elements of a set $S$ are ordered, we just say that this
is a _permutation_ of $S$. Our formula tells us there are $n!$ such
permutations. For example, there are $3! = 6$ permutations of the set
$\{a,b,c\}$.

## Unordered selections without repetition

A _combination_ of $r$ elements from a set $S$ is a subset of $S$ with $r$
elements.

The number of combinations of $r$ elements from a set of $n$ elements $(0 \leq r
\leq n)$ is

$$\frac{n(n-1) \dots (n-r+1)}{r!} = \frac{n!}{r!(n-r)!} = \binom{n}{r}$$

## Ordered selections with repetition

The number of sequences of $r$ terms, each from some set of $n$ elements, is

$$n \times n \times \dots \times n = n^r$$

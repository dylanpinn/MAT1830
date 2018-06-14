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

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

**Questions**

**19.1** A bank requires a PIN that this is a string of four decimal digits. How
many such PINs are there? How many are made of four different digits?

A PIN is an ordered selection with repetition of four elements from the set
$\{0, \dots, 9\}$. So there are $10^4 = 10000$ possible PINs.

A PIN with four _different_ digits is a permutation of four elements from the
set $\{0, \dots, 9\}$. So there are $\frac{10!}{6!} = 5040$ possible PINs with
four different digits.

**19.2** How many binary strings of length 5 are there? How many of these
contain exactly two 1s?

There are $2^5 = 32$ binary strings of length 5.

There are $\binom{5}{2} = 10$ that contain exactly two 1s.

## Unordered selections with repetition

A **multiset** is like a set, except we allow elements to appear more than once
and we keep track of how many times they occur.

An ordered selection of $r$ elements, with repetition allowed, from a set $X$ of
$n$ elements can be thought of a multiset with $r$ elements, each in $X$.

The number of multisets of $r$ elements, each from a set of $n$ elements, is

$$\binom{n+1-1}{r} = \frac{(n+r-1)!}{r!(n-1)!}$$

**Question**

Elodie orders a pizza from a shop that allows any 4 toppings to be chosen from a
list of 11 options. Is this choice

1. ordered without repetition
2. unordered without repetition
3. ordered with repetition
4. unordered with repetition

**Answer** **2** It's reasonable to assume that Elodie doesn't care about the
order in which the toppings are put on the pizza, and that she doesn't want to
repeat toppings.

$$\binom{11}{4} = \frac{11 \times 10 \times 9 \times 8}{4 \times 3 \times 2
\times 1} = 330$$

**Question**

Sam orders 3 pizzas from a shop that sells 7 different pizzas. Is his choice

1. ordered without repetition
2. unordered without repetition
3. ordered with repetition
4. unordered with repetition

**Answer** **4** The same pizza may be picked more than once, but the order
doesn't matter.

$$\binom{7+3-1}{3} = \binom{9}{3} = \frac{9 * 8 * 7}{3 * 2 * 1} = 84$$

## The pigeonhole principle

If $n$ items are placed in $m$ containers with $n > m$, then at least one
container has at least two items.

**Example**

If a drawer contains only blue, black and white socks and you take out four
socks without looking at them, then you are guaranteed to have two of the same
colour.

**Questions**

**19.3** In a game, each of 10 players holds a red, blue and green marbles, and
places one marble in a bag. How many possibilities are there for for the colours
of the marbles in the bag? If each player chooses their colour at random are all
of these possibilities equally likely?

There are $\binom{n+r-1}{r} = \binom{3+10-1}{10} = \binom{12}{10} =
\frac{12!}{10!2!} = 66$ possibilities.

These are _not_ equally likely. For example, the "all red" case is less likely
than having 3 red, 3 blue and 4 green.

**19.4** How many ways are there to partition a set with 10 elements into one
class of 5 elements, one class of 3 elements and one class of 2 elements? How
many ways are there to partition a set with 10 elements into one class of 6
elements and two classes of 2 elements each?

In the first case, there are $\binom{10}{5} \binom{5}{3} = 252 \times 10 = 2520$
ways.

In the second case, there are $\binom{10}{6} \frac{\binom{4}{2}}{2} = 210 \times
3 = 630$ ways.

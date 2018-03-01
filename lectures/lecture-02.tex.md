# Lecture 2 - Divisors and Primes

**Definitiion:** An _integer_ is a "whole number". It may be positive or
negative or zero.

## 2.1 Primes

A positive integer $p > 1$ is a prime if its only positive integer divisors are
1 and $p$.

**Fundamental Theorem of Arithmetic:**

_Each integer $> 1$ can be expressed in exactly one way, up to order, as a
product of primes._

**Example:**

$$210 = 2 \times 3 \times 5 \times 7$$

and this is the only product of primes which equals $210$.

## 2.2 Recognising primes

If an integer $n > 1$ has a divisor, it has a divisor $\leq \sqrt{n}$, because
for any divisor $a > \sqrt{n}$ we also have the divisor $n / a$, which is $<
\sqrt{n}$.

```
assign a the value 2.
assign prime the value T.
while a <= sqrt{n} and prime = T
  if a divides n
    give prime the value F
  else
    increase the value of a by 1.
```

## 2.3 Finding divisors

This algorithm also finds a prime divisor of $n$. Either the least $a \leq
\sqrt{n}$ which divides $n$, or, if we do not find a divisor among the $a \leq
\sqrt{n}$, $n$ itself is prime.

## 2.4 The greatest common divisor of two numbers

We can find the greatest common divisor of positive integers _m_ and _n_,
$gcd(m,n)$, without finding their prime divisors.

**Euclidean Algorithm**


```
Input: positive integers m and n with m >= n
Output: gcd(m,n)

a := m, b := n
r := remainder when a is divided by b
while r != 0 do
  a := b
  b := r
  r := remainder when a is divided by b
end
return b
```

**Definition:** Suppose _m_ and _n_ are positive integers. Then a _common
divisor_ of _m_ and _n_ is an integer which divides both _m_ and _n_.

**Example:** The common divisors of $30$ and $45$ are $1, 3, 5, 15$ (and their
negatives).

**Definition:** Suppose _m_ and _n_ are positive integer. Then the _greatest
common divisor_ (or gcd) of _m_ and _n_ is the greatest integer which is a
common divisor of _m_ and _n_.

**Examples:**

$$gcd(30,45) = 15$$
$$gcd(13,21) = 1$$
$$gcd(15,21) = 3$$

**Example:**

Find $gcd(165,120)$.

$$165 = 1 \times 120 + 45$$
$$120 = 2 \times  45 + 30$$
$$ 45 = 1 \times  30 + 15$$
$$ 30 = 2 \times  15 +  0$$

So $gcd(165,120) = 15$.

**Fact:** $gcd(a - kb, b) = gcd(a, b)$ for any positive integers $a, b, k$.

**Proof:** If _d_ is a common divisor of _a_ and _b_ then _d_ is a common
divisor of _a_ - _kb_ and _b_.

If _e_ is a common divisor of $a - kb$ and $b$ then $e$ is a common divisor of
$a$ and $b$ (note $a = (a - kb) + kb)$.

So the list of common divisors of is exactly the same as the list of common
divisors of $a$ and $b$.

So the greatest common divisor of $a - kb$ and $b$ is equal to the greatest
common divisor of $a$ and $b$.

## 2.5 The Euclidean algorithm works!

We start with the precondition $m \geq n > 0$. Then the division theorem tells
us there is a remainder $r < b$ when $a = m$ is divided by $b = n$. Repeating
the process gives successively smaller remainders, and hence the algorithm
eventually returns a value.

## 2.6 Extended Euclidean algorithm

If we have used the Euclidean algorithm to find that $gcd(m, n) = d$, we can
"work backwards" through its steps to find integers $a$ and $b$ such that $am +
bn = d$.

**Question:** Find integers $a$ and $b$ such that $353a + 78b = 1$.

We first use the Euclidean algorithm to find $gcd(353, 78)$:

$$353 = 4 \times 78 + 41$$
$$ 78 = 1 \times 41 + 37$$
$$ 41 = 1 \times 37 +  4$$
$$ 37 = 9 \times  4 +  1$$
$$  4 = 4 \times  1 +  0$$

Then we use the Extended Euclidean algorithm:

$$1 = 37 - 9 \times 4$$
$$1 = 37 - 9(41 - 37) = -9 \times 41 + 10 \times 37$$
$$1 = -9 \times 41 + 10(78 - 41) = 10 \times 78 - 19 \times 41$$
$$1 = 10 \times 78 - 19(353 - 4 \times 78) = -19 \times 353 + 86 \times 78$$

So $-19 \times 353 + 86 \times 78 = 1$. One solution is $a = -19$, $b = 86$

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

## 2.3 Finding divisors

This algorithm also finds a prime divisor of $n$. Either the least $a \leq
\sqrt{n}$ which divides $n$, or, if we do not find a divisor among the $a \leq
\sqrt{n}$, $n$ itself is prime.


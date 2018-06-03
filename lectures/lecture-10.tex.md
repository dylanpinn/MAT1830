# Lecture 10: Induction and well-ordering

In the previous lecture we were able to prove a property _P_ holds for
$0,1,2,\dots$ as follows:

**Base step.** Prove $P(0)$

**Induction step.** Prove $P(k) \Rightarrow P(k+1)$ for each natural number $k$.

This is sufficient to prove that $P(n)$ holds for all natural numbers $n$, but
it may be difficult to prove that $P(k+1)$ follows from $P(k)$. It may in fact
be easier to prove the induction step

$$P(0) \land P(1) \land \dots \land P(k) \Rightarrow P(k+1)$$

That is, it may help to assume _P_ holds for _all_ numbers before $k+1$.
Induction with this style of induction step is sometimes called the _strong
form_ of mathematical induction.

### Example 1

Prove that, for each integer $n \geq 2$, $n$ has a prime factorisation.

**Solution** Let $P(n)$ be the statement "_n_ has a prime factorisation".

**Base step.** 2 is prime. So just '2' is a prime factorisation for 2.

**Induction step.** Suppose that $P(2), P(3), \dots, P(k)$ are true for some
integer $k \geq 2$. This means that $2, 3, ..., k$ all have prime
factorisations.

We want to prove that $P(k+1)$ is true. We need to show that $k+1$ has a prime
factorisation.

If $k+1$ is prime, then just '$k+1$' is a prime factorisation for $k+1$.

If $k+1$ is not prime, then $k+1 = i \times j$ for integers $i,j$ such that $2
\leq i,j leq k$.

Because $P(i)$ is true $i$ has a prime factorisation.

Because $P(j)$ is true $j$ has a prime factorisation.

So $i \times j$ has a prime factorisation. (Just combine the prime
factorisations of _i_ and _j_.)

So $P(k+1)$ is true.

This proves that $P(n)$ is true for each integer $n \geq 2$.

### Question

Which of the following is likely to require strong induction for its proof?

1. $1+3+5+ \dots + (2n-1) = n^2$ for all $n \geq 1$.
2. $\neg(p_1 \lor p_2 \lor \dots \lor p_n \equiv \neg p_1 \land \neg p_2 \land
   \dots \land \neg p_n$ for all $n \geq 2$.
3. $a_n$ is divisible by $3$ for all $n \geq 0$, where $a_0, a_1, a_2, a_3,
   \dots$ is the sequence defined by $a_0 = 3, a_1 = 12,$ and $a_i = a_{i-1} +
   2a_{a-2}$ for $i \geq 2$.
4. Both 2 & 3.

**Answer:**

For 1., split $1+3+5+\dots+(2k+1)$ as $(1+3+5+\dots+(2k-1)) + 2k + 1$ and use
normal induction.

For 2., split $\neg(p_1 \lor p_2 \lor \dots \lor p_n $

For 3., the definition of $a_{k+1}$ uses both $a_k$ and $a_{k-1}$ so strong
induction will be useful.

So 3.

### Normal Induction Proof of 2.

Prove that $\neg(p_1 \lor p_2 \lor \dots \lor p_n \equiv \neg p_1 \land \neg
p_2 \land \dots \land \neg p_n$ for all $n \geq 2$.

#### Solution

Let $P(n)$ be the statement "$\neg (p_1 \lor p_2 \lor \dots \lor p_n \equiv \neg
p_1 \land \neg p_2 \land \dots \land \neg p_n$".

**Base Step.** $P(2)$ says "$\neg(\p_1 \lor p_2) \equiv \neg p_1 \land \neg
\p_2$" which is just DeMorgan's law.

**Induction step.** Suppose that $P(k)$ is true for some integer $k \geq 2$. So
$\neg (p_1 \lor p_2 \lor \dots \lor p_k) \equiv \neg p_1 \land p_2 \land \dots
\land \neg p_k$.

We want to prove that $P(k+1)$ is true. We need to show that $\neg (p_1 \lor p_2
\lor \dots \lor p_{k+1} \equiv \neg p_1 \land \neg p_2 \land \dots \land \neg
p_{k+1}$.

$$\neg (p_1 \lor p_2 \lor \dots \lor p_k \lor p_{k+1}$$
$$\equiv \neg ((p_1 \lor \p_2 \lor \dots \p_k) \lor p_{k+1})$$
$$\equiv \neg (p_1 \lor \p_2 \lor \dots \lor p_k) \land \neg p_{k+1}$$ by
DeMorgan's law.

$$\equiv (\neg p_1 \land \neg p_2 \land \dots \land \neg p_k) \land \neg
p_{k+1}$$

by $P(k)$

$$\equiv \neg p_1 \land \neg p_2 \land \dots \land \neg p_k \land \neg p_{k+1}$$

So $P(k+1)$ is true.

This proves that $P(n)$ is true for each integer $n \geq 2$.

## Example 2

Prove that every integer is a sum of distinct powers of 2. (Just a power of two
by itself counts as a "sum".)

The idea behind this proof is to repeatedly subtract the largest possible power
of 2. We illustrate with the number 27.

27 - largest power of 2 less than 27 $= 27 - 16 = 11$

11 - largest power of 2 less than 11 $= 11 - 8 = 3$

3 - largest power of 2 less than 3 $= 3 - 2 = 1$

Hence $27 = 16 + 8 + 2 + 1 = 2^4 + 2^3 + 2^1 + 2^0$. (It is only interesting to
find _distinct_ powers of 2, because of course each integer $\geq 1$ is a sum of
1s, and $1=2^0$.)


### Solution

Let $P(n)$ be the statement "_n_ can be written as a sum of distinct powers of
2".

**Base step.** $1=2^0$, so 1 is a sum of (one) power of 2.

**Induction step.** Suppose that $P(1), P(2), ..., P(k)$ are true for some
integer $k \geq k$. This means that $1, 2, ..., k$ can be written as a sum of
distinct powers of 2.

We want to prove that $P(k+1)$ is true. We need to show that $k+1$ can be
written as a sum of distinct powers of 2.

If $k+1$ is a power of 2, then we are finished.

If not, let $2^j$ be the greatest power of 2 less than $k+1$.

(This means that $2^j > \frac{1}{2}(k+1)$.)

Let $i = (k+1) - 2^j$. Note that $1 \leq i < 2^j$.

Because $P(i)$ is true, $i$ can be written as a sum of distinct powers of 2.
(Note that each power of 2 in this sum is smaller than $2^j$ because $i < 2^j$).

So $k+1 = 2^j + i$ can be written as a sum of distinct powers of 2.

So $P(k+1)$ is true.

This proves that $P(n)$ is true for each integer $n \geq 2$.

## Question 10.2

What else tells you every integer is a sum of distinct powers of 2?

The fact that every integer can be written as binary is equivalent to saying
every integer is a sum of distinct powers of 2.

## Question 10.3

Is every integer $geq 1$ a sum of distinct powers of 3?

No. The powers of three are $1, 3, 9, 27, ...$ So, for example, 2 is not and 7
is not.

We can write every integer $\geq 1$ as
$$a_0 3^0 + a_1 3^1 + a_2 3^2 + a_3 3^3 + \dots$$

Where $a_0, a_1, a_2, a_3, \dots$ are all in {0,1,2}, however.

## 10.2 Well-ordering and descent

Induction expresses the fact that each natural number $n$ can be reached by
starting at 0 and going upwards (e.g. adding 1) a finite number of times.

Equivalent facts are that it is only a finite number of steps, _downwards_ from
any natural number to 0, that _any descending sequence of natural numbers is
finite_, and that _any set of natural numbers has a least element._

This property is called _well-ordering_ of the natural numbers. It is often
convenient to arrange a proof to "work downwards" and appeal to well-ordering by
saying that the process of working downwards must eventually stop.

Such proofs are equivalent to induction, though they are sometimes called
"infinite descent" or similar.

## 10.3 Proofs by descent

**Example 1.** Prove that any integer $\geq 2$ has a prime divisor.

If $n$ is prime, then it is a prime divisor of itself. If not, let $n_1 < n$ be
a divisor of $n$.

If $n_1$ is prime, it is a prime divisor of $n$. If not, let $n_2 < n_1$ be a
divisor of $n_1$ (and hence of $n$).

If $n_2$ is prime, it is a prime divisor of $n$. If not, let $n_3 > n_2$ be a
divisor of $n_2$, etc.

The sequence $n > n_1 > n_2 > n_3 > \dots$ must eventually terminate, and this
means we find a prime divisor of $n$.

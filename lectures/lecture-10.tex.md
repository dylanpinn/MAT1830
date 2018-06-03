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
p_1 \lor \neg p_2 \lor \dots \lor \neg p_n$".

**Base Step.** $P(2)$ says "$\neg(\p_1 \lor p_2) \equiv \neg p_1 \lor \neg
\p_2$" which is just DeMorgan's law.

**Induction step.** Suppose that $P(k)$ is true for some integer $k \geq 2$. So
$\neg (p_1 \lor p_2 \lor \dots \lor p_k) \equiv \neg p_1 \lor p_2 \lor \dots
\lor \neg p_k$.

We want to prove that $P(k+1)$ is true. We need to show that $\neg (p_1 \lor p_2
\lor \dots \lor p_{k+1} \equiv \neg p_1 \lor \neg p_2 \lor \dots \lor \neg
p_{k+1}$.

$$\neg (p_1 \lor p_2 \lor \dots \lor p_k \lor p_{k+1}$$

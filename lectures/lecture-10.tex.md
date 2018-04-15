# Lecture 10: Induction and well-ordering

In the previous lecture we were able to prove a property _P_ holds for 0,1,2,...
as follows:

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
factorisations of _i_ and _j_.)A

So $P(k+1)$ is true.

This proves that $P(n)$ is true for each integer $n \geq 2$.

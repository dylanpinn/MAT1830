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

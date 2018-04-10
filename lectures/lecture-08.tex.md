# Lecture 8: Predicate Logic

"She is the most famous actor in the world." is different from "She is the most
famous mathematician in the world."

## 8.1 Valid sentences

A sentence is valid in predicate logic is _valid_ if it has value T under all
interpretations.

## 8.2 Interpretations

$\forall xM(x)$

Two of the possible interpretations of this are:

$M(x)$ is "she is at least as famous as $x$" and $x$ ranges over all actors.

$M(x)$ is "she is at least as famous as $x$" and $x$ ranges over all
mathematicians.

### Question 8.1

Give interpretations which make the following false.

$$\exists nP(n) \to \forall nP(n)$$

n ranges over the positive integers and $P(n)$ is "n is prime"

$$\forall x \forall y(R(x,y) \to R(x,y))$$

x and y range over the real numbers and $R(x,y)$ is "$x < y$".

### Question

Which of the following interpretations makes $\forall m \exists n S(m,n)$ false?

$m$ and $n$ range over the integers and $S(m,n)$ is "$m = 2n$".

## 8.3 Recognising valid sentences

**Example**: $\forall xP(x) \to \exists xP(x)$ is true for all properties P, and
hence is valid.

## 8.4 Consequence and equivalence

As in propositional logic, a sentence $\psi$ is a _logical consequence_ of a
sentence $\phi$ if any interpretation which makes $\phi$ true makes $\psi$ true.
Again we write $\phi \Rightarrow \psi$ if $\psi$ is a consequence of $\phi$, and
this the same as saying $\phi \to \psi$ is valid.

### Question 8.2

Give an interpretation to show that $\exists x(P(x) \land L(x))$ and $\exists
xP((x) \land \neg L(x))$ are not equivalent.

Let $x$ range over the integers, and let $P(x)$ be "10 divides $x$" and $L(x)$
be "$x$ is even".

Then $\exists x(P(x) \land L(x))$ is true because there is an integer that is
divisible by 10 and is even (20 for example).

But $\exists x(P(x) \land \neg L(x))$ is false because there is no integer that
is divisible by 10 and is odd.

So there is an interpretation in which one of these formulas is true and the
other is false. This means they're not logically equivalent.

### Question 8.3

Does $\forall x \exists yR(x,y) \Rightarrow \exists y \forall xR(x,y)$?

No. Let $x$ and $y$ range over the real numbers and $R(x,y)$ be $x < y$. Then
$\forall x \exists yR(x,y)$ is true but $\exists y \forall xR(x,y)$ is false.

### Question 8.4

Does $\exists y \forall xR(x,y) \Rightarrow \forall x \exists yR(x,y)$?

Yes. If $\exists y \forall xR(x,y)$ is true then there is one specific $y$, say
$y \prime$, such that $R(x, y \prime) \equiv T$ for all $x$. So then for any $x$
there is a value of $y$, namely $y \prime$, such that $R(x,y \prime) \equiv T$.
So $\forall x \exists yR(x,y)$ is true.

### Question

Does $\forall xP(x) \lor \forall xQ(x) \Rightarrow \forall x(P(x) \lor Q(x))$?

**Thinking:** The LHS is effectively $(\forall xP(x)) \lor (\forall xQ(x))$ It's
an $\lor$ of two separate $\forall$ statements.

**Answer:** Yes. If the first statement is true, then $P(x)$ is true for all $x$
in the range or $Q(x)$ is true for all $x$ in the range. In each case this will
mean that $P(x) \lor Q(x)$ is true for all $x$ in the range, and so the second
statement will be true.

### Question

Does $\forall x(P(x) \lor Q(x)) \Rightarrow \forall xP(x) \lor \forall xQ(x)$?
If not, give an interpretation which proves this.

**A.** No. $x$ ranges over positive integers, $P(x)$ is $x \leq 10$ and $Q(x)$
is $x \geq 1$.

**B.** No. $x$ ranges over positive integers, $P(x)$ is $x \leq 5$ and $Q(x)$
is $x \geq 15$.

**C.** No. $x$ ranges over positive integers, $P(x)$ is $x \leq 10$ and $Q(x)$
is $x \geq 11$.

**D.** Yes.

**Answer:** To show $\forall x(P(x) \lor Q(x)) \neg \Rightarrow \forall xP(x)
\lor \forall xQ(x)$ we need to make the LHS true and the RHS false.

In A, both LHS and RHS are true.

In B, the LHS is false.

In C, the LHS is true and the RHS is false, as required.

D cannot be correct because C shows $\forall x(P(x) \lor Q(x)) \neg \Rightarrow
\forall xP(x) \lor \forall xQ(x)$.

So C.

## 8.5 Useful equivalences

Two important equivalences involving quantifiers are:

$$\neg \forall xP(x) \equiv \exists x \neg P(x)$$
$$\neg \exists xP(x) \equiv \forall x \neg P(x)$$

These makes sense intuitively. For example, $\neg \forall xP(x)$ means $P(x)$ is
not true for all $x$, hence there is an $x$ for which $P(x)$ is false, that is,
$\exists x \neg P(x)$.

### Question 8.5

Explain why $\neg \forall p \forall tF(p,t) \equiv \exists p \exists t \neg
F(p,t)$.

$$\neg \forall p \forall tF(p,t) \equiv \exists p \neg \forall tF(p,t)$$
$$\equiv \exists p \exists t \neg F(p,t)$$

Intuitively: $\neg \forall p \forall tF(p,t)$ means it is not the case that
$F(p,t)$ is true for all combinations of $p$ and $t$. This is the same as saying
that there is some combination of $p$ and $t$ for which $F(p,t)$ is false.

## 8.6 Simplification

The infinite de Morgan's laws allow a certain simplification of predicate
formulas by "pushing $\neg$ inside quantifiers."

**Example:**

$$\neg \forall x \exists yQ(x,y) \equiv \exists x \neg \exists yQ(x,y)$$
$$\equiv \exists x \forall y \neg Q(x,y)$$

It is in fact possible to transform any quantified statement in predicate logic
to an equivalent with all quantifiers at the front.

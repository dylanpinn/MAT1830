# Lecture 7: Predicates and quantifiers

"Every real number is positive or negative."

False! But we want to be able to write it in logic and do things with it.

For example, we'd like to be able to say that its negation is "There is a real
number which is neither positive or negative."

## 7.1 Predicates

$P(n)$: "n is prime."

| $n$ | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | $\dots$ |
|-----|---|---|---|---|---|---|---|---|---|----|----|---------|
| $P(n)$ |F|T | T | F | T | F | T | F | F | F  |  T | $\dots$ |

## 7.2 Building sentences from predicates

_Quantifiers_:

- $\forall$ (meaning "for all")
- $\exists$ (meaning "there exists" or "there is").

## 7.3 Quantifiers and connectives

### Question 7.1

Write down "roses are red" in predicate logic using:

rose(x): "x is a rose"

red(x): "x is red"

$\forall x(\text{rose}(x) \to \text{red}(x))$

### Question 7.2

$$P(n): \text{"n is prime."}$$
$$E(n): \text{"n is even."}$$

What does $P(n) \land \neg E(n)$ mean?

"n is prime and n is not even." OR "n is an odd prime."

### Question 7.3

$$\text{pol}(x): \text{"x is a politician."}$$
$$\text{liar}(x): \text{"x is a liar."}$$

"All politicians are liars."

$\forall x(\text{pol}(x) \to \text{liar}(x))$

"Some politicians are liars."

$\exists x(\text{pol}(x) \land \text{liar}(x))$

"No politicians are liars."

$\forall x(\text{pol}(x) \to \neg \text{liar}(x))$

"Some politicians are not liars."

$\exists x(\text{pol}(x) \land \neg \text{liar}(x))$

### Question

Let $n$ range over the integers.

$P(n):$ "n is prime."

$E(n):$ "n is even."

$G(n):$ "$n \geq 3$."

What does $\exists n((P(N) \land G(N)) \to \neg E(n))$ mean?

"All primes are greater than or equal to 3 are odd."

## 7.4 Alternating quantifiers

### Order of quantifiers

Let x and y range over all people.

$\forall x \exists y(x \text{ is friends with } y)$ Think: ∀x(∃y(x is friends
with y)).

$\exists y(x \text{ is friends with } y)$ is saying “x has a friend.”

$\forall x \exists y(x \text{ is friends with } y)$ is saying “Everybody has a
friend.”

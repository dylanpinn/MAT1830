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

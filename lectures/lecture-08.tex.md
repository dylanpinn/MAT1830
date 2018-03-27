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

### Question 8.2

Give an intepretation

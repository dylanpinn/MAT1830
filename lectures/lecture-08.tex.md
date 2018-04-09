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



# Lecture 4 - Logic

## Question 4.1

Which of the following are propositions?

$$1 + 1 = 3 \text { Yes } \text{ (false) }$$
$$1 + 1 \text { No}$$
$$3 \text { divides } 9 \text{ Yes } \text{ (true)}$$
$$3 \div 7 \text { No}$$

## 4.1 Connectives ∧, ∨ and ¬

Define $\land$ by the following _truth table_:

| $p$ | $q$ | $p \land q$ |
|-----|-----|-------------|
|  T  |  T  |     T       |
|  T  |  F  |     F       |
|  F  |  T  |     F       |
|  F  |  F  |     F       |

Define $\lor$ by the _truth table_:

| $p$ | $q$ | $p \lor q$ |
|-----|-----|------------|
|  T  |  T  |     T      |
|  T  |  F  |     T      |
|  F  |  T  |     T      |
|  F  |  F  |     F      |

Define $\neg$ by the _truth table_:

| $p$ | $\neg p$ |
|-----|----------|
|  T  |  F       |
|  F  |  T       |

### Notation

$$\land \text { "and" }$$
$$\lor \text { "or" (inclusive) }$$
$$\neg \text { "not" }$$

### Order of precedence

$\neg$ has precedence over the other connectives.

For example, $\neg p \lor q$ means $ (\neg p) \lor q$.

### Example

Find the truth tables for $p \land (q \lor r)$ and $(p \land q) \lor (p \land
r)$

| $p$ | $q$ | $r$ | $q \lor r$ | $p \land (q \lor r)$ | $p \land q$ |
|-----|-----|-----|------------|----------------------|------------|
|  T  |  T  |  T  |     T      |     T                |     T      |
|  T  |  T  |  F  |     T      |     T                |     T      |
|  T  |  F  |  T  |     T      |     T                |     F      |
|  T  |  F  |  F  |     F      |     F                |     F      |
|  F  |  T  |  T  |     T      |     F                |     F      |
|  F  |  T  |  F  |     T      |     F                |     F      |
|  F  |  F  |  T  |     T      |     F                |     F      |
|  F  |  F  |  F  |     F      |     F                |     F      |

| $p \land r$ | $(p \land q) \lor (q \and r)$ |
|-------------|-------------------------------|
|     T       |     T                         |
|     F       |     T                         |
|     T       |     T                         |
|     F       |     F                         |
|     F       |     F                         |
|     F       |     F                         |
|     F       |     F                         |
|     F       |     F                         |

### Question

What must the truth values of $p$ and $q$ be to make $p \land (\neg p \lor \neg
q)$ true?

#### Answer

$p$ mus be T because otherwise the expression would evaluate to F.

The expression is then $T \land (F \lor \neq q)$.

To make the bracketed part evaluate to T we need $neg q$ to be T.

Or in other words we need $q$ to be F.

## 4.2 Implication

$$\Rightarrow \text { "implies" }$$

We define $\Rightarrow$ by the _truth table_:

| $p$ | $q$ | $p \Rightarrow q$ |
|-----|-----|------------|
|  T  |  T  |     T      |
|  T  |  F  |     F      |
|  F  |  T  |     T      |
|  F  |  F  |     T      |

### Question 4.2

f: "foo"

b: "bar"

"if foo, then bar" $f \Rightarrow b$

"bar if foo" $f \Rightarrow b$

"bar only if foo" $b \Rightarrow f$

"foo implies not bar" $f \Rightarrow \neg b$

"foo is sufficient for bar" $f \Rightarrow b$

"foo is necessary for bar" $b \Rightarrow f$

## 4.3 Other connectives

$$\iff \text { "if and only if" }$$
$$\veebar \text { "exclusive or" }$$

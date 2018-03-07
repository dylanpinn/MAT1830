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

| $p$ | $q$ | $r$ | $q \lor r$ | $p \land (q \lor r)$ |
|-----|-----|-----|------------|----------------------|
|  T  |  T  |  T  |     T      |     T                |
|  T  |  T  |  F  |     T      |     T                |
|  T  |  F  |  T  |     T      |     T                |
|  T  |  F  |  F  |     F      |     F                |
|  F  |  T  |  T  |     T      |     F                |
|  F  |  T  |  F  |     T      |     F                |
|  F  |  F  |  T  |     T      |     F                |
|  F  |  F  |  F  |     F      |     F                |

| $p \land q$ | $p \land r$ | B |
|-------------|-------------|-------------------------------|
|     T       |     T       |     T                         |
|     T       |     F       |     T                         |
|     F       |     T       |     T                         |
|     F       |     F       |     F                         |
|     F       |     F       |     F                         |
|     F       |     F       |     F                         |
|     F       |     F       |     F                         |
|     F       |     F       |     F                         |

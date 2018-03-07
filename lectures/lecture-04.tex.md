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

We define $\iff$ by the _truth table_:

| $p$ | $q$ | $p \iff q$ |
|-----|-----|------------|
|  T  |  T  |     T      |
|  T  |  F  |     F      |
|  F  |  T  |     F      |
|  F  |  F  |     T      |

$$\veebar \text { "exclusive or" }$$

We define $\veebar$ by the _truth table_:

| $p$ | $q$ | $p \veebar q$ |
|-----|-----|------------|
|  T  |  T  |     F      |
|  T  |  F  |     T      |
|  F  |  T  |     T      |
|  F  |  F  |     F      |

### Question 4.3

"Would you like coffee or tea?" - exclusive

"Oranges or lemons are a good source of vitamin C." - inclusive

"He will arrive in a minute or two." - exclusive

### Question

What must the truth values of _p_ and _q_ be to make $q \Rightarrow (p \veebar
q)$ false?

#### Answer

For $q \Rightarrow (p \veebar q)$ to be F we need $q$ to be T and $p \veebar q$
to be F.

$q$ must be T and $p \veebar T$ must be F.

This means that $p$ must be T (checking both cases for $p$).

## 4.4 Remarks

1. The symbols $\land$ and $\lor$ are intentionally similar to the symbols $\cap$
   and $\cup$ for set intersection and union because
   $$x \in A \cap B  \Leftrightarrow (x \in A) \land (x \in B)$$
   $$x \in A \cup B  \Leftrightarrow (x \in A) \lor (x \in B)$$
2. The "exclusive or" function $\veebar$ is written XOR in some programming
   languages.
3. If we write 0 for F and 1 for T then $\veebar$ becomes the function:

| $p$ | $q$ | $p \veebar q$ |
|-----|-----|------------|
|  1  |  1  |     0      |
|  1  |  0  |     1      |
|  0  |  1  |     1      |
|  0  |  0  |     0      |

  This is known as the "mod 2 sum", because $1 + 1 = 2 \equiv 0$ (mod 2)


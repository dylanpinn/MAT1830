# Lecture 5: Tautologies and logical equivalence

## 5.1 Tautologies and contradictions

A sentence in propositional logic:

* a _tautology_ if it has value **T** under all interpretations;
* a _contradiction_ if it has value **F** under all interpretations.

### Example

"If Morne Morkel is limping and AB de Villiers is looking grumpy, then South
Africa are losing the test match."

_p_: "Morne Morkel is limping."

_q_: "AB de Villiers is looking grumpy."

_r_: "South Africa are losing the test match."

$$(p \land q) \to r$$

_p_ could be **T** or **F**, _q_ could be **T** or **F**, and _r_ could be **T**
or **F**.

So there are $2 \times 2 \times 2 = 8$ ways to assign truth values to this
statement.

That's why there would be eight rows in the truth table.

### Question

How many ways are there to assign truth values to the following statement?

$$\neg((\neg p_1 \land p_2) \lor ((p_3 \lor \neg p_4) \land p_1)) \to (p_2 \land
p_5)$$

$$ 2 \times 2 \times 2 \times 2 \times 2 = 32$$

### Question 5.1

There are two possibilities for each of the variables and this gives a total of $2
\times 2 \times \dots \times 2 = 2^n$ possibilities.

## 5.2 Logical equivalence

Why should $p \to q$ mean the same as $\neg p \or q$?

"If you train hard, then you'll finish the marathon."

"You won't train hard or you'll finish the marathon."

"If that's a lion, then we're dead."

"That's not a lion or we're dead."

The expression:

$$\frac{x^3 - 3x^2 + 3x + 1}{(x - 1)^4} \times \frac{x^3 - x}{x + 1}$$

is actually the same as the expression $$x (\text{ for } x \not= -1, 1)$$, but
the second expression is nicer.

Similarly $$((p \land (p \lor q)) \to (\neg p \land q)) \land (p \lor \neg q)$$
is logically equivalent to $$\neg q$$

## Useful equivalences

The following equivalences are the most frequently used in this "algebra of
logic".

### Equivalence law

$$p \leftrightarrow q \equiv (p \to q) \land (q \to p)$$

### Implication law

$$p \to q \equiv (\neg p) \lor q$$

### Double Negation law

$$\neg \neg p \equiv p$$

### Idempotent laws

$$ p \land p \equiv p$$
$$ p \lor p \equiv p$$

### Commutative laws

$$p \land q \equiv q \land p$$
$$p \lor q \equiv q \lor p$$

### Associative laws

$$p \land (q \land r) \equiv (p \land q) \land r$$
$$p \lor (q \lor r) \equiv (p \lor q) \lor r$$

### Distributive laws

$$p \land (q \lor r) \equiv (p \land q) \lor (p \land r)$$
$$p \lor (q \land r) \equiv (p \lor q) \land (p \lor r)$$

### De Morgans's laws

$$\neg(p \land q) \equiv (\neg p) \lor (\neg q)$$
$$\neg(p \lor q) \equiv (\neg p) \land (\neg q)$$

### Identity laws

$$p \land T \equiv p$$
$$p \lor F \equiv p$$

### Annihilation laws

$$p \land F \equiv F$$
$$p \lor T \equiv T$$

### Inverse laws

$$p \land (\neg p) \equiv F$$
$$p \lor  (\neg p) \equiv T$$

### Absorption laws

$$p \land (p \lor q) \eqiuv p$$
$$p \lor (p \land q) \eqiuv p$$

### Question

What simpler sentence is $((p \land \neg \neg p) \lor \neg p) \lor (q \land r)$
logically equivalent to?

#### Answer

$$((p \land \neg \neg p) \lor \neg p) \lor (q \land r)$$
$$\equiv ((p \land p) \lor \neg p) \lor (q \land r)$$ (double negation law)
$$\equiv (p \lor \neg p) \lor (q \land r)$$ (idempotent law)
$$\equiv T \lor (q \land r)$$ (inverse law)
$$\equiv T$$ (annihilation law)

### Question 5.2

First show that $\neg (p \land q) \equiv \neg (p \lor \neg q)$.

| $p$ | $q$ | $p \land q$ |
|-----|-----|-------------|
|  T  |  T  |      T      |
|  T  |  F  |      F      |
|  F  |  T  |      F      |
|  F  |  F  |      F      |

| $\neg p$ | $\neg q$ | $\neg p \land \neg q$ |
|----------|----------|-----------------------|
|     F    |     F    |           F           |
|     F    |     T    |           T           |
|     T    |     F    |           T           |
|     T    |     T    |           T           |

The columns for $\neg (p \land q)$ and $\neg p \lor \neg q$ are the same so
$\neg (p \land q) \equiv \neg (p \lor \neg q)$.

Next show that $\neg (p \lor q) \equiv \neg p \land \neg q$.

| $p$ | $q$ | $p \lor q$  | $\neg (p \land q)$ |
|-----|-----|-------------|--------------------|
|  T  |  T  |      T      |        F           |
|  T  |  F  |      T      |        F           |
|  F  |  T  |      T      |        F           |
|  F  |  F  |      F      |        T           |

| $\neg p$ | $\neg q$ | $\neg p \land \neg q$ |
|----------|----------|-----------------------|
|     F    |     F    |           F           |
|     F    |     T    |           T           |
|     T    |     F    |           T           |
|     T    |     T    |           T           |

The columns for $\neg (p \lor q)$ and $\neg p \lor \neg q$ are the same so
$\neg (p \lor q) \equiv \neg (p \land \neg q)$.

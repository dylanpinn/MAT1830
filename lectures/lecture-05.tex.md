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

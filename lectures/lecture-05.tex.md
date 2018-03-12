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

$p$ could be **T** or **F**, $q$ could be **T** or **F**, and $r$ could be **T**
or **F**.

So there are $2 \times 2 \times 2 = 8$ ways to assign truth values to this
statement.

That's why there would be eight rows in the truth table.

### Question

How many ways are there to assign truth values to the following statement?

$$\not((\not p_1 \land p_2) \lor ((p_3 \lor \not p_4) \land p_1)) \to (p_2 \land
p_5)$$

$$ 2 \times 2 \times 2 \times 2 \times 2 = 32$$

### Question 5.1

There are two posibilites for each of the variables and this gives a total of $2
\times 2 \times \dots \times 2 = 2^n$ possibilities.

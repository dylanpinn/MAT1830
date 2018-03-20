# Lecture 6 - Rules of inference

## 6.1 The rule of replacement

Why can we say that $(\frac{2x}{2}^2 = x^2$?

Because $\frac{2x}{2} = x$.

And there's a rule of replacement.

It's the same in logic except with $\equiv$ instead of $=$.

So we can say that $p \land \neg(q \lor r) \equiv (p \land (\neg q \land \neg
r)$ because $\neg (q \lor r) \equiv \neg q \land \neg r$.

### Question 6.1

What does "no pain, no gain" mean as an implication?

$$ \text{"no pain" } \to \text{ "no gain"}$$

### Question 6.2

What is its contrapositive?

$$\neg \text{ "no pain" } \to \neg \text{ "no pain"}$$
OR
$$\text{"gain "} \to \text{ "pain"}$$

### Question

What is the contrapositive of "If $x \equiv 0$ (mod 6), then $2x \equiv 0$ (mod
6)"?

"If $2x \not\equiv 0$ (mod 6), then $x \not\equiv 0$ (mod 6)."

### Contrapositives are not negations!

Don't confuse contrapositives with negations.

We've seen that the contrapositive of $p \to q$ is $\neg q \to \neg p$ and that
is logically equivalent to the original statement.

The negation of $p \to q$ is $\neg (p \to q)$. It is not logically equivalent to
the original statement.

$$\neg (p \to q) \equiv \neg (\neg p \lor q)$$
$$\equiv \neg \neg p \land \neg q$$
$$\equiv p \land \neg q$$

"If he were the dean then he'd have pants on.""

**Contrapositive:** "If he doesn't have pants on then he isn't the dean."

Logically equivalent to the original statement!

**Negation:** "He's the dean and he doesn't have pants on."

True exactly when the original statement is false.

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

### Question 6.3

Write down the following sentences as implications and then write their
contrapositives.

**Sentence:** "You can't make an omelette without breaking eggs."

**Implication:** "you made an omelette" $\to$ "you broke eggs."

**Contrapositive:** "you didn't break eggs" $\to$ "you didn't make an omelette"

**Sentence:** "If $n$ is even, so is $n^2$."

**Implication:** "n is even" $\to$ "$n^2$ is even"

**Contrapositive:** "$n^2$ is odd" $\to$ "n is odd"

**Sentence:** "Haste makes waste."

**Implication:** "haste" $\to$ "waste"

**Contrapositive:** "no waste" $\to$ "no haste"

### Question

Suppose "If x is mimsy, then x is not frumious" is true. What can we say about
whether the following statements are true?

1. "If x is not frumious, then x is mimsy."
2. "x is mimsey and x is frumious."
3. "if x is frumious, then x is not mimsy."

(1) maybe, (2) false, (3) true

### Question 6.4

Show that $p \to (q \to (r \to p))$ is a tautology.

$$\equiv \neg p \lor (q \to (r \to p))$$
$$\equiv \neg p \lor (\neg q \lor (r \to p))$$
$$\equiv \neg p \lor (\neg q \lor (\neg r \lor p))$$
$$\equiv \neg p \lor \neg q \lor \neg r p$$
$$\equiv (\neg p \lor p) \lor \neg q \lor \neg r$$
$$\equiv T \lor \neg q \neg r$$
$$\equiv T$$

### Question 6.5

Find a tautology form with $n$ variables which is $p \to (q \to p)$ for $n=2$
and $p \to (q \to (r \to p))$ for $n=3$.

$$p_1 \to (p_2 \to (p_3 \to (p_4 \to \dots (p_{n-1} \to (p_n \to p_1 )) \dots
)))$$

## 6.2 Modus ponens

The tautology $((p \to q) \land p) \to q$ also translates into a rule of
inference known as _modus ponens:_ from sentences $p \to q$ and $p$ we can infer
the sentence $q$.

## 6.3 Logical consequence

A sentence $\psi$ is a _logical consequence_ of a sentence $\phi$, if $\psi = T$
whenever $\psi = T$. We write this as $\phu \implies \psi$.

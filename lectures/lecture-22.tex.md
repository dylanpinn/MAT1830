# Lecture 22: Conditional probability and Bayes' theorem

## Conditional probability

Conditional probabilities measure the likelihood of an event, given that some
other event occurs.

For events _A_ and _B_, the _conditional probability of A given B_ is

$$\Pr(A|B) = \frac{\Pr(A \cap B)}{\Pr(B)}$$

This definition also implies that $\Pr(A \cap B) = \Pr(A|B)\Pr(B)$.

**Example** A spinner is spun. Let _A_ be the event that the result was at elast
3 and _B_ be the event that the result was even. What is $\Pr(A|B)$?

- $\Pr(A \cap B) = \Pr(4) = \frac{1}{8}$
- $\Pr(B) = \Pr(2) + \Pr(4) = \frac{1}{4} + \frac{1}{8} = \frac{3}{8}$
- Thus, $\Pr(A|B) = \frac{\Pr(A \cap B)}{\Pr(B)} =
  \frac{\frac{1}{8}}{\frac{3}{8}} = \frac{1}{3}$.

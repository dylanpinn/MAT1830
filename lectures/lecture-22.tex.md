# Lecture 22: Conditional probability and Bayes' theorem

## Conditional probability

Conditional probabilities measure the likelihood of an event, given that some
other event occurs.

For events _A_ and _B_, the _conditional probability of A given B_ is

$$\Pr(A|B) = \frac{\Pr(A \cap B)}{\Pr(B)}$$

This definition also implies that $\Pr(A \cap B) = \Pr(A|B)\Pr(B)$.

**Example** A spinner is spun. Let _A_ be the event that the result was at least
3 and _B_ be the event that the result was even. What is $\Pr(A|B)$?

- $\Pr(A \cap B) = \Pr(4) = \frac{1}{8}$
- $\Pr(B) = \Pr(2) + \Pr(4) = \frac{1}{4} + \frac{1}{8} = \frac{3}{8}$
- Thus, $\Pr(A|B) = \frac{\Pr(A \cap B)}{\Pr(B)} =
  \frac{\frac{1}{8}}{\frac{3}{8}} = \frac{1}{3}$.

**Example** A binary string of length 6 is generated uniformly at random. Let
_A_ be the event that is the first bit is a 1 and _B_ be the event that the
string contains two 1s. What is $\Pr(A|B)$?

There are $2^6$ strings in our sample space. Now $A \cap B$ occurs when the
first bit is a 1 and the rest of the string contains one 1. There are
$\binom{5}{1}$ such strings and so $\Pr(A \cap B) = \frac{\binom{5}{1}}{2^6}$.
Also, there are $\binom{6}{2}$ strings containing two 1s and so $\Pr(B) =
\frac{\binom{6}{2}}{2^6}$. Thus,

$$\Pr(A|B) = \frac{\Pr(A \cap B)}{\Pr(B)} = \frac{\binom{5}{1}}{\binom{6}{2}} =
\frac{1}{3}$$.

**Exercise** A normal die is rolled. Let _A_ be the event that the result is an
odd number. Let _B_ be the event that the result is a square number.

- **A:** $\Pr(A|B) = \frac{1}{2}$ and $\Pr(B|A) = \frac{1}{4}$
- **B:** $\Pr(A|B) = \frac{1}{2}$ and $\Pr(B|A) = \frac{1}{3}$
- **C:** $\Pr(A|B) = \frac{1}{6}$ and $\Pr(B|A) = \frac{1}{6}$
- **D:** $\Pr(A|B) = \frac{2}{3}$ and $\Pr(B|A) = \frac{1}{4}$

**ANS: B:** Since $A \cap B = \{1\}$ we see that $\Pr(A \cap B)= \frac{1}{6}$.
So

$$\Pr(A|B) = \frac{\Pr(A \cap B)}{\Pr(B)} = \frac{\frac{1}{6}}{\frac{1}{3}} =
\frac{1}{2}$$

$$\Pr(B|A) = \frac{\Pr(A \cap B)}{\Pr(B)} = \frac{\frac{1}{6}}{\frac{1}{2}} =
\frac{1}{3}$$
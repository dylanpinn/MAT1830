# Lecture 21: Probability and Independence

Why should you care?

- Many algorithms work better if they make random choices. For example,
  "quicksort" can avoid its worst case by making random choices. The Pollard-p
  factorisation algorithm makes random choices as it searches for integer
  factors. To understand such algorithms you must understand probability.
- Many mathematical objects can only be constructed randomly. For example,
  graphs with large chromatic number but no short cycles.
- Random models are useful for studying the structure of real world networks.
  And of traffic modelling on them.
- Probability also helps in machine learning, reliability modelling, simulation
  algorithms, data mining, speech recognition, etc.

Probability gives us a way to model random processes mathematically. These
processes could be anything from the rolling of dice, to radioactive decay of
atoms, to the performance of a stock market index. The mathematical environment
we work in when dealing with probabilities is called a probability space.

## Probability spaces

A _probability space_ consists of:

- a set $S$ called a _sample space_ which contains all the possible _outcomes_
  of the random process; and
- a _probability_ function $\Pr: S \rightarrow [0,1]$ such that the sum of the
  probabilities of the outcomes in $S$ is 1.

Each time the process occurs it should produce exactly one outcome (never zero
or more than one). The probability of an outcome is a measure of the likeliness
that it will occur. It is given as a real number between 0 and 1 inclusive,
where 0 indicates that the outcome cannot occur and 1 indicates that the outcome
must occur.


**Example** Rolling a fair six-sided die could be modelled by a probability
space with sample space $S = \{1,2,3,4,5,6\}$ and probability function $\Pr$
given as follows.

![](images/L21-P6.png)

A sample space like this one where every outcome has an equal probability is
sometimes called a _uniform sample space_. Outcomes from a uniform sample space
are said to have been take _uniformly at random._

## Events

An _event_ is a subset of the sample space.

**Example** In the die rolling example with $S = \{1,2,3,4,5,6\}$, we could
define the event of rolling at least a 3. Formally, this would be the set
$\{3,4,5,6\}$. We could also define the event of rolling an odd number as the
set $\{1,3,5\}$.

The probability of an event $A$ is the sum of the probabilities of the outcomes
in $A$.

## Operations on events

Because events are defined as sets we can perform set operations on them. If $A$
and $B$ are events for a sample space $S$, then

- $A \cup B$ is the event "A or B"
- $A \cap B$ is the event "A and B"
- $\bar{A}$ is the event "not A"

We always take the sample space as our universal set, so $\bar{A}$ means $S-A$.

**Exercise** If $A$ and $B$ are any two events then $\Pr (A \cap B)$

- **A** $= \Pr(A) + \Pr(B)$
- **B** $= \Pr(A) \times \Pr(B)$
- **C** $= \Pr(A) - \Pr(B)$
- **D** $= \Pr(A) \div \Pr(B)$
- **E** $\leq \min(\Pr(A), \Pr(B))$

**ANS: E** In general $\Pr(A \cap B)$ depends on the events _A_ and _B_, but the
only thing you can be sure of is that it is no more than the probability of
either of the individual events.

## Independent events
We say that two events are _independent_ when the occurrence or non-occurrence
of one event does not affect the likelihood of the other occurring.

Two events _A_ and _B_ are _independent_ if

$$\Pr(A \cap B) = \Pr(A)\Pr(B)$$

**Example** A binary string of length 3 is generated uniformly at random. The
event _A_ that the first bit is a 1 is independent from the event _B_ that the
second bit is a 1. But _A_ is _not_ independent of the event _C_ that the string
contains exactly two 1s.

Formally, the sample space is $S = \{111, 110, 101, 100, 011, 010, 001, 000\}$
and $\Pr(s) = \frac{1}{8}$ for any $s \in S$. So,

$$A = \{111, 110, 101, 100\} \Rightarrow \Pr(A) = \frac{1}{2}$$
$$B = \{111, 110, 011, 010\} \Rightarrow \Pr(B) = \frac{1}{2}$$
$$C = \{110, 101, 011\} \Rightarrow \Pr(C) = \frac{3}{8}$$
$$A \cap B = \{111, 110\} \Rightarrow \Pr(A \cap B) = \frac{1}{4}$$
$$A \cap C = \{110, 101\} \Rightarrow \Pr(A \cap B) = \frac{1}{4}$$

So $\Pr(A \cap B) = \Pr(A)\Pr(B)$ but $\Pr(A \cap C) \not = \Pr(A)\Pr(C)$.

**Questions**

An integer is chosen uniformly at random from the set $\{1,2, \dots, 30\}$. Let
_A_ be the event that the integer is at most 20. Let _B_ be the event that the
integer is divisible by 6. Let _C_ be the event that the integer's last digit is
a 5.

**21.1** Write _A_, _B_ and _C_ as sets, and find their probabilities.

- $A = \{1,2,\dots, 19,20\}$. $\Pr(A) = \frac{2}{3}$.
- $B = \{6,12,18,24,30\}$. $\Pr(B) = \frac{1}{6}$.
- $C = \{5,15,25\}$. $\Pr(C) = \frac{1}{10}$.

**21.2** Find the probabilities of $A \cup B$, $A \cup C$, and $B \cup C$. Which
pairs of _A_, _B_, _C_ are mutually exclusive?

$\Pr(A \cup B) = \frac{11}{15}, \Pr(A \cup C) = \frac{7}{10}, \Pr(B \cup C) =
\frac{4}{15}$. The only pair which are mutually exclusive is _B_ and _C_.

**21.3** Find the probabilities of $A \cap B$, $A \cap C$, and $B \cap C$. Which
pairs of $A$, $B$, $C$ are independent?

$\Pr(A \cap B) = \frac{1}{10}, \Pr(A \cap C) = \frac{1}{15}, \Pr(B \cap C) = 0$.
The only pair which are independent is A and C.

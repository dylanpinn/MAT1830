# Lecture 12: Probability and Independence

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

- a set <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> called a _sample space_ which contains all the possible _outcomes_
  of the random process; and
- a _probability_ function <img src="/lectures/tex/dae2fb2d51b864f3b89cdf9bdc2d9c6d.svg?invert_in_darkmode&sanitize=true" align=middle width=100.79876069999997pt height=24.65753399999998pt/> such that the sum of the
  probabilities of the outcomes in <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> is 1.

Each time the process occurs it should produce exactly one outcome (never zero
or more than one). The probability of an outcome is a measure of the likeliness
that it will occur. It is given as a real number between 0 and 1 inclusive,
where 0 indicates that the outcome cannot occur and 1 indicates that the outcome
must occur.

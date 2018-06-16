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

- a set <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> called a _sample space_ which contains all the possible _outcomes_
  of the random process; and
- a _probability_ function <img src="/lectures/tex/dae2fb2d51b864f3b89cdf9bdc2d9c6d.svg?invert_in_darkmode&sanitize=true" align=middle width=100.79876069999997pt height=24.65753399999998pt/> such that the sum of the
  probabilities of the outcomes in <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> is 1.

Each time the process occurs it should produce exactly one outcome (never zero
or more than one). The probability of an outcome is a measure of the likeliness
that it will occur. It is given as a real number between 0 and 1 inclusive,
where 0 indicates that the outcome cannot occur and 1 indicates that the outcome
must occur.


**Example** Rolling a fair six-sided die could be modelled by a probability
space with sample space <img src="/lectures/tex/dced7542a67b354865f3110e1e97f3e1.svg?invert_in_darkmode&sanitize=true" align=middle width=135.22810454999998pt height=24.65753399999998pt/> and probability function <img src="/lectures/tex/b83c728e70e3858d005e7af8724a31f4.svg?invert_in_darkmode&sanitize=true" align=middle width=17.62562669999999pt height=22.465723500000017pt/>
given as follows.

![](images/L21-P6.png)

A sample space like this one where every outcome has an equal probability is
sometimes called a _uniform sample space_. Outcomes from a uniform sample space
are said to have been take _uniformly at random._

## Events

An _event_ is a subset of the sample space.

**Example** In the die rolling example with <img src="/lectures/tex/dced7542a67b354865f3110e1e97f3e1.svg?invert_in_darkmode&sanitize=true" align=middle width=135.22810454999998pt height=24.65753399999998pt/>, we could
define the event of rolling at least a 3. Formally, this would be the set
<img src="/lectures/tex/f4dc57cef2859c4e72a0bf2213936fbd.svg?invert_in_darkmode&sanitize=true" align=middle width=71.23290569999999pt height=24.65753399999998pt/>. We could also define the event of rolling an odd number as the
set <img src="/lectures/tex/6b1e058bcb7bf32e190f9d1c31ecee00.svg?invert_in_darkmode&sanitize=true" align=middle width=55.70781314999999pt height=24.65753399999998pt/>.

The probability of an event <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> is the sum of the probabilities of the outcomes
in <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>.

## Operations on events

Because events are defined as sets we can perform set operations on them. If <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>
and <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> are events for a sample space <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/>, then

- <img src="/lectures/tex/d125f2409905fcd5b28b7846e0c5d41f.svg?invert_in_darkmode&sanitize=true" align=middle width=43.88690624999999pt height=22.465723500000017pt/> is the event "A or B"
- <img src="/lectures/tex/b0c1a78bbd8d865698d311abad4d5d92.svg?invert_in_darkmode&sanitize=true" align=middle width=43.88690624999999pt height=22.465723500000017pt/> is the event "A and B"
- <img src="/lectures/tex/b0faed3cbd132eca34ea20e3d1bd99c3.svg?invert_in_darkmode&sanitize=true" align=middle width=12.55717814999999pt height=26.97711060000001pt/> is the event "not A"

We always take the sample space as our universal set, so <img src="/lectures/tex/b0faed3cbd132eca34ea20e3d1bd99c3.svg?invert_in_darkmode&sanitize=true" align=middle width=12.55717814999999pt height=26.97711060000001pt/> means <img src="/lectures/tex/4213e756964d2192a0c4121eaa11da50.svg?invert_in_darkmode&sanitize=true" align=middle width=43.447372649999984pt height=22.465723500000017pt/>.

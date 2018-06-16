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

**Exercise** If <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> are any two events then <img src="/lectures/tex/28b5a4a44aa801bbe67b4e1aad986480.svg?invert_in_darkmode&sanitize=true" align=middle width=74.29794074999998pt height=24.65753399999998pt/>

- **A** <img src="/lectures/tex/59dd54b8428391a4142f8b33f6381e55.svg?invert_in_darkmode&sanitize=true" align=middle width=123.8870061pt height=24.65753399999998pt/>
- **B** <img src="/lectures/tex/bcfabe6e1e7795be9ba6d5ee8b986499.svg?invert_in_darkmode&sanitize=true" align=middle width=123.8870061pt height=24.65753399999998pt/>
- **C** <img src="/lectures/tex/e6057fc1eff7a46024cd9658518c5564.svg?invert_in_darkmode&sanitize=true" align=middle width=123.8870061pt height=24.65753399999998pt/>
- **D** <img src="/lectures/tex/c79e9922b7ccbc9502b51f155bdcae1f.svg?invert_in_darkmode&sanitize=true" align=middle width=123.8870061pt height=24.65753399999998pt/>
- **E** <img src="/lectures/tex/e96b2f51cd2189a19551f6d0371c47d5.svg?invert_in_darkmode&sanitize=true" align=middle width=151.28447564999996pt height=24.65753399999998pt/>

**ANS: E** In general <img src="/lectures/tex/3b71f17c7a65a2decc536b81dad249fe.svg?invert_in_darkmode&sanitize=true" align=middle width=74.29794074999998pt height=24.65753399999998pt/> depends on the events _A_ and _B_, but the
only thing you can be sure of is that it is no more than the probability of
either of the individual events.

## Independent events
We say that two events are _independent_ when the occurrence or non-occurrence
of one event does not affect the likelihood of the other occurring.

Two events _A_ and _B_ are _independent_ if

<p align="center"><img src="/lectures/tex/852b42745a108df4fc2dec378be9a47e.svg?invert_in_darkmode&sanitize=true" align=middle width=185.3995143pt height=16.438356pt/></p>

**Example** A binary string of length 3 is generated uniformly at random. The
event _A_ that the first bit is a 1 is independent from the event _B_ that the
second bit is a 1. But _A_ is _not_ independent of the event _C_ that the string
contains exactly two 1s.

Formally, the sample space is <img src="/lectures/tex/0000e783732a19a196904aaaafb6200e.svg?invert_in_darkmode&sanitize=true" align=middle width=297.7856408999999pt height=24.65753399999998pt/>
and <img src="/lectures/tex/cbf67d64a02e3597be2b12954fc34f72.svg?invert_in_darkmode&sanitize=true" align=middle width=68.55929519999998pt height=27.77565449999998pt/> for any <img src="/lectures/tex/2d8cca33f0ee74986943da285a93a659.svg?invert_in_darkmode&sanitize=true" align=middle width=38.82401819999999pt height=22.465723500000017pt/>. So,

<p align="center"><img src="/lectures/tex/f0b72656dd4477da8a9d8001abaf73b6.svg?invert_in_darkmode&sanitize=true" align=middle width=249.73525665pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/87dd06b1cbe048e59093ae32f678dfb2.svg?invert_in_darkmode&sanitize=true" align=middle width=251.664468pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/fc8502b5b118f76aff98f646934a99ee.svg?invert_in_darkmode&sanitize=true" align=middle width=218.96342325pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/8d267e27d807df190abf590b0a3e9225.svg?invert_in_darkmode&sanitize=true" align=middle width=248.92443839999999pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/b107dd928ec9bbb0fc8098d9b8140c7a.svg?invert_in_darkmode&sanitize=true" align=middle width=254.94838874999996pt height=37.099754999999995pt/></p>

So <img src="/lectures/tex/67bdfcb9ff2d468183db604179645a91.svg?invert_in_darkmode&sanitize=true" align=middle width=185.39951429999996pt height=24.65753399999998pt/> but <img src="/lectures/tex/d9a0611dc7268248572bc0d4e0211baa.svg?invert_in_darkmode&sanitize=true" align=middle width=184.66198079999998pt height=24.65753399999998pt/>.

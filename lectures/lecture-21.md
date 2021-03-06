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

<p align="center"><img src="/lectures/tex/1a9a8a8fc00b44c17125fb9132787c99.svg?invert_in_darkmode&sanitize=true" align=middle width=271.6528881pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/79f49b4f89ab0660f27599b6c54c2da8.svg?invert_in_darkmode&sanitize=true" align=middle width=273.5820978pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/107796081fdc231bad6f6d6113ca20a2.svg?invert_in_darkmode&sanitize=true" align=middle width=240.8810547pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/0f7487c7f9eef22331f3acd36c78dd38.svg?invert_in_darkmode&sanitize=true" align=middle width=270.84206819999997pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/3b3c5fdf3cd809747cdff154bbb684dd.svg?invert_in_darkmode&sanitize=true" align=middle width=270.4733031pt height=32.990165999999995pt/></p>

So <img src="/lectures/tex/67bdfcb9ff2d468183db604179645a91.svg?invert_in_darkmode&sanitize=true" align=middle width=185.39951429999996pt height=24.65753399999998pt/> but <img src="/lectures/tex/d9a0611dc7268248572bc0d4e0211baa.svg?invert_in_darkmode&sanitize=true" align=middle width=184.66198079999998pt height=24.65753399999998pt/>.

**Questions**

An integer is chosen uniformly at random from the set <img src="/lectures/tex/7340fdfa704e4d287f978037def5f0d7.svg?invert_in_darkmode&sanitize=true" align=middle width=93.1505553pt height=24.65753399999998pt/>. Let
_A_ be the event that the integer is at most 20. Let _B_ be the event that the
integer is divisible by 6. Let _C_ be the event that the integer's last digit is
a 5.

**21.1** Write _A_, _B_ and _C_ as sets, and find their probabilities.

- <img src="/lectures/tex/bccf39bcbab3cd86ee182b03c51b59e5.svg?invert_in_darkmode&sanitize=true" align=middle width=151.141287pt height=24.65753399999998pt/>. <img src="/lectures/tex/1ed3a15ec1fc9f2710b744379f8b2a27.svg?invert_in_darkmode&sanitize=true" align=middle width=73.18261334999998pt height=27.77565449999998pt/>.
- <img src="/lectures/tex/cbaab7d2f84e5c12f4aaab8bd79f4b38.svg?invert_in_darkmode&sanitize=true" align=middle width=154.84587029999997pt height=24.65753399999998pt/>. <img src="/lectures/tex/5a00d31ff9a258d3be10458af112adb3.svg?invert_in_darkmode&sanitize=true" align=middle width=74.14721984999998pt height=27.77565449999998pt/>.
- <img src="/lectures/tex/01aca8627de5cd59c8300b8b714bfc5b.svg?invert_in_darkmode&sanitize=true" align=middle width=106.98849975pt height=24.65753399999998pt/>. <img src="/lectures/tex/3bfd94d0329987105d44c2878a668837.svg?invert_in_darkmode&sanitize=true" align=middle width=80.33099909999999pt height=27.77565449999998pt/>.

**21.2** Find the probabilities of <img src="/lectures/tex/d125f2409905fcd5b28b7846e0c5d41f.svg?invert_in_darkmode&sanitize=true" align=middle width=43.88690624999999pt height=22.465723500000017pt/>, <img src="/lectures/tex/978f3ca9fdbef1f9be3be8998957b97c.svg?invert_in_darkmode&sanitize=true" align=middle width=43.518141149999984pt height=22.465723500000017pt/>, and <img src="/lectures/tex/534d600a2eccce5f4f2546c54d35350a.svg?invert_in_darkmode&sanitize=true" align=middle width=44.482745999999985pt height=22.465723500000017pt/>. Which
pairs of _A_, _B_, _C_ are mutually exclusive?

<img src="/lectures/tex/975a47ab1dbb2702cb883bb555b18071.svg?invert_in_darkmode&sanitize=true" align=middle width=352.66380434999996pt height=27.77565449999998pt/>. The only pair which are mutually exclusive is _B_ and _C_.

**21.3** Find the probabilities of <img src="/lectures/tex/b0c1a78bbd8d865698d311abad4d5d92.svg?invert_in_darkmode&sanitize=true" align=middle width=43.88690624999999pt height=22.465723500000017pt/>, <img src="/lectures/tex/1d75cab5b9bb7059a01816f390d6e779.svg?invert_in_darkmode&sanitize=true" align=middle width=43.518141149999984pt height=22.465723500000017pt/>, and <img src="/lectures/tex/c460185233a7cde14b5d33dd0e342095.svg?invert_in_darkmode&sanitize=true" align=middle width=44.482745999999985pt height=22.465723500000017pt/>. Which
pairs of <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>, <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/>, <img src="/lectures/tex/9b325b9e31e85137d1de765f43c0f8bc.svg?invert_in_darkmode&sanitize=true" align=middle width=12.92464304999999pt height=22.465723500000017pt/> are independent?

<img src="/lectures/tex/c52170b1a7f90a061b013d5e3cc00f1c.svg?invert_in_darkmode&sanitize=true" align=middle width=345.80532194999995pt height=27.77565449999998pt/>.
The only pair which are independent is A and C.

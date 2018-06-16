# Lecture 22: Conditional probability and Bayes' theorem

## Conditional probability

Conditional probabilities measure the likelihood of an event, given that some
other event occurs.

For events _A_ and _B_, the _conditional probability of A given B_ is

<p align="center"><img src="/lectures/tex/e2a7af74439812f95f0d982d1bb1c0ee.svg?invert_in_darkmode&sanitize=true" align=middle width=158.78763615pt height=38.83491479999999pt/></p>

This definition also implies that <img src="/lectures/tex/5860fd7aa37e7846276de471c1e73221.svg?invert_in_darkmode&sanitize=true" align=middle width=203.25914235pt height=24.65753399999998pt/>.

**Example** A spinner is spun. Let _A_ be the event that the result was at least
3 and _B_ be the event that the result was even. What is <img src="/lectures/tex/55fc1799f50d66462cc650ec731dc094.svg?invert_in_darkmode&sanitize=true" align=middle width=60.59946749999999pt height=24.65753399999998pt/>?

- <img src="/lectures/tex/0e343ab47260a10a7a1aa578ae459819.svg?invert_in_darkmode&sanitize=true" align=middle width=165.28859654999997pt height=27.77565449999998pt/>
- <img src="/lectures/tex/33fa8b89d05880f001355f1b00ad4095.svg?invert_in_darkmode&sanitize=true" align=middle width=256.4208372pt height=27.77565449999998pt/>
- Thus, <img src="/lectures/tex/33cf43c44f88cb083eeb182b58c89ae3.svg?invert_in_darkmode&sanitize=true" align=middle width=205.79041394999996pt height=37.54198139999998pt/>.

**Example** A binary string of length 6 is generated uniformly at random. Let
_A_ be the event that is the first bit is a 1 and _B_ be the event that the
string contains two 1s. What is <img src="/lectures/tex/55fc1799f50d66462cc650ec731dc094.svg?invert_in_darkmode&sanitize=true" align=middle width=60.59946749999999pt height=24.65753399999998pt/>?

There are <img src="/lectures/tex/c3a4aa729873ec54312d9af87608014d.svg?invert_in_darkmode&sanitize=true" align=middle width=14.771756999999988pt height=26.76175259999998pt/> strings in our sample space. Now <img src="/lectures/tex/b0c1a78bbd8d865698d311abad4d5d92.svg?invert_in_darkmode&sanitize=true" align=middle width=43.88690624999999pt height=22.465723500000017pt/> occurs when the
first bit is a 1 and the rest of the string contains one 1. There are
<img src="/lectures/tex/bb13ebf60d342c9e474fdde6c7b7e422.svg?invert_in_darkmode&sanitize=true" align=middle width=21.621118199999987pt height=29.419440600000005pt/> such strings and so <img src="/lectures/tex/a4ab93c2ac3d07b6a7744ad664cb66f0.svg?invert_in_darkmode&sanitize=true" align=middle width=116.56729589999999pt height=43.068412200000004pt/>.
Also, there are <img src="/lectures/tex/cce20003de73186579b665e0a0cdce0f.svg?invert_in_darkmode&sanitize=true" align=middle width=21.621118199999987pt height=29.419440600000005pt/> strings containing two 1s and so <img src="/lectures/tex/d55866b63b168d385532761ccb0f5f94.svg?invert_in_darkmode&sanitize=true" align=middle width=85.97379944999999pt height=43.068412200000004pt/>. Thus,

<p align="center"><img src="/lectures/tex/939af30e0be5c81bda5857bd2e496f51.svg?invert_in_darkmode&sanitize=true" align=middle width=240.35357775pt height=45.528984599999994pt/></p>

**Exercise** A normal die is rolled. Let _A_ be the event that the result is an
odd number. Let _B_ be the event that the result is a square number.

- **A:** <img src="/lectures/tex/305470adb8ae7a49e1f58a418dfcab14.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/ee337f7160622a3b2a96bdaaaa9d5f6d.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>
- **B:** <img src="/lectures/tex/305470adb8ae7a49e1f58a418dfcab14.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/da76a6832f25f6f26a36a40734d3a2d2.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>
- **C:** <img src="/lectures/tex/5443b7403614410d29d8cf88d066e473.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/6e6c73f707c99eeac6fe5d344c296bc7.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>
- **D:** <img src="/lectures/tex/32405c6978e4b4a9750a08bd29701121.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/ee337f7160622a3b2a96bdaaaa9d5f6d.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>

**ANS: B:** Since <img src="/lectures/tex/c74f8d51bd5e63b0732f4d8b00a59cff.svg?invert_in_darkmode&sanitize=true" align=middle width=90.46215914999999pt height=24.65753399999998pt/> we see that <img src="/lectures/tex/714d73b92779626634bdaeede1500980.svg?invert_in_darkmode&sanitize=true" align=middle width=104.74071629999999pt height=27.77565449999998pt/>.
So

<p align="center"><img src="/lectures/tex/85a4e1706b50c55f8ba00bef2691feb6.svg?invert_in_darkmode&sanitize=true" align=middle width=229.2301968pt height=43.715357399999995pt/></p>

<p align="center"><img src="/lectures/tex/6edf12e0b00d973677d169ad6c0555a7.svg?invert_in_darkmode&sanitize=true" align=middle width=229.2301968pt height=43.715357399999995pt/></p>

## Independence again

Our definition of conditional probability gives us another way of defining
independence. We can say that events _A_ and _B_ are independent if <img src="/lectures/tex/3698ec15338daacbb6b8469c4bacb07b.svg?invert_in_darkmode&sanitize=true" align=middle width=125.25693674999998pt height=24.65753399999998pt/>.

**Exercise**

The previous example considered the events _A_ (odd number) and _B_ (square
number) and we calculated that <img src="/lectures/tex/305470adb8ae7a49e1f58a418dfcab14.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/0d3b21282e83b5d3cabe39e81520095a.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>.

- **A:** Event _A_ is independent of Event _B_, and vice versa.
- **B:** The events _A_ and _B_ are NOT independent because a die roll of 1 is
  included in both.
- **C:** The event _A_ is independent of _B_ but the event _B_ is NOT
  independent of _A_.
- **D:** The event _B_ is independent of _A_ but the event _A_ is NOT
  independent of _B_.

**ANS: A** because <img src="/lectures/tex/fdbac099ba07864a1c429f613f55adcb.svg?invert_in_darkmode&sanitize=true" align=middle width=157.67230379999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/a29cf123fae3e1f828571cb483d1047d.svg?invert_in_darkmode&sanitize=true" align=middle width=158.63690864999998pt height=27.77565449999998pt/>. (Either of these is enough to show that these events are independent.
Note that C and D are red herrings; the situations they describe are impossible
regardless of what A and B are.)

## Independent repeated trials

Generally if we perform exactly the same action multiple times, the results for
each trial will be independent of the others. For example, if we roll a die
twice, then the result of the first roll will be independent of the result of
the second.

For two independent repeated trials, each form a sample space _S_, our overall
sample space is <img src="/lectures/tex/e0b21bbf35b24a4af54eea3d1cdbd61f.svg?invert_in_darkmode&sanitize=true" align=middle width=42.145974749999986pt height=22.465723500000017pt/> and our probability function will be given by
<img src="/lectures/tex/f0144e8869015a814b7d18535f6dc656.svg?invert_in_darkmode&sanitize=true" align=middle width=196.30148505pt height=24.65753399999998pt/>. For three independent repeated trials the
sample space is <img src="/lectures/tex/251c3ff6cc925da9ef3969252419f752.svg?invert_in_darkmode&sanitize=true" align=middle width=73.26454904999999pt height=22.465723500000017pt/> and the probability function <img src="/lectures/tex/d77799584eb9a41ef773c1651bae18c9.svg?invert_in_darkmode&sanitize=true" align=middle width=266.9179457999999pt height=24.65753399999998pt/>, and so on.

**Example** The spinner from the previous example is spun twice. What is the
probability that the results add to 5?

![](images/L22-P10.png)

A total of 5 can be obtained as <img src="/lectures/tex/095fd82910e4596f519accd5a543590c.svg?invert_in_darkmode&sanitize=true" align=middle width=168.03659069999998pt height=24.65753399999998pt/>. Because the spins
are independent:

<p align="center"><img src="/lectures/tex/111f4a655509fda34b3a4c9ea810202f.svg?invert_in_darkmode&sanitize=true" align=middle width=262.46544885pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/240ce693b0e076b2980f3d9b02bf7d1d.svg?invert_in_darkmode&sanitize=true" align=middle width=262.46544885pt height=32.990165999999995pt/></p>

So, because <img src="/lectures/tex/ebff16cb47cfd3ef691b89f732149219.svg?invert_in_darkmode&sanitize=true" align=middle width=124.20097304999997pt height=24.65753399999998pt/> and <img src="/lectures/tex/c2b3cecb67a773c47721114a4b95184e.svg?invert_in_darkmode&sanitize=true" align=middle width=36.52973609999999pt height=24.65753399999998pt/> are mutually exclusive, the
probability of the total being 5 is <img src="/lectures/tex/0294f8d2c9aae9a3b51a4f1b759945f7.svg?invert_in_darkmode&sanitize=true" align=middle width=163.49741594999998pt height=27.77565449999998pt/>.

**Questions**

**22.1** An integer is selected uniformly at random from the set <img src="/lectures/tex/c5638b1f94bb0102dab18e7282cebf4d.svg?invert_in_darkmode&sanitize=true" align=middle width=93.1505553pt height=24.65753399999998pt/>. What is the probability that it is divisible by 5, given that it is odd?

Let <img src="/lectures/tex/c32b6d0783d88878c8e874693b55144d.svg?invert_in_darkmode&sanitize=true" align=middle width=106.39266165pt height=24.65753399999998pt/> be the event that the chosen number is divisible by 5. Let
<img src="/lectures/tex/1d20e8014a8958eb2e98b19bc6211be8.svg?invert_in_darkmode&sanitize=true" align=middle width=193.20193859999998pt height=24.65753399999998pt/> be the event that the chosen number is odd.

<p align="center"><img src="/lectures/tex/c0205a74462bbcb2f136922b4f0278ed.svg?invert_in_darkmode&sanitize=true" align=middle width=275.64565875pt height=38.83491479999999pt/></p>

**22.2** A standard die is rolled twice. What is the probability that the first
roll is a 1, given that the sum of the rolls is 6?

- Let _A_ be the event that the first roll is 1.
- Let _B_ be the event that the sum of the rolls is 6 (which happens as <img src="/lectures/tex/ad1a89bba2abd17952a5d06506920294.svg?invert_in_darkmode&sanitize=true" align=middle width=211.87158299999996pt height=21.18721440000001pt/>).

<p align="center"><img src="/lectures/tex/e036a10d7e7adb8877984a09ededf139.svg?invert_in_darkmode&sanitize=true" align=middle width=275.64565875pt height=38.83491479999999pt/></p>

## Bayes' theorem

Bayes' theorem gives a way of calculating the conditional probability of an
event _A_ given an event _B_ when we already know the probabilities of _A_, of
_B_ given _A_, and of _B_ given <img src="/lectures/tex/b0faed3cbd132eca34ea20e3d1bd99c3.svg?invert_in_darkmode&sanitize=true" align=middle width=12.55717814999999pt height=26.97711060000001pt/>.

**Bayes' theorem.** For events _A_ and _B_,

<p align="center"><img src="/lectures/tex/06ed8a6d73ed6ad54dd1a9bf2d812904.svg?invert_in_darkmode&sanitize=true" align=middle width=316.73880314999997pt height=39.23922585pt/></p>

**Example** The Australian government decides to crack down vampires. They
develop a test for vampirism that is right 99% of the time and decide to screen
everyone in the country. Suppose there are 100 vampires in the population of 24
million. We would guess that the test would come up positive for 99 of the 100
vampires, but also for 239 999 humans.

We are assuming that the conditional probability of testing positive given
you're a vampire is 0.99. But what is the conditional probability of being a
vampire given that you tested positive?

<p align="center"><img src="/lectures/tex/5ba7b32b310497d4e428cba38b573f38.svg?invert_in_darkmode&sanitize=true" align=middle width=319.9350429pt height=39.23922585pt/></p>
<p align="center"><img src="/lectures/tex/439436f349faea3099d6a6b0dc6e3a8a.svg?invert_in_darkmode&sanitize=true" align=middle width=455.67134085pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/6b926036ccf5e1c9a8b1e9a6ae892af6.svg?invert_in_darkmode&sanitize=true" align=middle width=105.1689969pt height=34.3600389pt/></p>
<p align="center"><img src="/lectures/tex/e303162dae9d0a0fa55bc9ed7126d3a3.svg?invert_in_darkmode&sanitize=true" align=middle width=63.0138036pt height=10.5936072pt/></p>
